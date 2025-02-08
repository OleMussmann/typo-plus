# Typo-Plus, a Typo Theme Extension

This theme extension tweaks the look and feel of the [typo theme](https://github.com/tomfran/typo) and adds extra features. Some of those might be added upstream eventually.

## Features
### Added
- A "Slides" page for listing presentation
- A "Slide" layout for showcasing a presentation
- [Mermaid](http://mermaid.js.org/) diagram color scheme changes based on light-/dark mode

### Changed
- Uses the [iceberg](https://github.com/cocopon/iceberg.vim) colorscheme
- Changed fonts
    - [Habibi](https://fonts.google.com/specimen/Habibi) by [Magnus Gaarde](http://skriftklog.dk/) for headings
    - [Average](https://fontforge.io/best-pairings/average/) by [Eduardo Rodríguez Tunni](https://www.tipo.net.ar/)  for running text
    - [Victor Mono](https://rubjo.github.io/victor-mono/) by [Rune Bjørnerås](https://github.com/rubjo) for `code`
- Adjusted font sizes and margins
- Justified body text
- Introduction of `»` style elements

## Installation

### Submodule
```
git submodule add --depth=1 https://github.com/OleMussmann/typo-plus.git themes/typo-plus
git submodule update --init --recursive
```

## Usage

Add `typo-plus` _before_ `typo` in your hugo config, e.g.

```
theme = ['typo-plus', 'typo']
```

## Licenses
This extension is licensed under the [MIT license](./LICENSE). The contained fonts are licensed under the [SIL Open Font License](https://openfontlicense.org/open-font-license-official-text/):

- [Average](https://fontforge.io/best-pairings/average/)  
  Copyright (c) 2012 by The Average Project Authors (https://github.com/etunni/average).

- [Habibi](https://fonts.google.com/specimen/Habibi)  
  Copyright (c) 2011 by Sorkin Type Co (https://www.sorkintype.com), with Reserved Font Name "Habibi".

- [Victor Mono](https://rubjo.github.io/victor-mono/)  
  Copyright (c) 2023 by The Victor Mono Project Authors (https://github.com/rubjo/victor-mono-font).
