# Bookmark component

[![npm version](https://badge.fury.io/js/%40visual-framework%2Fvf-bookmark.svg)](https://badge.fury.io/js/%40visual-framework%2Fvf-bookmark)

## About

Indicates if an item has been bookmarked to a list of favourites or similar.

## Usage

This component shows if a piece of content has been selected by a user as a favourite using a text label and icon.

No JavaScript functionality is provided and it is expected that the state handling will be done on a case-by-case basis on the project application.

### Active state

The active state of the icon is managed by adding the class `vf-bookmark--active`. This class should be added by your framework or sever-side code.

### Options

The component can be configured with a number of options.

- `bookmark_href`: defaults to `JavaScript:Void(0);`
    - Any url that may be required.
- `label_inactive`: defaults to `Bookmark`
- `label_active`: defaults to `Bookmarked`
- `is_active`: defaults to `true`
    - `true` or `false`
    - sets `vf-bookmark--active` CSS class
    - determines the appropriate `label_inactive` or `label_active`
- `modifier`: defaults to `inline`
    - `inline` or `button`
- `icon`: defaults to `star`
    - `star` or `heart` (a bookmark icon may be added in the future)

### Accessibility

This component targets WCAG 2.1 AA accessibility.

Note that the SVG icons use `aria-hidden="true"` as to be ignored by screen readers.

## Install

This repository is distributed with [npm][https://www.npmjs.com/]. After [installing npm][https://www.npmjs.com/get-npm] and [yarn](https://classic.yarnpkg.com/en/docs/install), you can install `vf-bookmark` with this command.

```
$ yarn add --dev @visual-framework/vf-bookmark
```

### JS

[If your component uses JS]

You should import this component in `./components/vf-component-rollup/scripts.js` or your other JS process:

```js
import { vfComponentName } from 'vf-bookmark/vf-bookmark';
// Or import directly
// import { vfComponentName } from '../components/raw/vf-bookmark/vf-bookmark.js';
vfComponentName(); // if needed, invoke it
```

### Sass/CSS

[If your component uses Sass]

The style files included are written in [Sass](https://sass-lang.com/). If you're using a VF-core project, you can import it like this:

```
@import "@visual-framework/vf-bookmark/vf-bookmark.scss";
```

Make sure you import Sass requirements along with the modules. You can use a [project boilerplate](https://stable.visual-framework.dev/building/) or the [`vf-sass-starter`](https://stable.visual-framework.dev/components/vf-sass-starter/)

## Help

- [Read the Visual Framework troubleshooting](https://stable.visual-framework.dev/troubleshooting/)
- [Open a ticket](https://github.com/visual-framework/vf-core/issues)
- [Chat on Slack](https://join.slack.com/t/visual-framework/shared_invite/enQtNDAxNzY0NDg4NTY0LWFhMjEwNGY3ZTk3NWYxNWVjOWQ1ZWE4YjViZmY1YjBkMDQxMTNlNjQ0N2ZiMTQ1ZTZiMGM4NjU5Y2E0MjM3ZGQ)
