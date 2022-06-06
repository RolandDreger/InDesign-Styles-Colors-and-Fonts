# InDesign – Styles, Colors and Fonts

Where the heck are all the styles, colors, and fonts in the document? How do they get into? And under what circumstances can they be removed without side effects or not?

Sometimes searching for it fails, sometimes you can delete it, but the settings will be lost. Here is an attempt to make a (complete 🤷‍♂️) checklist.


## Paragraph Styles

| Place | Note |
| --- | --- |
| **Setting for »Based on« Paragraph Style** | |
| **Setting for default paragraph style for text** | Paragraph style can be deleted without warning message if not applied in the current document. Setting gets lost. |
| **Object Style** | Paragraph style can be deleted without warning message if object style is not applied. Setting gets lost. |
| **Cell Style** | Paragraph style can be deleted without warning message if cell style is not applied. Setting gets lost. |
| **Table of Contents Style** | Paragraph style can be deleted without warning message if no table of contents has been created. Setting gets lost. |
| **Anchored Object Defaults** | *Object ▶︎ Anchored Object ▶︎ Insert  ▶︎ Text.* Style can be deleted without warning message if no anchored object was inserted into the document. Setting gets lost. |
| **Conditional Text** | Check hidden condition! |
| **Track change** | Check deleted or moved Text! |
| **Footnote options** | Paragraph style can be deleted without warning message if no footnote is inserted in the document. Setting gets lost. |
| **Endnote options** | Paragraph style can be deleted without warning message if no endnote is inserted in the document. Setting gets lost. |
| **Text Variable** | Running Header |
| **Caption Setup Options** | Paragraph style can be deleted without warning message if no caption is inserted into the document. Setting gets lost. |
| **Multi-state Object** | |
| &nbsp; | |
| XML | |
| **XML Element** | Even if the XML element is not placed in the document. |
|	**Map Styles to Tags** | |
| &nbsp; | |
| Index | |
|	**Generate Index settings** | Paragraph style can be deleted without warning message if no index is used/generated in the document. Setting gets lost. |
|	**Page Reference Type** | *To Next Use Of Style.* Paragraph style can be deleted without warning message if no paragraph with this style is applied in the document. Setting gets lost. |
| &nbsp; | |
| EPub Export Preferences | |
| **Paragraph style to break InDesign document.** | Paragraph style can be deleted without warning message if not applied in the current document. Setting gets lost. |


## Character Styles

| Place | Note |
| --- | --- |
| **Setting for »Based on« Character Style** | |
| **Setting for default character style for text** | Character style can be deleted without warning message if not applied in the current document. Setting gets lost. |
| **Paragraph Override** | Bullet characters and numbering, Drop caps and nested styles, Grep styles. | 
| **Table of Contents Style** | Character style can be deleted without warning message if no table of contents has been created. Setting gets lost. |
| **Conditional Text** | Check hidden condition! |
| **Track change** | Check deleted or moved Text! |
| **Footnote options** | Character style can be deleted without warning message if no endnote is inserted in the document. Setting gets lost. |
| **Endnote options** | Character style can be deleted without warning message if no endnote is inserted in the document. Setting gets lost. |
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
|	**Generate Index settings** | Character style can be deleted without warning message if no index is used/generated in the document. Setting gets lost. |
| **Index	Page Reference Options** | The character style applied to page numbers. Character style can be deleted without warning message if no index is used in the document. Setting gets lost. |


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
| **Anchored Object Defaults** | *Object ▶︎ Anchored Object ▶︎ Insert.* Style can be deleted without warning message if no anchored object was inserted into the document. Setting gets lost. |
| **Track change** | Check anchored objects in deleted or moved text! |
| **Multi-state Object** | |
| **XML Element** | Even if the XML element is not placed in the document. |


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
