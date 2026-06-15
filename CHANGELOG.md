# Changelog

## 0.2.1 - 2026-06-15
- Updated test-file.txt, removing redundant example texts.

## 0.2.0 - 2026-06-15
- Fixed typo in language aliases (`TXT Syntex` → `TXT Syntax`, `Text Syntex` → `Text Syntax`).
- Added support for `.toml`, `.editorconfig` and `.gitconfig` file extensions.
- Added keywords `toml`, `editorconfig`, `gitconfig` to marketplace metadata.
- Added `;` as a recognized line comment in `language-configuration.json`.
- Fixed comment pattern to be anchored at line start, preventing URL fragments (`#anchor`) from being highlighted as comments.
- Fixed ALL CAPS heading pattern to exclude lines containing `=` or `:`, avoiding conflict with `KEY=VALUE` highlights.
- Added boolean constant highlighting: `true`, `false`, `yes`, `no`, `on`, `off` (case-insensitive).
- Added date and timestamp highlighting: ISO dates (`2024-01-15`), datetime (`T08:00:00`) and time (`10:32:45`).
- Added full-line coloring for log severity lines: `ERROR`/`FAILED` (red), `WARN`/`WARNING` (yellow), `SUCCESS`/`PASS`/`PASSED` (green).
- Added backtick string highlighting.
- Added inline comments to grammar patterns for maintainability.
- Updated README.MD to document folding syntax, new extensions and new highlighting features.
- Updated test-file.txt to cover all new cases.

## 0.1.2 - 2026-06-14
- Updated README.MD screenshot descriptions.

## 0.1.1 - 2026-06-14
- Updated marketplace extension category to use only `Programming Languages`.

## 0.1.0 - 2026-06-13
- Stable version.

## 0.0.4 - 2026-06-13
- Added images section.
- Added icon and screenshot images.
- Added test-file.txt.
- Added the SUPPORT.MD file.
- Updated the package.json.

## 0.0.3 - 2026-06-12
- Removed `indentationRules` from `language-configuration.json`.
- Consolidated comment patterns in `txt.tmLanguage.json`.
- Improved performance for big plain-text files.

## 0.0.2 - 2026-06-11
- Fixed highlighting on titles and sections.
- Fixed language-configuration.json symbols.
- Fixed text.tmLanguage.json conventions.

## 0.0.1 - 2026-06-10
- First alpha release to tests only.
- Added support for TXT, LOG, INI, CONF, CFG, ENV and PROPERTIES files.
- Added highlighting for titles and sections.
- Added highlighting for comments starting with `#` and `;`.
- Added highlighting for sections in the `[section]` format.
- Added highlighting for key/value pairs.
- Added highlighting for URLs, emails and numbers.
- Added highlighting for important words such as `TODO`, `FIXME`, `NOTE`, `INFO`, `DEBUG`, `WARN`, `WARNING`, `ERROR`, `FAILED`, `SUCCESS`, `PASS` and `PASSED`.
- Added basic folding support for `Section`, `Region`, `Step`, `[section]` and `---`.