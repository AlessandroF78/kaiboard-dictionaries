# KaiBoard Autocorrect Language Packs

Offline autocorrect dictionaries for KaiBoard multilingual keyboard.

## Supported Languages

| Language | Code | Dictionary Size |
|----------|------|----------------|
| Italian | it_IT | ~340 KB |
| German | de_DE | ~1.03 MB |
| Greek | el_GR | ~5.46 MB |
| English (US) | en_US | ~182 KB |
| Spanish | es_ES | ~230 KB |
| French | fr_FR | ~328 KB |
| Georgian | ka_GE | ~539 KB |
| Dutch | nl_NL | ~1.9 MB |
| Polish | pl_PL | ~4.7 MB |
| Portuguese | pt_PT | ~1.54 MB |
| Turkish | tr_TR | ~37.5 MB |
| Russian | ru_RU | ~595 KB |
| Ukrainian | uk_UA | ~1.83 MB |

## Dictionary Format

All dictionaries use the **Hunspell** format:
- `.dic` file: word list
- `.aff` file: affix rules

Each language pack is distributed as a ZIP file containing both files.

## Download

Download individual language packs from the [Releases](https://github.com/AlessandroF78/kaiboard-dictionaries/releases) page.

Direct download links are available in the [`version.json`](version.json) file.

## Usage in KaiBoard

KaiBoard automatically downloads the required language pack when you switch keyboard layout or when a dictionary is needed for autocorrection.

The app checks the `version.json` file to get the latest dictionary URLs and downloads them on demand.

## Version Control

- Current version: **1.1**
- Release date: 2026-02-11
- Check [`version.json`](version.json) for programmatic access to version information

## License

Dictionaries are sourced from:
- LibreOffice Dictionaries (MPL 2.0 / LGPL)
- Mozilla Firefox Language Tools

Each dictionary maintains its original license. See individual dictionary sources for specific licensing information.

## Source

All dictionaries were extracted and processed from LibreOffice 2025 language packs, ensuring high quality and up-to-date word lists.
