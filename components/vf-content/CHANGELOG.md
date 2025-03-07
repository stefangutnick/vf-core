### 1.6.2

* Dependency bumps.

### 1.6.1

* Dependency bumps.

### 1.6.0

* Use vf-spacing tokens for heading margins.
* Reduce bottom margin on headings to be more consistent with overall typography, design kit.
  * https://github.com/visual-framework/vf-core/pull/1589
* Darken and increase figure text size
  * https://github.com/visual-framework/vf-core/issues/1582
* Figures take a responsive and centered layout, which is most typical.
  * https://github.com/visual-framework/vf-core/issues/1583

### 1.5.6

* Adds support for responsive `img` and `figure` elements
  * https://github.com/visual-framework/vf-core/issues/1412

### 1.5.4

* dependency bump

### 1.5.2

* Remove author information from example, as we have a dedicated vf-article-meta-information component.
* Fix blockquote bottom margin.

### 1.5.1

* Fixes a bug with a non-existent @visual-framework/form was required.

### 1.5.0

* changes the dev dependencies to match their new names and versions

### 1.4.1

* Removes the 'dark mode' CSS for links - as it's not implemented.
* changes any `set-` style functions to cleaner version

### 1.4.0

* adds top margin override for first item inside of `vf-content`

### 1.3.2

* dependency bump

### 1.3.0

* updates spacing design tokens
* requires `v2.0.0` of the `vf-design-tokens` package or newer

### 1.2.2

* dependency bump

### 1.2.0

* adds loading="lazy" to the img element for better performance

### 1.1.9

* dependency bump

### 1.1.7

* fixes an issue when content creators add the bold/strong tags to hedaing to make them bolder - when they shouldn't be
* adds a little more padding to ul and ol elements so they visually fit 'inside' of vf-content

### 1.1.4

* fixes support for vf-figure alignment options

### 1.1.1

* adds a floated vf-figure example in the nunjucks file
* adds CSS for margin spacing of vf-figure inside of vf-content
* adds table styles to match default vf-table with striped rows

### 1.1.0

* `vf-content` becomes less of a utility and a general purpose for long-form content
* Standardise links colours
* Add intial support for `--dark` links

### 1.0.8

* Add support for cite, figcaption
* Improve spacing on blockquote

### 1.0.3

* Lerna version bump

### 1.0.1

* Lerna version bump

### 1.0.0

* Initial stable release
