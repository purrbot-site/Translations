> # Archived
> This repository has been archived.
> Translations are now handled on https://lang.purrbot.site
> If you want to contribute towards the project, contact Andre_601#0601 on the [Support Discord](https://purrbot.site/discord)

## Translations
\*Purr* allows to have a per-guild language to be set.  
The language used can be set through the `.language` command (Default is english (en)).

### Adding own translations
You may add your own translation for \*Purr* to be used in the future.  
In order to do this, copy the content of the [en.json](/lang/en.json), create a new file named after the language code of your language, add the content of the en.json to it and start translating!

As a thank you for translating the bot will you be mentioned in this readme and become a part of the translator-team of this organisation.

Please follow those guidelines listed below:
- Do NOT
  - Alter, add or remove placeholders. A placeholder starts with a `{` and ends with a `}` (`{example}`).  
  You may change its position if f.e. your language has a different direction.
  - Add, remove or edit unicode. Unicode starts with a `\u` followed by 4 charactes.  
  Only add, remove or edit them when it is unavoidable. For example, when your language (somehow) doesn't support it.
- You should
  - Try to keep commits at a minimum.  
  It's okay to do commits, if files have changed since you started the PR, but your PR shouldn't start with 10+ commits.  
  Use the "Squash and merge" or "Rebase and merge" options when needed.

### Additional information
Some languages may have different meanings for the same character, or have a *feel* to it that depends on what personality the character is.  
Here is a small summary of \*Purr*'s personality for those cases:  
> \*Purr* is a caring person. She loves to help others and to bring joy, fun and entertainment. She's happy when others are happy.  
> She's very protective about her little sister \*Snuggle* and won't allow people to do certain actions to her (e.g. Kissing her using \*Purr*'s commands).  
> She may also have a dirty mind at certain points and will also make such comments in those cases (Like when someone uses the `.bj` command on themself.
>
> She's married to another women and very happy about this.

## Supported languages
This is an up to date list of translations available for you.

| Language: | Code*: | Translated by: |
| --------- | ------ | -------------- |
| English   | en     | Andre_601      |
| German    | de     | Andre_601      |
| Korean    | ko     | Katinor        |
| Russian   | ru     | TheDanWolf     |

*The code may be used in the `.language set <language>` command.
