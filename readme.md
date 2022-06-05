# InDesign – Styles, Colors and Fonts

Where the heck are all the colors, fonts and styles in the document? How do they get into? And under what circumstances can they be removed or not?

Sometimes searching for it fails, sometimes you can delete it, but the settings will be lost. Here is an attempt to make a (complete 🤷‍♂️) checklist.


## Paragraph Styles

| Place | Note |
| --- | --- |
| **As »Based on« Paragraph Style** | |
| **As default paragraph style for text** | Paragraph style can be deleted without warning message if not applied in the current document. |
| **Object Styles** | Paragraph style can be deleted without warning message if object style is not applied. |
| **Cell Styles** | Paragraph style can be deleted without warning message if cell style is not applied. |
| **Table of Contents Styles** | Can be deleted without warning message if no table of contents has been created. |
| **Anchored Object Defaults** | Object ▶︎ Anchored Object ▶︎ Insert  ▶︎ Text. Style can be deleted without warning message if no anchored object was inserted into the document. |
| **Via Book** | Paragraph style can be deleted if not applied in the current document. |
| **Conditional Text** | Check hidden condition! |
| **Track changes** | Check deleted or moved Text! |
| **Footnote options** | Paragraph style can be deleted without warning message if no footnote is inserted in the document. |
| **Endnote options** | Paragraph style can be deleted without warning message if no endnote is inserted in the document. |
| **Text Variables** | Running Header |
| **Caption Setup Options** | Paragraph style can be deleted without warning message if no caption is inserted into the document. | |
| **Multi-state Objects** | |
| &nbsp; | |
| XML | |
| **XML Element** | Even if the XML element is not placed in the document. |
|	**Map Styles to Tags** | |
| &nbsp; | |
| Index | |
|	**Generate Index settings** | Paragraph style can be deleted without warning message if no index is used in the document. |
|	**Page Reference Type: To Next Use Of Style** | Paragraph style can be deleted without warning message if no paragraph with this style is applied in the document. |
| &nbsp; | |
| EPub Export Preferences | |
| **Paragraph style to break InDesign document.** | Paragraph style can be deleted without warning message if not applied in the current document. Setting gets lost. |


## Character Styles

| Place | Note |
| --- | --- |
| **As »Based on« Character Style** | |
| **As default character style for text** | Character style can be deleted without warning message if not applied in the current document. |
| **Paragraph Overrides** | Bullet characters and numbering, Drop caps and nested styles, Grep styles. | 
| **Table of Contents Styles** | Character style can be deleted without warning message if no table of contents has been created. |
| **Via book synchronization** | Character style can be deleted without warning message if it is not applied in the current document. |
| **Conditional Text** | Check hidden condition! |
| **Track changes** | Check deleted or moved Text! |
| **Footnote options** | Character style can be deleted without warning message if no endnote is inserted in the document. |
| **Endnote options** | Character style can be deleted without warning message if no endnote is inserted in the document. |
| **Cross-reference formats** | |
| **Hyperlink options** | |
| **Text Variables** | Running Header |
| **Multi-state Objects** | |
| &nbsp; | |
| XML | |
| **XML Element** | Even if the XML element is not placed in the document. |
| **Map Styles to Tags** | |
| &nbsp; | |
| Index | |
|	**Generate Index settings** | Character style can be deleted without warning message if no index is used in the document. |
| **Index	Page Reference Options** | The character style applied to page numbers. Character style can be deleted without warning message if no index is used in the document. |


## Table Styles/Cell Styles

| Place | Note |
| --- | --- |
| **As »Based on« Table/Cell Style** | |
| **Conditional Text** | Check hidden condition! |
| **Track changes** | Check deleted or moved Text! |
| **Multi-state Objects** | |
| **XML Element** | Even if the XML element is not placed in the document. |


## Object Styles

| Place | Note |
| --- | --- |
| **As »Based on« Object Style** | |
| **Anchored Object Defaults** | Object ▶︎ Anchored Object ▶︎ Insert. Style can be deleted without warning message if no anchored object was inserted into the document. |
| **Via book synchronization** | Object style can be deleted without warning message if it is not applied in the current document. |
| **Track changes** | Check anchored objects in deleted or moved text! |
| **Multi-state Objects** | |
| **XML Element** | Even if the XML element is not placed in the document. |


## Colors

| Place | Note |
| --- | --- |
| **Paragraph Styles** | |
| **Character Styles** | |
| **Object Styles** | |
| **Table Styles** | |
| **Cell Styles** | |
| **Imported graphics**| AI, INDD, PDF |
| **Conditional Text** | Check hidden condition! |
| **Track Changes** | Check deleted or moved Text! |
| **Transparency Effects** | |
| **Multi-state Objects** | |
| **Ink Manager** | Ink alias |
| **XML Element** | Even if the XML element is not placed in the document. |
| &nbsp; | |
| Local Overrides | |
| **Paragraphs** | Paragraph rules, Paragraph Shading, Paragraph Border. Does not have to be applied to a text. |
| **Characters** | Underline options, strikethrough options. Does not have to be applied to a text. |


## Fonts

| Place | Note |
| --- | --- |
| **Paragraph Styles** | |
| **Character Styles** | |
| **Local Overrides** | |
| **Imported graphics** | INDD, PDF |
| **Conditional Text** | Check hidden condition! |
| **Multi-state Objects** | |
| **XML Element** | Even if the XML element is not placed in the document. |


## General Notes

Styles and colors can get into the document via the book synchronization. These can be deleted without warning message if they are not applied in the current document.

If something is missing, please tell me.