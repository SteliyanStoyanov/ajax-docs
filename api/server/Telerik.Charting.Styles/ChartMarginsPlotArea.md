---
title: Telerik.Charting.Styles.ChartMarginsPlotArea
page_title: Telerik.Charting.Styles.ChartMarginsPlotArea
description: Telerik.Charting.Styles.ChartMarginsPlotArea
---

# Telerik.Charting.Styles.ChartMarginsPlotArea

Plot area's margins

## Inheritance Hierarchy

* System.Object
* Telerik.Charting.StateManagedObject : IChartingStateManagedItem, IChartingStateManager, IDisposable
* Telerik.Charting.Styles.LayoutDecoratorBase : ICloneable
* Telerik.Charting.Styles.ChartMargins
* Telerik.Charting.Styles.ChartMarginsPlotArea

## Properties

###  Left `Unit`

Sets the left margin in pixels or percent of the chart's width.

###  Right `Unit`

Sets the right margin in pixels or percent of the chart's width.

###  Top `Unit`

Sets the top margin in pixels or percent of the chart's height.

###  Bottom `Unit`

Sets the bottom margin in pixels or percent of the chart's height.

###  Left `Unit`

Sets the left side in pixels or percents of the chart's width.

###  Right `Unit`

Sets the right side in pixels or percents of the chart's width.

###  Top `Unit`

Sets the top side in pixels or percents of the chart's height.

###  Bottom `Unit`

Sets the bottom side in pixels or percents of the chart's height.

###  ViewStateIgnoresCase `Boolean`

Gets if view sate should ignore case

###  ViewState `StateBag`

Sate bag to store view state content

## Methods

###  Reset

Reset to default settings

#### Returns

`System.Void` 

###  op_Implicit

Implicitly creates a new instance of ChartMargins from the specified string.

#### Parameters

#### value `System.String`

The string to parse

#### Returns

`Telerik.Charting.Styles.ChartMargins` New instance of ChartMargins from the specified string

###  Parse

Converts the specified string to an instance of ChartMargins.

#### Parameters

#### value `System.String`

The string to convert from.

#### Returns

`Telerik.Charting.Styles.ChartMargins` New instance of ChartMargins from the specified string

###  Parse

Converts the specified string to an instance of ChartMargins.

#### Parameters

#### value `System.String`

The string to convert from.

#### culture `System.Globalization.CultureInfo`

Culture info

#### Returns

`Telerik.Charting.Styles.ChartMargins` New instance of ChartMargins from the specified string

###  Reset

Reset to default settings.

#### Returns

`System.Void` 

###  Reset

Set value in pixels or percents of all sides

#### Parameters

#### value `Telerik.Charting.Styles.Unit`

Value in pixels or percents of all sides

#### Returns

`System.Void` 

###  Equals

Checks whether objects are equal

#### Parameters

#### obj `System.Object`

Object to compare

#### Returns

`System.Boolean` Result of comparing

###  GetHashCode

Gets hash code

#### Returns

`System.Int32` Hash code

###  op_Equality

Operator comparing

#### Parameters

#### layoutDecoratorOne `Telerik.Charting.Styles.LayoutDecoratorBase`

First object for comparing

#### layoutDecoratorTwo `Telerik.Charting.Styles.LayoutDecoratorBase`

Second object for comparing

#### Returns

`System.Boolean` Result of comparing

###  op_Inequality

Operator not equal

#### Parameters

#### layoutDecoratorOne `Telerik.Charting.Styles.LayoutDecoratorBase`

First object for comparing

#### layoutDecoratorTwo `Telerik.Charting.Styles.LayoutDecoratorBase`

Second object for comparing

#### Returns

`System.Boolean` Whether objects are not equal

###  Clone

Clone this object

#### Returns

`System.Object` New instance of LayoutDecoratorBase class with the same fields as this one

###  CopyFrom

Copy fields from object

#### Parameters

#### layoutDecorator `Telerik.Charting.Styles.LayoutDecoratorBase`

Object to copy from

#### Returns

`System.Void` 

###  Telerik.Charting.IChartingStateManager.LoadViewState

Loads data from a view state

#### Parameters

#### state `System.Object`

View state to load data from

#### Returns

`System.Void` 

###  Telerik.Charting.IChartingStateManager.SaveViewState

Saves object data to a view state

#### Returns

`System.Object` Saved view state object

###  Telerik.Charting.IChartingStateManager.TrackViewState

Tracks view state changes

#### Returns

`System.Void` 

###  CloneState

Makes a view state clone

#### Returns

`System.Web.UI.StateBag` StateBag

###  SaveViewState

Saves object data to a view state

#### Returns

`System.Object` Saved view state object

###  TrackViewState

Tracks view state changes

#### Returns

`System.Void` 

###  LoadViewState

Loads data from a view state

#### Parameters

#### state `System.Object`

View state to load data from

#### Returns

`System.Void` 

###  SetDirty

Sets the item dirty state

#### Returns

`System.Void` 

###  ToString

ToString() override. Used in the properties grid to avoid object type showing.

#### Returns

`System.String` Empty string

