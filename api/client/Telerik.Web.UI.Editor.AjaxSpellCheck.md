---
title: Telerik.Web.UI.Editor.AjaxSpellCheck
page_title: Client-side API Reference
description: Telerik.Web.UI.Editor.AjaxSpellCheck
slug: Telerik.Web.UI.Editor.AjaxSpellCheck
---

# Telerik.Web.UI.Editor.AjaxSpellCheck : Sys.UI.Control

## Inheritance Hierarchy

* Sys.UI.Control
* *[Telerik.Web.UI.Editor.AjaxSpellCheck]({%slug Telerik.Web.UI.Editor.AjaxSpellCheck%})*

## Methods

### get_editor

Returns the RadEditor instance.

#### Parameters

#### Returns

`Telerik.Web.UI.RadEditor`

### set_editor

Sets the RadEditor instance.

#### Parameters

##### editor `Telerik.Web.UI.RadEditor`

The RadEditor instance.

#### Returns

`None`

### get_language

Gets the language used by the Spell-Check service.

#### Parameters

#### Returns

`String`

### set_language

Sets the language used by the Spell-Check service.

#### Parameters

##### language `String`

The language.

#### Returns

`None`

### spellCheck

Performs a spell check on the content.

#### Parameters

#### Returns

`None`

### finishSpellCheck

Stops the spell checking and updates the content.

#### Parameters

##### raiseEvent? `Boolean`

Indicates whether to raise the spellCheckEnd event.

#### Returns

`None`

### cancelSpellCheck

Stops the spell checking and retrieves the original state of the content.

#### Parameters

##### raiseEvent? `Boolean`

Indicates whether to raise the spellCheckEnd event.

#### Returns

`None`

### addCustomWord

Adds a custom word to the collection.

#### Parameters

##### word `String`

#### Returns

`None` 

## Events

### spellCheckStart

This event is fired when the spell checking has started.

#### Event Data

##### sender `Telerik.Web.UI.Editor.AjaxSpellCheck`

The AjaxSpellCheck instance raised the event.

##### args `Sys.EventArgs`

The event arguments.

### spellCheckEnd

This event is fired when the spell checking has finished.

#### Event Data

##### sender `Telerik.Web.UI.Editor.AjaxSpellCheck`

The AjaxSpellCheck instance raised the event.

##### args `Sys.EventArgs`

The event arguments.