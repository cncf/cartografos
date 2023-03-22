# Localization

Now that the first version of the cloud native glossary is live,
we'd love to start localizing it into different languages. 

 - [Initiate a new localization team](#initiating-a-new-localization-team)
 - [Join an existing localization team](#join-an-existing-localization-team)
 - [Localization team guidelines](#localization-team-guidelines)

Contributions to improving the following localization guides and localization policies are also welcome.

---

# Initiating a new localization

## Basic requirements to initiate a new localization team

- The Cloud Native Maturity Model website does not have a localization for your language yet
  - ask in the [cartografos-wg channel in Slack](https://cloud-native.slack.com/archives/C026EQ8LU2Z). There may be a group of volunteers who haven't gotten started yet.

## Instructions to initiate a new localization

### 1. Join the Slack channel and say hello

If you're interested in creating a new localization, whether you have a team or are on your own, please join the #cartografos-wg channel on the CNCF slack and say hi. If you are looking for more volunteers, let everyone in the channel know. There may be someone in there looking for a team as well. 

### 2. Configuring a new language

Open a PR with the localization initiation.

#### 2-1. Adding a new language setting to site configuration

To add a new language to the site, modify [config.toml](https://github.com/cncf/cartografos/blob/main/website/config.toml#L47).

The `[languages]` block of `config.toml` is used to set the language. For instance, `[languages.en]` stands for English and `[languages.de]` for German language configuration. Go to the `[languages]` block in `config.toml` and add a new block for your language-specific configuration. For instance, the German localization team added its `[languages.de]` block after the `[languages.en]` block.

- Example of `New language block for /config.toml`
  ```diff
  [languages]
  [languages.en]
  title = "Cloud Native Maturity Model"
  description = "The intent of the Cloud Native Maturity Model is to help you move from inception through to full adoption of cloud native technologies using the CNCF landscape to achieve the full benefits of running scalable applications in modern, dynamic environments in public and hybrid clouds."
  languageName ="English"
  contentDir = "content/en"
  # Weight used for sorting.
  weight = 1
  
  +[languages.de]
  +title = "Cloud Native Maturity Model"
  +description = "Das Cloud Native Maturity Model soll Ihnen dabei helfen, sich von den Anfängen bis zur vollständigen Übernahme von Cloud Native-Technologien unter Verwendung der CNCF-Landschaft zu bewegen, um alle Vorteile der Ausführung skalierbarer Anwendungen in modernen, dynamischen Umgebungen in öffentlichen und hybriden Clouds zu nutzen."
  +languageName = "Deutsch"
  +contentDir = "content/de"
  +weight = 2
  ```

#### 3-2. Adding a file for site strings

`website/i18n/<localization>.toml` sets up language-specific site strings.
For a new localization, add a file `website/i18n/<localization>.toml` based on `website/i18n/en.toml`.
`other = "<English site strings>"` in `website/i18n/<localization>.toml` can be translated.

#### 3-3. Adding a new localization directory

Translated Glossary terms are saved in the appropriate language directory inside `website/content/`.

Create a subdirectory in `content` and name it using the appropriate two-letter language code (`website/content/<localization>`).
For example, 
```
contents/en
contents/de
...
```

#### 3-4. Minimum required content

Localize content and save to `website/content/<localization>`.

Your PR should include all pages because it makes no sense to only tranlate part of the Cloud Native Maturity Model.

#### 3-5. Check configuration works and open a PR

Before opening a PR, ensure the website with the updated configuration works by running [Hugo server](https://github.com/cncf/cartografos/blob/main/website/content/contribute/_index.md#contributing-to-the-website). If it does, select the new language on the local website.

Open a PR and wait for it to be reviewed by the [maintainers](https://github.com/cncf/cartografos/blob/main/OWNERS).

### 5. Merging the PR branch into `main` branch

Once the PR is merged, the localized content will go live on its website 🎉
