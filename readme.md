# InDesign – Styles, Colors and Fonts

Where the heck are all the styles, colors, and fonts in the document? How do they get into? And under what circumstances can they be removed without side effects or not?

Sometimes searching for it fails, sometimes you can delete it, but the settings will be lost. Here is an attempt to make a (complete 🤷‍♂️) checklist.


## Paragraph Styles

| Place | Note |
| --- | --- |
| **Setting for »Based on« Paragraph Style** | |
| **Setting for default paragraph style for text** | :warning: |
| **Object Style** | :warning: |
| **Cell Style** | :warning: |
| **Table of Contents Style** | :warning: |
| **Anchored Object Defaults** | *Object ▶︎ Anchored Object ▶︎ Insert  ▶︎ Text.* :warning: |
| **Conditional Text** | Check hidden condition! |
| **Track change** | Check deleted or moved Text! |
| **Footnote options** | :warning: |
| **Endnote options** | :warning: |
| **Text Variable** | *Running Header* |
| **Caption Setup Options** | :warning: |
| **Multi-state Object** | |
| &nbsp; | |
| XML | |
| **XML Element** | Even if the XML element is not placed in the document. |
|	**Map Styles to Tags** | |
| &nbsp; | |
| Index | |
|	**Generate Index settings** | :warning: |
|	**Page Reference Type** | *To Next Use Of Style.* :warning: |
| &nbsp; | |
| EPub Export Preferences | |
| **Paragraph style to break InDesign document.** | :warning: |

:warning: Paragraph style can be deleted without warning message if not applied or no item is inserted into the current document. Setting gets lost.

## Character Styles

| Place | Note |
| --- | --- |
| **Setting for »Based on« Character Style** | |
| **Setting for default character style for text** | :warning: |
| **Paragraph Override** | Bullet characters and numbering, Drop caps and nested styles, Grep styles. | 
| **Table of Contents Style** | :warning: |
| **Conditional Text** | Check hidden condition! |
| **Track change** | Check deleted or moved Text! |
| **Footnote options** | :warning: |
| **Endnote options** | :warning: |
| **Cross-reference format** | |
| **Hyperlink options** | |
| **Text Variable** | Running Header |
| **Multi-state Object** | |
| &nbsp; | |
| XML | |
| **XML Element** | Even if the XML element is not placed in the document. |
| **Map Styles to Tags** | |
| &nbsp; | |
| Index | |
|	**Generate Index settings** | :warning: |
| **Index	Page Reference Options** | The character style applied to page numbers. :warning: |

:warning: Character style can be deleted without warning message if not applied or no item is inserted into the current document. Setting gets lost.

## Table Styles/Cell Styles

| Place | Note |
| --- | --- |
| **Setting for »Based on« Table/Cell Style** | |
| **Conditional Text** | Check hidden condition! |
| **Track change** | Check deleted or moved Text! |
| **Multi-state Object** | |
| **XML Element** | Even if the XML element is not placed in the document. |


## Object Styles

| Place | Note |
| --- | --- |
| **Setting for »Based on« Object Style** | |
| **Anchored Object Defaults** | *Object ▶︎ Anchored Object ▶︎ Insert.* :warning: |
| **Track change** | Check anchored objects in deleted or moved text! |
| **Multi-state Object** | |
| **XML Element** | Even if the XML element is not placed in the document. |

:warning: Object style can be deleted without warning message if not applied or no item is inserted into the current document. Setting gets lost.

## Colors

| Place | Note |
| --- | --- |
| **Paragraph Style** | |
| **Character Style** | |
| **Object Style** | |
| **Table Style** | |
| **Cell Style** | |
| **Imported graphic**| AI, INDD, PDF |
| **Conditional Text** | Check hidden condition! |
| **Track Change** | Check deleted or moved Text! |
| **Transparency Effect** | |
| **Multi-state Object** | |
| **Ink Manager** | Ink alias |
| **XML Element** | Even if the XML element is not placed in the document. |
| &nbsp; | |
| Local Overrides | |
| **Paragraph** | Paragraph rules, Paragraph Shading, Paragraph Border. Does not have to be applied to a text. |
| **Character** | Underline options, strikethrough options. Does not have to be applied to a text. |


## Fonts

| Place | Note |
| --- | --- |
| **Paragraph Style** | |
| **Character Style** | |
| **Local Override** | |
| **Imported graphic** | INDD, PDF |
| **Conditional Text** | Check hidden condition! |
| **Multi-state Object** | |
| **XML Element** | Even if the XML element is not placed in the document. |


## General Notes

### Book Synchronization
Styles and colors can get into the document via the book synchronization. These can be deleted without warning message if they are not applied in the current document.

### Search in IDML
Sometimes you can reach your goal faster if you search for "orphaned" formats in the IDML file.

1. Export InDesign document as IDML
2. Change the file extension to .zip
3. Unpack the ZIP folder
4. Search in the unpacked files e.g. for the name of the style 

## Contribute
If something is missing, please tell me.
