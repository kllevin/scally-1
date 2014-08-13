# TODO

## Global

- Create JIRA tickets.
- Replace all instances of `/* endif */` with `// endif`.
- Remove all instances of `== true` for Sass `@if` statements.
- Have a setting that allows you to dictate when everything goes linear e.g. **Grid**?
- Make sure all instances of `px` for borders and shadows use `rem`.
- Setup AutoPrefixer.
- Link up CodePen to Scally stylesheet.
- `_tech-debt.scss` file.


---


## Core

- Make sure all comments are formatted properly:
  - 2 line breaks after page title comments.
  - 4 line breaks between section heading comments.
  - 2 line breaks between heading comments.
  - No full stops after URL's.
  - Full stop after everything except `//` comments and URL's.
  - Bullet list for `@credit` references.
- `style.scss`.
- New `box-sizing` reset technique.
- Make sure all instances of `px` for borders and shadows use `rem`.
- Sass 3.3. application e.g. Sass maps for vars.
- Mixins:
  - xx

## Layout

- Don't couple `container-bg-color-x` with base `.container`.

## Components

- Fancy `select` (see 'Parking project').
- Block quote.

## Utilities

- Every Utility needs to be applied via all the main breakpoints (see Alec).
- Spacing, use all spacing `var`s and apply to `margin` and `padding` on all sides of the box.
- State?
- Cursor?
- Positioning:
  - Top left.
  - Top right.
  - Bottom left.
  - Bottom right.
  - Stretch (pulls each corner/side so that it stretches to it's parent):
    - All (`top: 0; bottom: 0; left: 0; right: 0;`).
    - Sides (`left: 0; right: 0;`).
    - Ends (`top: 0; bottom: 0;`).
- Ideas:
  - <http://jsfiddle.net/csswizardry/25741myb/>.


---


## Other

### Documentation

- Update CSS Guidelines.

### Sass Newness

- <http://visuellegedanken.de/2014-03-29/using-bem-syntax-with-sass-3-3/>
- <http://robots.thoughtbot.com/removing-sass-duplication>
- <http://viget.com/extend/sass-maps-are-awesome>
- <http://unakravets.tumblr.com/post/78744593423/sass-snippets-the-almighty-ampersand>

### Put to the team

- Dynamically pull in Normalize?
- Have a vendor partial for 3rd party styles e.g. Google Map images (`.gm-style`)?

### CodePen Demo styles

    /* DEMO STYLES */
    body {padding: 40px !important;}

    .demo-heading {
      background: #93a1a1 !important;
      color: #fff !important;
      padding: 6px !important;
      margin: 24px 0 !important;
      font-family: Georgia, serif !important;
    }

    .demo-heading:first-child {margin-top: 0 !important;}