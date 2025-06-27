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

### [6.3.11] - 2025-06-27

#### Fixed
- Minor margin fixes on wyswiyg images, non-page node elements

### [6.3.10] - 2025-06-24

#### Changed
- Adjusted calendar styling to improve appearance, alignment and consistency

### [6.3.9] - 2025-03-05

#### Fixed
- Alignment styling fixes for link wrapped wysiwyg media
- Removed external link icon from being appended to linked images
- Removed hyphenated word breaks from paragraph text

### [6.3.8] - 2025-02-25

#### Changed
- Adjusted all banner type (fullwidth, content and sidebar) styling as per base Figma design updates
- Adjusted card pseudo styling as per base Figma design updates
- Adjusted horizontal card styling to include 1:1 image variant

### [6.3.7] - 2025-01-31

#### Fixed
- Glitch from D10.3 that removed hook for system message templates/styling. Added community recommended fix.
- Missing .site-logo class on logo template
- Adjusted page template to fix content not going full width when sidebar empty
- Moved paragraph line-height and max-width within copy.scss to upanupstarter to become included in ckeditor styling
- Fixes to figure/media styling to improve consistency with ckeditor, adjustments/bug fixes to margins
#### Added
- FDK compatible button classes: .button--default-fdk and .button--emphasis-fdk
#### Changed
- Changed $line-width to match upanupstarter, 80ch -> 75ch

### [6.3.6] - 2024-12-03

#### Fixed
- Added white background to `.ck-content` to fix colouring of content within CKEditor when using dark mode

### [6.3.5] - 2024-06-27

#### added
- Added meta tag to avoid errant dark mode

#### Changed
- Styled table caption like an h3

#### Fixed
- Accordion group toggle arrow now faces correct direction

### [6.3.4] - 2024-06-14

#### Changed
- Changed `header.twig` include to have initial `aria-label` attribute on the mobile menu trigger and mobile search trigger elements

### [6.3.3] - 2024-06-05

#### Added
- Added psuedo elements to 2nd level desktop menu flyouts to prevent 3rd level menu from closing while moving cursor over

#### Changed
- Adjusted disabled radio & checkbox colors
– Adjusted calendar styling to remove double row border

### [6.3.2] - 2024-06-03

#### Added
- Added CSS for margin-top of content rows when the body field is present on detail views

### [6.3.1] - 2024-04-30

#### Changed
- Removed media query from `main-desktop.scss` until better improvement is ready

### [6.3.0] - 2024-04-30

#### Changed
- Split the `main.scss` folder into `main-desktop.scss` and `main-mobile.scss` files

### [6.2.2] - 2024-04-29

#### Added
- Added `color: $font` to the `html.scss` file

### [6.2.1] - 2024-04-26

#### Fixed
- Moved BC Sans stuff out of `_font-family.scss` and into it's own file so it can be included in `ckeditor.scss`

### [6.2.0] - 2024-04-10

#### Added
- Added Feedbucket boolean and token in `html.html.twig`

### [6.1.0] - 2024-04-03

#### Changed
- Changed font family from _Noto Sans_ to _BC Sans_

### [6.0.1] - 2024-04-02

#### Fixed
- Fixed issue where the search form wasn't loading styling from a view filter CSS file

### [6.0.0] - 2024-04-02

#### Added
- Theme version to `upanupstarter.info.yml`

#### Changed
- Changed paths from `themes/custom` to `themes/contrib`

### [5.0.0] - 2024-03-22

#### Added
- Removed margin on first content row if it's the next element after the page title

#### Changed
- Styling updated for new dynamic quicklinks mobile filter markup (same as desktop)

#### Fixed
- Fixed styling for checkbox, radio elements with title's shown before the input

### [4.5.4] - 2024-03-22

### Changed
- Changed dynamic quicklinks filter selector to be more universal (to accommodate new upanupbase a11y markup adjustments)

### [4.5.3] - 2024-03-22

### Fixed
- Added missing focus appearance for scrollable tables

### [4.5.2] - 2024-03-19

#### Changed
- Changed `page--front.html.twig` to `page--homepage.html.twig` to avoid issues with non-_Homepage_ nodes being used as the front page

### [4.5.1] - 2024-03-15

#### Added
- Added `dark-site.scss` to compile the scss/css in the `dark_site` library into one css file for use on a static dark site

### [4.5.0] - 2024-03-15

#### Added
- Templates, styling for 'dark site' nodes

### [4.4.5] - 2024-03-13

#### Changed
- Updates to calendar styling

### [4.4.4] - 2024-03-13

#### Fixed
- Corrected line height to `<p>` tags within blockquotes

#### Changed
- Changed out core search autocomplete ajax throbber to base themed one, and hid when not active

### [4.4.3] - 2024-03-12

#### Fixed
- Removed padding on header search input submit to rectify odd spacing on some sites
- Added ajax styling so base ajax gif is being used

### [4.4.2] - 2024-03-12

#### Fixed
- Mobile Safari: Select font color, Date and Time input font color and minimum heights + widths.

### [4.4.1] - 2024-03-12

#### Removed
- Removed bold font weight on smartdate, date fields in content due to collateral

### [4.4.0] - 2024-03-12

#### Added
- Library override for `calendar-view.default.css` to apply some slightly opionionated stlying

### [4.3.1] - 2024-03-11

#### Added
- Added appearance styling for webkit and moz to date/time inputs to fix iOS bug

### [4.3.0] - 2024-03-08

#### Added
- Added libraries for new "table of contents" component

### [4.2.0] - 2024-03-07

#### Added
- Added `tabs` library to add styling to similar library in `upanupbase`

### [4.1.2] - 2024-02-29

#### Changed
- Changed Font Awesome kit js

### [4.1.1] - 2024-02-16

#### Fixed
- Margin adjustments to improve spacing of webform elements

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
