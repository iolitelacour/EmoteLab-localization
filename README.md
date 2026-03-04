# EmoteLab translations

Thank you for helping translate [EmoteLab](https://emotelab.app/). This repository holds **translation files** that contributors edit. Each file is a CSV (spreadsheet) you can open in Excel, Google Sheets, or any text editor.

## What's in this repo

Files are grouped **by language** (e.g. `fr/`, `ja/`, `ko/`). In each language folder you’ll find:

- **Main Menu String Table_language code.csv**: In-app UI text (menus, buttons, messages).
- **CoffeeBean/**: Names for CoffeeBean assets (animations, color groups, parts, sliders).

File names end with a **language code**, e.g. `_fr` (French), `_ja` (Japanese), `_ko` (Korean).

## Collaboration & translation rules

- **Volunteer translations & usage**  
  - All translations are contributed on a volunteer basis.  
  - By submitting translations (via pull requests, issues, or files shared directly with the maintainer), you confirm that you have the right to contribute them and you authorize the EmoteLab project to use, modify, and distribute them, including in commercial versions of EmoteLab.

- **Work with other translators**  
  - Before starting work on a new language or making large changes, please join the [EmoteLab Discord translation channel](https://discord.gg/eHmdpxFB2k). Not all translators use Git, so coordination and discussion happen there.  
  - Respect other translators' work. Avoid overwriting large sections without discussing first.  
  - If you think an existing translation is not good, raise it politely in the translation channel and try to reach a consensus with other speakers of that language before changing it.  
  - The project maintainer does not speak every language, so they cannot always judge which translation is best. In case of conflicts, the maintainer will usually follow the recommendations and consensus from native speakers in the translation channel when deciding whether to accept a pull request. **Pull requests are only considered from people who are known in the Discord translation channel;** PRs from others will not be accepted.

## How to translate

1. **Get the files**  
   - **Using Git:** Fork this repo, make your edits on your fork, then open a Pull Request to submit your changes.  
   - **Without Git:** On this repo’s GitHub page, click **Code** → **Download ZIP**. Unzip it, edit the CSV(s), then send the finished file(s) to the project maintainer.  
   Questions? Contact the maintainer via Discord.

2. **Open the CSV**  
   Open the file for your language (e.g. `Main Menu String Table_zh.csv`) in Excel, Google Sheets, or a text editor.  
   - **First column (Key):** Do not change. It identifies each string.  
   - **Second column (en):** English reference. Do not change.  
   - **Third column (your language):** Put your translation here. This is the only column you need to edit.

3. **Save and send back**  
   Save as CSV (UTF-8). Send the updated file(s) to the project maintainer, or open a Pull Request if you use GitHub.

## Tips

- Keep the same row order; don't add or remove rows.  
- If a string doesn't need translation (e.g. names, brands), you can leave the English text.  
- For placeholders like `{0}` in the English text, keep them in the same place in your translation.

## Questions?

Contact the EmoteLab project maintainer via Discord. Thank you for contributing.
