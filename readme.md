# Simple Combo

*Simple Combo* is a jQuery-based combo box widget that is

* simple
* lightweight
* consistent with native widget look and feel

with simpleCombo, you can turn select lists into combo boxes like this:

`$(`*selector*`).simpleCombo();`

Simple combo boxes are normal select lists with one extra feature: you can type
directly into the combo box to add an extra option, which is automatically
selected.

Since these combo boxes are actually just select lists plus JavaScript, they
look exactly like regular select lists. They can be styled, resized, etc.
with no visual glitches.

## Example

Add combo box functionality to all select lists with the `allow-edit` class.

`$('select.allow-edit').simpleCombo();`

## Notes

* On Safari, characters cannot be entered when the combo is expanded.
* Only regular ascii characters can be entered: no accented letters or non-Latin characters.

