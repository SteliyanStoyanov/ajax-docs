---
title: Telerik.Web.UI.GridHTMLEditorColumnEditor
page_title: Telerik.Web.UI.GridHTMLEditorColumnEditor
description: Telerik.Web.UI.GridHTMLEditorColumnEditor
---

# Telerik.Web.UI.GridHTMLEditorColumnEditor

The editor for Telerik.Web.UI.GridHTMLEditorColumn column.

## Inheritance Hierarchy

* System.Object
* System.Web.UI.Control
* Telerik.Web.UI.GridColumnEditorBase : IGridColumnEditor
* Telerik.Web.UI.GridTextColumnEditor
* Telerik.Web.UI.GridHTMLEditorColumnEditor

## Properties

###  Text `String`

Gets or sets the  Content property.

###  IsInitialized `Boolean`

Get value if the editor has been initialized after an InitializeInControl or InitializeFromControl method call

###  Editor `RadEditor`

Gets the  control.

###  Text `String`

Gets or sets the cell text.

###  ToolTip `String`

The ToolTip that will be applied to the  control.

###  ContainerControl `Control`

Gets the instance of the Container control (generally a TableCell), after the last call of InstantiateInControl method

###  IsInitialized `Boolean`

Get value if the editor has been initialized after an InitializeInControl or InitializeFromControl method call

###  IsInEditMode `Boolean`

Get a value indicating whether the current row/column editor is in edit mode.

## Methods

###  SetOwner

#### Returns

`System.Void` 

###  SetOwner

#### Returns

`System.Void` 

###  InitializeInControl

#### Returns

`System.Void` 

###  InitializeFromControl

#### Returns

`System.Void` 

###  CopySettingsFrom

Copy setting from given column editor

#### Parameters

#### editor `Telerik.Web.UI.IGridColumnEditor`

#### Returns

`System.Void` 

###  CreateControls

Create the input/edit controls belonging to the editor and prepare for AddControlsToContainer call.

#### Returns

`System.Void` 

###  AddControlsToContainer

Implement this member to create the edit controls in the grid cell.
            This method is called from each column's InitializeCell method, when a  initializes its cells.

#### Returns

`System.Void` 

###  LoadControlsFromContainer

This method should recrteate the state of the column editor (edit controls, etc) from the container.
            This method is called when  method is called, or when
            GridEditableItem.EditManager.GetColumnEditor is called.

#### Remarks
This method is should prepare the column editor to extract values from the edit controls residign in a TableCell of the grid.

#### Returns

`System.Void` 

