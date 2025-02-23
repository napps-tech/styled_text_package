## 2.0.0-nullsafety.0

* Migrate to null safety.

## 1.0.3+4

* Improved handling of broken xml.

## 1.0.3+3

* Fixed a bug when the space between two tags was eaten.

## 1.0.3+2

* Made a workaround to keep whitespace between tags: `<b>bold</b>&space;<i>italic</i>`.
* Added `size`, `color` and `backgroundColor` parameters to `IconStyle` class.

## 1.0.3+1

* Added `CustomTextStyle` text style, for which you can specify handling of tag attributes.

## 1.0.2+1

* Added the `StyledText.selectable` constructor to create selectable text.
* Added guidance on escaping XML special characters in text.
* The deprecated `isNewLineAsBreaks` parameter has been removed.

## 1.0.1+3

* Fixed flickering when changing style, styles and text.

## 1.0.1+2

* Improved support for DefaultTextSyle, now `style` property is merging with DefaultTextSyle.
* Fixed a bug where no redrawing occurred when changing `style` property.

## 1.0.1+1

* The parameter isNewLineAsBreaks has been renamed to newLineAsBreaks, isNewLineAsBreaks is deprecated.

## 1.0.1

* The parameter isNewLineAsBreaks has been added, indicating not to ignore line breaks in the source text.
* Added description of parameters via doc comments.

## 1.0.0+2

* Allow XML special chars: &lt; (<), &amp; (&), &gt; (>), &quot; ("), and &apos; (')
* Avoid memory leak log message

## 1.0.0+1

* Example added.

## 1.0.0

* Initial release.
