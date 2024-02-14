# upanupstarter

Upanup's starter theme for all projects.

## Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Example:

```
### [#.#.#] - YYYY-MM-DD

#### Added
- for new features.

#### Changed
- for changes in existing functionality.

#### Deprecated
- for soon-to-be removed features.

#### Removed
- for now removed features.

#### Fixed
- for any bug fixes.

#### Security
- in case of vulnerabilities.
```

### [Unreleased]

### [4.1.0] - 2024-02-14

#### Fixed
- Fixed/improved <figure> media images where WYSIWYG applies .align-{direction} class (adjusted float, margins and mobile appearance)

#### Changed
- Adjusted conditional check for both hours and label in hours block (so each could appear independently)
- Added default margin below wysiwyg images without captions

### [4.0.1] - 2024-01-19

#### Fixed
- Added `!important` to `left: auto` and `right: auto` for mobile menu third-level items to stop them from appearing off screen

### [4.0.0] - 2024-01-19

#### Changed
- Print styling removed from individual files and into new `*--print.scss` files
- Libraries updated with new `*--print.css` files
- `upanupstarter.info.yml` updated with new libraries from `upanupbase`
- Updated `libraries-extend` for `upanupbase/nav`

### [3.1.2] - 2023-12-05

#### Fixed
- Removed Google Fonts line from `ckeditor5-stylesheets`, added `@import` of fonts in `ckeditor.scss`

### [3.1.1] - 2023-11-30

#### Added
- Print styling for accordions

#### Fixed
- Removed straggling `$int` color variables

### [3.1.0] - 2023-11-20

#### Changed
- Changed color variables: removed `$active-` and `$int-`, replaced w/ named variables (i.e. `$teal`)

### [3.0.2] - 2023-11-03

#### Fixed
- Fixed button hover so it uses the `underline--hover` mixin

### [3.0.1] - 2023-11-02

#### Fixed
- Removed `::after` icon on external links in CKEditor (given that Font Awesome is not loaded there)

### [3.0.0] - 2023-10-31

#### Changed
- CKEditor styles now target CK5
- D10 listed as core requirement

### [2.5.1] - 2023-10-27

#### Fixed
- Fixed missing prefixes from last compilation

#### Added
- Added generic `figure`, `figcaption` styling

### [2.5.0] - 2023-10-27

#### Fixed
- Fixed swiper js & image-slider css being included when swiper not present

#### Changed
- Included compatibility for single image to adopt content banner styling

### [2.4.1] - 2023-10-20

#### Changed
- Changed outline style from `dashed` to `solid`

### [2.4.0] - 2023-10-17

#### Added
- Added styling for Fullcalendar block

### [2.3.0] - 2023-08-29

#### Fixed
- Fixed imports to compile base element styles into ckeditor.css file

### [2.2.0] - 2023-08-28

#### Fixed
- Improved browser font scaling for button--ui mixin
- Fixed spacing for banner captions
- Fixed minimum size for slider control buttons

### [2.1.0] - 2023-08-09

#### Added
- Added `notice` library for new "notice" component

### [2.0.0] - 2023-07-05

#### Changed
- Updated `prepros.config` to ignore .scss files
- Renamed scss folder to scss-css
- Compiled all .scss files using Live Sass Compiler VS Code extension

#### Removed
- Removed css folder

### [1.0.0] - 2023-06-20

#### Added
- Initial commit