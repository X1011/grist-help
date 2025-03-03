# Interface: CursorPos

[grist-plugin-api](../modules/grist_plugin_api.md).CursorPos

Represents the position of an active cursor on a page.

## Table of contents

### Properties

- [fieldIndex](grist_plugin_api.CursorPos.md#fieldindex)
- [rowId](grist_plugin_api.CursorPos.md#rowid)
- [rowIndex](grist_plugin_api.CursorPos.md#rowindex)
- [sectionId](grist_plugin_api.CursorPos.md#sectionid)

## Properties

### fieldIndex

• `Optional` **fieldIndex**: `number`

The index of the selected field in the current view.

___

### rowId

• `Optional` **rowId**: [`UIRowId`](../modules/grist_plugin_api.md#uirowid)

The rowId (value of the `id` column) of the current cursor position, or 'new' if the cursor is on a new row.

___

### rowIndex

• `Optional` **rowIndex**: `number`

The index of the current row in the current view.

___

### sectionId

• `Optional` **sectionId**: `number`

The id of a section that this cursor is in. Ignored when setting a cursor position for a particular view.
