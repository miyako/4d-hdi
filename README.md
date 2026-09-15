![version](https://img.shields.io/badge/version-16-8331AE)
![version](https://img.shields.io/badge/version-17-3E8B93)

# 4d-hdi

A directory of **HDI** (*How Do I*) example databases published by 4D for **v16** and **v17**, with a short description of what each one demonstrates and a link to a modernised, project-architecture version where one exists.

HDIs are the small, single-topic demo databases that accompany 4D feature announcements on the [4D blog](https://blog.4d.com/). They were distributed as binary `.4DB` databases, which current 4D releases can no longer open directly. This repository is the index for an ongoing effort to convert the v16/v17 generation to the `.4DProject` architecture so the examples stay runnable.

## How to read the tables

| Column | Meaning |
|---|---|
| **HDI** | The name under which 4D distributed the demo. |
| **Showcases** | What the demo actually demonstrates. |
| **Updated** | Link to a converted, runnable `.4DProject` repository, if one exists. |
| **Original** | The original binary `.4DB` download, as published by 4D. |

A link in **Updated** means the demo has been converted and is maintained; an empty cell means it is original-only and a candidate for conversion.

**Progress:** 9 of 107 v16/v17 HDIs converted.

---

## 4D v16

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DWP_Bookmarks | Creating, navigating and removing bookmarks in a 4D Write Pro document. | [HDI_4DWP_Bookmarks](https://github.com/miyako/HDI_4DWP_Bookmarks) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_4DWP_Bookmarks.zip) |
| HDI_4DWP_Filter4DExpressions | Controlling which 4D expressions a 4D Write Pro document is allowed to evaluate. | [HDI_4DWP_Filter4DExpressions](https://github.com/miyako/HDI_4DWP_Filter4DExpressions) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_4DWP_Filter4DExpressions.zip) |
| HDI_4DWP_InsertDoc | Inserting one 4D Write Pro document into another at a given position. | [HDI_4DWP_InsertDoc](https://github.com/miyako/HDI_4DWP_InsertDoc) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_4DWP_InsertDoc.zip) |
| HDI_4DWP_InsertPicture | Inserting pictures into a 4D Write Pro document, inline and as characters. | [HDI_4DWP_InsertPicture](https://github.com/miyako/HDI_4DWP_InsertPicture) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_4DWP_InsertPicture.zip) |
| HDI_4DWP_InvoicesAndBookmarks | Building an invoice document by driving 4D Write Pro bookmarks from data. | [HDI_4DWP_InvoicesAndBookmarks](https://github.com/miyako/HDI_4DWP_InvoicesAndBookmarks)
 | [zip](https://download.4d.com/Demos/4D_v16/WP_InvoicesAndBookmarks.zip) |
| HDI_4DWP_Print | Printing a 4D Write Pro document, including print preview and page ranges. | | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_4DWP_Print.zip) |
| HDI_4DWP_Thread_safety | Using 4D Write Pro commands inside preemptive processes. | | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_4DWP_Thread_safety.zip) |
| HDI_4DWP_ViewProperties | Switching a 4D Write Pro area between draft, page and embedded view modes, and toggling rulers, margins and invisible characters. | | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_4DWP_ViewProperties.zip) |
| HDI_DISTINCT_ATTRIBUTES | Retrieving the distinct values of an object-field attribute with `DISTINCT ATTRIBUTE VALUES`. | [HDI_DISTINCT_ATTRIBUTES](https://github.com/miyako/HDI_DISTINCT_ATTRIBUTES) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_DISTINCT_ATTRIBUTES.zip) |
| HDI_GetPictureFormats | Listing the picture codecs available to 4D on the current platform. | [HDI_GetPictureFormats](https://github.com/miyako/HDI_GetPictureFormats) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_GetPictureFormats.zip) |
| HDI_ListboxAutoResizeColumns | Distributing list box width across columns automatically when the form is resized. | [HDI_ListboxAutoResizeColumns](https://github.com/miyako/HDI_ListboxAutoResizeColumns) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_ListboxAutoResizeColumns.zip) |
| HDI_ListboxOnColumnResize | Reacting to live column resizing in a list box via the `On Column Resize` form event. | [HDI_ListboxOnColumnResize](https://github.com/miyako/HDI_ListboxOnColumnResize) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_ListboxOnColumnResize.zip) | [HDI_ListboxOnColumnResize](https://github.com/miyako/HDI_ListboxOnColumnResize)
| HDI_ListboxVariableRowHeight | Giving individual list box rows different heights, including automatic row height. | [HDI_ListboxVariableRowHeight](https://github.com/miyako/HDI_ListboxVariableRowHeight) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_ListboxVariableRowHeight.zip) |
| HDI_ManageCache | Steering the data cache at runtime -- `SET CACHE SIZE`, unload minimum size, flush periodicity, `FLUSH CACHE`, and live statistics from `Cache info`. | [HDI_ManageCache](https://github.com/miyako/HDI_ManageCache) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_ManageCache.zip) |
| HDI_Mouse_Up_Event | The `On Mouse Up` form event on picture objects -- SVG rubber-band selection, and picture drag-and-drop with timer-driven edge auto-scroll. | [HDI_MouseUpEvent](https://github.com/miyako/HDI_MouseUpEvent) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_Mouse_Up_Event.zip) |
| HDI_SavePrintSettings | Serialising print settings with `Print settings to BLOB` and restoring them with `BLOB to print settings`, persisted per platform. | [HDI_SavePrintSettings](https://github.com/miyako/HDI_SavePrintSettings) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_SavePrintSettings.zip) |
| HDI_XML_Commands_thread_safe | The thread-safe XML command set used from preemptive processes. | [HDI_XML_Commands_thread_safe](https://github.com/miyako/HDI_XML_Commands_thread_safe) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_ThreadSafe_XMLCommands.zip) |
| HDI_WebServerPreemptive | Serving web requests from preemptive processes and measuring the throughput difference. | [HDI_WebServerPreemptive](https://github.com/miyako/HDI_WebServerPreemptive) | [zip](https://downloads.4d.com/Demos/4D_v16/HDI_WebServerPreemptive.zip) |

## 4D v16 R2

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_ListboxProperties | Reading and writing list box appearance properties at runtime with `LISTBOX SET PROPERTY` / `LISTBOX Get property`. | [HDI_ListboxProperties](https://github.com/miyako/HDI_ListboxProperties) | [zip](https://downloads.4d.com/Demos/4D_v16_R2/HDI_ListboxProperties.zip) |
| HDI_ManageListboxHightlight | Controlling the list box selection highlight independently of the selected rows. | [HDI_ManageListboxHightlight](https://github.com/miyako/HDI_ManageListboxHightlight) | [zip](https://downloads.4d.com/Demos/4D_v16_R2/HDI_ManageListboxHightlight.zip) |
| HDI_ORDER_BY_ATTRIBUTE | Sorting a selection on an attribute inside an object field with `ORDER BY ATTRIBUTE`. | [HDI_ORDER_BY_ATTRIBUTE](https://github.com/miyako/HDI_ORDER_BY_ATTRIBUTE) | [zip](https://downloads.4d.com/Demos/4D_v16_R2/HDI_ORDER_BY_ATTRIBUTE.zip) | 
| HDI_QueryByAttribute | Querying on an attribute inside an object field with `QUERY BY ATTRIBUTE`, including indexed object attributes. | [HDI_QueryByAttribute](https://github.com/miyako/HDI_QueryByAttribute) | [zip](https://downloads.4d.com/Demos/4D_v16_R2/HDI_QueryByAttribute.zip) |

## 4D v16 R3

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DWritePro_StandardActions | Driving a 4D Write Pro area entirely from built-in standard actions, with no glue code. | | [zip](https://downloads.4d.com/Demos/4D_v16_R3/HDI_4DWritePro_StandardActions.zip) |
| HDI_NewStandardActions | The standard actions introduced for form objects, menus and toolbars. | | [zip](https://downloads.4d.com/Demos/4D_v16_R3/HDI_NewStandardActions.zip) |
| HDI_OB_New | Building objects and arrays literally with `New object` and `New collection` instead of `OB SET`. | | [zip](https://downloads.4d.com/Demos/4D_v16_R3/HDI_OB_New.zip) |

## 4D v16 R4

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DViewProNewFormObject | The 4D View Pro form object -- a spreadsheet area embedded directly in a 4D form. | | [zip](https://downloads.4d.com/Demos/4D_v16_R4/HDI_4DViewProNewFormObject.zip) |
| HDI_4DWritePro_Tables | Creating and formatting tables in a 4D Write Pro document programmatically. | | [zip](https://downloads.4d.com/Demos/4D_v16_R4/HDI_4DWritePro_Tables.zip) |
| HDI_JSONFileValidation | Validating a parsed document against a JSON Schema with `JSON Validate`, and branching on the `success` flag and error collection. | [HDI_JSONFileValidation](https://github.com/miyako/HDI_JSONFileValidation) | [zip](https://downloads.4d.com/Demos/4D_v16_R4/HDI_JSONFileValidation.zip) |
| HDI_ObjectNotationDatasource | Binding form objects directly to object-notation expressions as their data source. | | [zip](https://downloads.4d.com/Demos/4D_v16_R4/HDI_ObjectNotationDatasource.zip) |
| HDI_PictureObjectAttribute | Storing and retrieving pictures inside object fields and object attributes. | | [zip](https://downloads.4d.com/Demos/4D_v16_R4/HDI_PictureObjectAttribute.zip) |
| HDI_StandardActionMultiStateObject | Wiring multi-state picture buttons and three-states checkboxes to standard actions. | | [zip](https://downloads.4d.com/Demos/4D_v16_R4/HDI_StandardActionMultiStateObject.zip) |
| HDI_TabbableObjectOrder | Controlling keyboard entry order and which objects participate in tabbing. | | [zip](https://downloads.4d.com/Demos/4D_v16_R4/HDI_TabbableObjectOrder.zip) |
| HDI_Tips | Help tips on form objects, including dynamic tips computed from an expression. | | [zip](https://downloads.4d.com/Demos/4D_v16_R4/HDI_Tips.zip) |
| HDI_UseCollections | The collection type -- creation, iteration, `push`/`pop`, `map`, `sort` and object/collection interop. | | [zip](https://downloads.4d.com/Demos/4D_v16_R4/HDI_UseCollections.zip) |

## 4D v16 R5

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DVP_AutoRowHeight | Fitting 4D View Pro row heights to their content automatically. | | [zip](https://downloads.4d.com/Demos/4D_v16_R5/HDI_4DVP_AutoRowHeight.zip) |
| HDI_4DWP_BackImagePaperBox | Setting a background picture on a 4D Write Pro document and scoping it to the paper box. | | [zip](https://downloads.4d.com/Demos/4D_v16_R5/HDI_4DWP_BackImagePaperBox.zip) |
| HDI_4DWP_HeadersFooters | Independent headers and footers per section, including distinct first-page and left/right variants. | | [zip](https://downloads.4d.com/Demos/4D_v16_R5/HDI_4DWP_HeadersFooters.zip) |
| HDI_4DWP_InsertPictureExpression | Inserting a picture into a 4D Write Pro document as a live 4D expression rather than as static content. | | [zip](https://downloads.4d.com/Demos/4D_v16_R5/HDI_4DWP_InsertPictureExpression.zip) |
| HDI_4DWritePro_Links | Linking a 4D Write Pro document to external content and refreshing it on demand. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_4DWritePro_Links.zip) |
| HDI_FormData | Passing data between forms by handing an object to `DIALOG` and binding the dialog's fields to it through the `Form` command. | [HDI_FormData](https://github.com/miyako/HDI_FormData) | [zip](https://downloads.4d.com/Demos/4D_v16_R5/HDI_FormData.zip) |
| HDI_GetProcessActivity | Building a timer-driven process and user monitor on `Process activity` (formerly `Get process activity`), with per-session CPU aggregation and a web JSON feed. | [HDI_Get-process-activity](https://github.com/miyako/HDI_Get-process-activity) | [zip](https://downloads.4d.com/Demos/4D_v16_R5/HDI_GetProcessActivity.zip) |
| HDI_JSON_Pointer | Resolving `$ref` JSON Pointers with `JSON Resolve pointers` -- in-object refs, `rootFolder` refs to external files, and `merge` to patch over a defaults file. | [HDI_JSON_Pointer](https://github.com/miyako/HDI_JSON_Pointer) | [zip](https://downloads.4d.com/Demos/4D_v16_R5/HDI_JSON_Pointer.zip) |
| HDI_ListboxHelpTips | Per-cell help tips in a list box, computed from the row's data. | | [zip](https://downloads.4d.com/Demos/4D_v16_R5/HDI_ListboxHelpTips.zip) |

## 4D v16 R6

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DWP_ImageInAbsolutePosition | Anchoring a picture at an absolute position in a 4D Write Pro document, independent of the text flow. | | [zip](https://downloads.4d.com/Demos/4D_v16_R6/HDI_4DWP_ImageInAbsolutePosition.zip) |
| HDI_Collection_Members | The collection member functions -- `map`, `reduce`, `filter`, `find`, `slice`, `distinct` and friends. | | [zip](https://downloads.4d.com/Demos/4D_v16_R6/HDI_Collection_Members.zip) |
| HDI_Collection_Query | Querying a collection of objects with `collection.query()` and placeholder parameters. | | [zip](https://downloads.4d.com/Demos/4D_v16_R6/HDI_Collection_Query.zip) |
| HDI_JSONForm | Dynamic forms -- driving `DIALOG` from a parsed JSON form object, loading form JSON by path, and injecting one as a subform with `OBJECT SET SUBFORM`. | [HDI_JSONForm](https://github.com/miyako/HDI_JSONForm) | [zip](https://downloads.4d.com/Demos/4D_v16_R6/HDI_JSONForm.zip) |
| HDI_useSharedObjects | Shared objects and shared collections, and the `Use`...`End use` block that guards concurrent access. | | [zip](https://downloads.4d.com/Demos/4D_v16_R6/HDI_useSharedObjects.zip) |

---

## 4D v17

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DVP_Offscreen_doc | Working with a 4D View Pro document offscreen, with no form area attached. | | [zip](https://github.com/4d-depot/HDI_4DVP_Offscreen.git) |
| HDI_4DWP_Elements | Addressing the structural elements of a 4D Write Pro document -- document, body, sections, paragraphs, tables. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_4DWP_Elements.zip) |
| HDI_4DWP_GetPosition | Retrieving the on-screen coordinates of a range or element in a 4D Write Pro document. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_4DWP_GetPosition.zip) |
| HDI_4DWP_MultiColumn | Multi-column layout in 4D Write Pro, including per-section column count and spacing. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_4DWP_MultiColumn.zip) |
| HDI_4DWP_SetGetText | Reading and writing the plain text of a 4D Write Pro range with `WP SET TEXT` / `WP Get text`. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_4DWP_SetGetText.zip) |
| HDI_4DWriteProContextualMenu | Customising the 4D Write Pro contextual menu, including suppressing and extending entries. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_4DWriteProContextualMenu.zip) |
| HDI_DISTINCT_ATTRIBUTE_PATH_VALUES | Retrieving distinct values along an attribute *path* inside an object field. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_DISTINCT_ATTRIBUTE_PATH_VALUES.zip) |
| HDI_EntitySelectionInListbox | Using an ORDA entity selection directly as a list box data source. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_EntitySelectionInListbox.zip) |
| HDI_ForEach | The `For each`...`End for each` loop over collections, entity selections and object properties. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ForEach.zip) |
| HDI_GET_STRUCTURE_INFO | Introspecting the database structure -- tables, fields, indexes and relations -- as objects. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_GET_STRUCTURE_INFO.zip) |
| HDI_JSONTableForm_v17 | Generating a table's input and output forms from a JSON dynamic-form description. | | [zip](https://download.4d.com/4DBlog/Tips/4D_v17/DynamicForm_TableForm/HDI_JSONTableForm_v17.zip) |
| HDI_ListboxCollection | Collection-backed list boxes -- binding a collection of objects to a list box and addressing columns by attribute path. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ListboxCollection.zip) |
| HDI_ListBoxCollection_Advanced_v17 | Cascading collection list boxes -- one nested object drilled through with `currentItemSource`, plus per-row `metaSource` styling sampled from theme colours at runtime. | [HDI_ListBoxCollection_Advanced_v17](https://github.com/miyako/HDI_ListBoxCollection_Advanced_v17) | [zip](https://download.4d.com/4DBlog/Tips/4D_v17/HDI_ListBoxCollection_Advanced_v17.zip) |
| HDI_ListboxLiveResizing | Live column resizing feedback in a list box while the user drags a separator. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ListboxLiveResizing.zip) |
| HDI_ORDA_CRUD | The ORDA create / read / update / delete cycle on entities. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_CRUD.zip) |
| HDI_ORDA_Current_Selection | Bridging between the classic current selection and an ORDA entity selection in both directions. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_Current_Selection.zip) |
| HDI_ORDA_Dynamic_Sort_v17 | Sorting an entity selection on an attribute chosen at runtime. | | [zip](https://download.4d.com/4DBlog/Tips/4D_v17/ORDA_Dynamic_Sort_v17.zip) |
| HDI_ORDA_Handling_Entities | Entity lifecycle -- `new`, `save`, `drop`, `reload`, `touched`, and stamp-based conflict detection. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_Handling_Entities.zip) |
| HDI_ORDA_Lock | Locking entities with ORDA and interpreting the returned status object. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_Lock.zip) |
| HDI_ORDA_Logical_Operators | Combining entity selections with `and`, `or`, `minus` set operations. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_Logical_Operators.zip) |
| HDI_ORDA_Objects_And_Collections | How ORDA entities and entity selections interoperate with plain objects and collections. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_Objects_And_Collections.zip) |
| HDI_ORDA_Optimistic_Lock | The optimistic locking model -- detecting a stale entity at save time via its stamp. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_Optimistic_Lock.zip) |
| HDI_ORDA_Pessimistic_Lock | The pessimistic locking model -- explicitly locking an entity before editing it. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_Pessimistic_Lock.zip) |
| HDI_ORDA_Query | Querying with `dataClass.query()` -- query strings, placeholders, relation traversal and formula criteria. | | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_Query.zip) |
| HDI_ORDA_Statistics | Aggregate functions over entity selections -- `sum`, `average`, `min`, `max`, `count`. | [HDI_ORDA_Statistics](https://github.com/miyako/HDI_ORDA_Statistics) | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_ORDA_Statistics.zip) |
| HDI_VariableRowHeight | Per-row heights in a list box driven by the row's content. | [HDI_VariableRowHeight](https://github.com/miyako/HDI_VariableRowHeight) | [zip](https://downloads.4d.com/Demos/4D_v17/HDI_VariableRowHeight.zip) |

## 4D v17 R2

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DWP_AnchoredPictureExpressions | Anchored pictures in 4D Write Pro whose content comes from a 4D expression. | | [zip](https://downloads.4d.com/Demos/4D_v17_R2/HDI_4DWP_AnchoredPictureExpressions.zip) |
| HDI_TablePagination | Repeating table headers and controlling row breaks across pages in 4D Write Pro. | | [zip](https://downloads.4d.com/Demos/4D_v17_R2/HDI_TablePagination.zip) |
| HDI_VP_DB_Method | The 4D View Pro database method, used to intercept spreadsheet events centrally. | | [zip](https://downloads.4d.com/Demos/4D_v17_R2/HDI_VP_DB_Method.zip) |

## 4D v17 R3

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DWP_ManageSections | Creating and configuring sections in a 4D Write Pro document -- page numbering, headers, columns per section. | | [zip](https://downloads.4d.com/Demos/4D_v17_R3/HDI_4DWP_ManageSections.zip) |
| HDI_ConvertFormToDynamicForm | Exporting a designed form to its JSON description so it can be loaded as a dynamic form. | | [zip](https://downloads.4d.com/Demos/4D_v17_R3/HDI_ConvertFormToDynamicForm.zip) |
| HDI_GetApplicationInfo | Reading application and runtime information as a structured object. | | [zip](https://downloads.4d.com/Demos/4D_v17_R3/HDI_GetApplicationInfo.zip) |
| HDI_NewFormula | Formula objects -- `Formula` / `Formula from string` and invoking them as first-class values. | | [zip](https://downloads.4d.com/Demos/4D_v17_R3/HDI_NewFormula.zip) |
| HDI_RelaunchAndTest | Restarting the application programmatically, useful for self-updating and test harnesses. | | [zip](https://downloads.4d.com/Demos/4D_v17_R3/HDI_RelaunchAndTest.zip) |
| HDI_VP_ExportToExcel | Exporting a 4D View Pro document to `.xlsx`. | | [zip](https://downloads.4d.com/Demos/4D_v17_R3/HDI_VP_ExportToExcel.zip) |

## 4D v17 R4

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DVP_SetGetCells | Reading and writing 4D View Pro cell values and ranges from 4D code. | | [zip](https://downloads.4d.com/Demos/4D_v17_R4/HDI_4DVP_SetGetCells.zip) |
| HDI_4DWP_ExportDocx | Exporting a 4D Write Pro document to `.docx`. | | [zip](https://downloads.4d.com/Demos/4D_v17_R4/HDI_4DWP_ExportDocx.zip) |
| HDI_4DWP_MoreCoordinates | Extended coordinate queries in 4D Write Pro -- mapping between document positions and screen points. | | [zip](https://downloads.4d.com/Demos/4D_v17_R4/HDI_4DWP_MoreCoordinates.zip) |
| HDI_4DWP_VerticalRulers | Enabling and using the vertical ruler in a 4D Write Pro area. | | [zip](https://downloads.4d.com/Demos/4D_v17_R4/HDI_4DWP_VerticalRulers.zip) |
| HDI_4DWP_VirtualStructure | Exposing table and field names to 4D Write Pro through a virtual structure, so documents never reference real names. | | [zip](https://downloads.4d.com/Demos/4D_v17_R4/HDI_4DWP_VirtualStructure.zip) |
| HDI_SendMail | Sending mail with the SMTP transporter object, including attachments and authentication. | | [zip](https://downloads.4d.com/Demos/4D_v17_R4/HDI_SendMail.zip) |

## 4D v17 R5

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DVP_SelectionCells | Reading and manipulating the current cell selection in a 4D View Pro area. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_4DVP_SelectionCells.zip) |
| HDI_4DWP_Hyperlinks | Inserting and following hyperlinks in a 4D Write Pro document. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_4DWP_Hyperlinks.zip) |
| HDI_4DWP_SetTabs | Defining tab stops and tab leaders in 4D Write Pro paragraphs. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_4DWP_SetTabs.zip) |
| HDI_4DWP_UseTargets | Named targets in a 4D Write Pro document, used as hyperlink destinations and insertion anchors. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_4DWP_UseTargets.zip) |
| HDI_4DWP_ViewSettings | Persisting and restoring 4D Write Pro view settings such as zoom, view mode and visible guides. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_4DWP_ViewSettings.zip) |
| HDI_Database_Info | Reading database measures and file information as objects. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_Database_Info.zip) |
| HDI_Encryption | Data file encryption -- encrypting tables, supplying the passphrase and working with the encryption key store. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_Encryption.zip) |
| HDI_FilesAndFolders | The object-oriented `File` / `Folder` API that replaces the legacy document commands. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_FilesAndFolders.zip) |
| HDI_PlaceHolders_AttributePaths | Using placeholders for attribute *paths* in ORDA queries, so the sorted/queried attribute can be chosen at runtime. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_PlaceHolders_AttributePaths.zip) |
| HDI_PlaceHolders_Values | Using value placeholders in ORDA queries to keep user input out of the query string. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_PlaceHolders_Values.zip) |
| HDI_SetUserAlias | Giving a session an alias so it is identifiable in the administration window and process list. | | [zip](https://downloads.4d.com/Demos/4D_v17_R5/HDI_SetUserAlias.zip) |
| ORDA_Dynamic_Code | Building and executing ORDA queries assembled dynamically at runtime. | | [zip](https://download.4d.com/4DBlog/Tips/4D_v17R5/ORDA_Dynamic_Code.zip) |

## 4D v17 R6

| HDI | Showcases | Updated | Original |
|---|---|---|---|
| HDI_4DVP_CellValues | Typed cell values in 4D View Pro -- text, number, date, boolean and formula cells. | | [zip](https://downloads.4d.com/Demos/4D_v17_R6/HDI_4DVP_CellValues.zip) |
| HDI_4DVP_Style | Applying cell and range styles in 4D View Pro, including reusable named styles. | | [zip](https://downloads.4d.com/Demos/4D_v17_R6/HDI_4DVP_Style.zip) |
| HDI_CSS_colors | Using CSS colour names and notations wherever 4D accepts a colour. | | [zip](https://downloads.4d.com/Demos/4D_v17_R6/HDI_CSS_colors.zip) |
| HDI_Order_ByFormula | Sorting an entity selection by an arbitrary formula rather than a stored attribute. | | [zip](https://downloads.4d.com/Demos/4D_v17_R6/HDI_Order_ByFormula.zip) |
| HDI_Query_ByFormula | Querying an entity selection with a formula criterion. | | [zip](https://downloads.4d.com/Demos/4D_v17_R6/HDI_Query_ByFormula.zip) |

---

## Related restorations (pre-v16)

Outside the v16/v17 scope of this directory, the following older demos have also been restored and are listed here for completeness.

| HDI | Origin | Showcases | Repository |
|---|---|---|---|
| HDI_Indexes | v11 | Creating and dropping all four index types (B-tree, cluster, composite, keyword) at runtime and timing their effect on `QUERY` and `ORDER BY`. | [HDI_Indexes](https://github.com/miyako/HDI_Indexes) |
| HDI_Passwords | v11 | Driving the built-in user/group system from code -- user lists, `CHANGE CURRENT USER`, group-gated features, and `USERS TO BLOB` backup/restore. | [HDI_Passwords](https://github.com/miyako/HDI_Passwords) |
| HDI_PicturesCombine | v12 | Superimposing two pictures with `COMBINE PICTURES` in `Superimposition` mode, with live offset and transparency sliders. | [HDI_PicturesCombine](https://github.com/miyako/HDI_PicturesCombine) |
| HDI_PicturesCrop | v12 | Interactive cropping with `TRANSFORM PICTURE` in `Crop` mode, using mutually-constrained sliders and `OBJECT MOVE` to draw the crop rectangle. | [HDI_PicturesCrop](https://github.com/miyako/HDI_PicturesCrop) |
| HDI_ScrollTwoPictures | v14 | Synchronising two scaled picture areas by mirroring `OBJECT GET/SET SCROLL POSITION` on the scroll event (since renamed `On Scroll`). | [HDI_ScrollTwoPictures](https://github.com/miyako/HDI_ScrollTwoPictures) |
| HDI_OnScrollEventInPictureAndListBox | v15 | Reading and driving scroll position for both a list box and a scrollable picture, including a moving viewport indicator over a thumbnail. | [HDI_OnScrollEventInPictureAndListBox](https://github.com/miyako/HDI_OnScrollEventInPictureAndListBox) |
| HDI_PictureTransparency | v15 | Colour keying with `TRANSFORM PICTURE` (`Transparency`), then overlaying a logo with `COMBINE PICTURES` in `Superimposition` mode. | [HDI_PictureTransparency](https://github.com/miyako/HDI_PictureTransparency) |
| HDI_UseSvgFilters | v15 | Chaining SVG blur, offset and blend filter primitives by named result (the former Windows blend-mode limitation no longer applies thanks to Direct2D). | [HDI_UseSvgFilters](https://github.com/miyako/HDI_UseSvgFilters) |

## Scope and sources

**In scope.** HDI demos published with 4D v16, v16 R2-R6, v17 and v17 R2-R6.

**Out of scope.**

- **v18 and later.** Already indexed by [4d-depot/4d-depot](https://github.com/4d-depot/4d-depot/blob/master/HDIbyVersion.md), and those demos still open in current 4D releases.
- **Region-specific tips.** A few assets shipped only in the Japanese distribution (`GoogleChart_4Dv16`, `HDI_TwitterSearchAPI`, `HDI_Bootstrap_4DTags`, `HDI_FileManager`, `4DDebugLogAnalyser`, `ServerAdministrator_JA`) are not 4D-published HDIs and are not listed.
- **`HDI_Template`.** A repository template for new conversions, not a demo.

**Sources.**

- [4D v17 demos page](https://se.4d.com/demos4dv17) and [4D v18 demos page](https://se.4d.com/demos4dv18) -- official download URLs.
- [classic-HDI](https://github.com/miyako/classic-HDI) and [HDI-restoration](https://github.com/miyako/HDI-restoration) -- preliminary research on pre-v16 demos.

## Contributing a conversion

Converted repositories follow a common shape:

1. Start from [HDI_Template](https://github.com/miyako/HDI_Template), which carries the shared `.github/instructions/` rules.
2. Open the original `.4DB` in 4D 21 and let it convert to `.4DProject`.
3. Modernise in small, reviewable branches -- variable declarations, standard actions, localisation, method visibility, dialog lifecycle, dark mode.
4. Tag the repository with the `4d-hdi` topic so it is discoverable, and add the row here.
