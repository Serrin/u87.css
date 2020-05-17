![U-87-Cyber-Combat-Unit.jpg](https://github.com/Serrin/u87.css/raw/master/U-87-Cyber-Combat-Unit.jpg "U-87-Cyber-Combat-Unit.jpg")


# u87.css

This is the default css of my code documentations.

For a demo page please check the testpages of the versions and the [Celestra](https://github.com/Serrin/Celestra) project!


## Versions

### __u87.css v0.9.9 (Toaster)__
- _float grid v0.8.0_
- _This is the last version with the original design._

### u87.css v0.9.10
- _float grid v0.8.0_
- New design.

### u87.css v0.9.11
- _flex grid v0.9.0_
- New themes (blue, dark, light).
- New flexbox based grid.

### u87.css v0.9.12
- _flex grid v0.9.1_
- New utility classes.
- Fixes in the grid and `.flex-w-*` classes.

### u87.css v0.9.13
- _flex grid v0.9.2_
- New utility classes, new print styles and many fixes in the grid (_restructured to "mobile first"_).

### u87.css v0.9.14
- _grid v0.9.3, flex grid v0.9.3, css grid v0.8.1_
- New utility classes.
- Default text color changed to black from #333333.
- New print styles.
- Fixes in themes.
- `-ms` vendor prefixed flex values have been removed (used only in IE10) and many fixes in the flex grid.
- The `.row` (`.flex`) and `.col-XX` (`.flex-XX`) aliases have been removed from the __flex grid__.
- __CSS GRID__ classes has been added as experimental tools in the __u87-0.9.14-cssgrid.css__ file.

### u87.css v0.9.15
- _grid v0.9.4, flex grid v0.9.5 - flex grid 2 implemented, css grid v0.8.2 - experimental_
- Added a grid cheatsheet.
- New utility classes (colors, fonts, etc.).
- New container classes added (`.container-sm`, `.container-md`,  `.container`, `.container-lg`, `.container-xl`, `.container`).
- New hide classes added (`.hide-xs`, `.hide-sm`, `.hide-md`, `.hide-lg`, `.hide-xl`, `.hide`).
- New container classes added in the __flex grid__ (`.flex-xs`, `.inline-flex-xs`, `.flex-sm`, .`inline-flex-sm`, `.flex-md`, `.inline-flex-md`, `.flex`, `.inline-flex`, `.flex-lg`, .`inline-flex-lg`, `.flex-xl`, `.inline-flex-xl`).
- New flex item classes added in the __flex grid__ (`.flex-w-xs-XX`, `.flex-w-XX`, `.flex-w-sm-XX`, `.flex-w-md-XX`, `.flex-w-lg-XX`, `.flex-w-xl-XX`).
- The old flex item `.flex-XX` classes (1-24, not the `.flex-w-XX`) have been renamed to `.flex-f-XX`.
- New grid container classes added in the __css grid__ (`.grid-xs`, `.inline-grid-xs`, `.grid-sm`, `.inline-grid-sm`, `.grid-md`, `.inline-grid-md`, `.grid`, `.inline-grid`, `.grid-lg`, `.inline-grid-lg`, `.grid-xl`, `.inline-grid-xl`).
- New cell classes added in the __css grid__ (`.cell`, `.cell-rows-xs-XX`, `.cell-rows-XX`, `.cell-rows-sm-XX`, `.cell-rows-md-XX`, `.cell-rows-lg-XX`, `.cell-rows-xl-XX`, `.cell-cols-xs-XX`, `.cell-cols-XX`, `.cell-cols-sm-XX`, `.cell-cols-md-XX`, `.cell-cols-lg-XX`, `.cell-cols-xl-XX`).
- Many cell classes have been renamed in the __css grid__ (`.ms-cell-row-XX` -> `.ms-cell-start-row-XX`, `.ms-cell-col-XX` -> `.ms-cell-start-col-XX`, `.cell-row-start-XX` -> `.cell-start-row-XX`, `.cell-row-end-XX` -> `.cell-end-row-XX`, `.cell-col-start-XX` -> `.cell-start-col-XX`, `.cell-col-end-XX` -> `.cell-end-col-XX`).
- The old `.cell-row-XX` and `.cell-col-XX` cell classes have been removed in the __css grid__.

### u87.css v0.9.16
- _grid v0.9.5, flex grid v0.9.6, css grid v0.8.3 - experimental_
- _This is the last version with IE11 and Edge 12-18 support._
- Many changes in the padding settings (in grids and elements too), but without class names amendation.
- The `font-family` properties are based on the __CSS Variables__ with fallbacks.
- The scrollbar color settings have been removed, but readded the Firefox properties in the new classes.
- New classes: `.break-all`, `.break-word` _- same as the HTML element_, `.nobreak`, `.hyphens-auto`, `.hyphens-manual`, `.nohyphens`
- New scrollbar classes: `scrollbar-auto`, `.scrollbar-thin`, `.scrollbar-none`, `.scrollbar-dark`, `.scrollbar-blue`, `.scrollbar-light`
- New font classes: `.font-fantasy`, `.font-cursive`, `.font-italic`, `.font-more-bolder`, `.font-hairline`, `.font-100`, `.font-200`, `.font-300`, `.font-400`, `.font-500`, `.font-600`, `.font-700`, `.font-800`, `.font-900`, `.font-950`, `.font-1000`
- Removed classes: `.heading-a`, `.heading-b`, `.heading-c`, `.heading-d`

### u87.css v0.9.17 (Cython)
- _grid v0.9.6, flex grid v0.9.7, css grid v0.9.0_
- _The IE11 and and Edge 12-18 has been removed from the supported browsers._
- Added new files: __u87-0.9.17-map.md__, __u87-0.9.17.min.css__, __u87-0.9.17.min.html__
- The __u87.css__ and __u87-cssgrid.css__ files have been merged.
- All of the `.ms-*` classes and `-ms-*` properties have been removed in the __css grid__.



## License

[https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)

MIT License

SPDX short identifier: MIT

Copyright (c) 2018 Ferenc Czigler

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
