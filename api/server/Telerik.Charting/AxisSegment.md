---
title: Telerik.Charting.AxisSegment
page_title: Telerik.Charting.AxisSegment
description: Telerik.Charting.AxisSegment
---

# Telerik.Charting.AxisSegment

Axis segment in case of ScaleBreaks enabled

## Inheritance Hierarchy

* System.Object
* Telerik.Charting.StateManagedObject : IChartingStateManagedItem, IChartingStateManager, IDisposable
* Telerik.Charting.AxisSegment

## Properties

###  Name `String`

Segments name in collection

###  MinValue `Double`

Segment minimum value at the axis

###  MaxValue `Double`

Maximum segment's value at the axis

###  Step `Double`

Axis items step for a current Segment

###  StartPoint `PointF`

Segment start point

###  EndPoint `PointF`

Segment end point

###  Rectangle `RectangleF`

Segment's bound rectangle

###  PixelsPerValue `Double`

Pixels per one value

###  ViewStateIgnoresCase `Boolean`

Gets if view sate should ignore case

###  ViewState `StateBag`

Sate bag to store view state content

## Methods

###  GetX

Gets X coordinate

#### Parameters

#### val `System.Double`

Series value to get coordinate of

#### Returns

`System.Nullable`1` Coordinate

###  GetY

Gets Y coordinate

#### Parameters

#### val `System.Double`

Series value to get coordinate of

#### Returns

`System.Nullable`1` Coordinate

###  SetRange

Recalculates items values in collection

#### Parameters

#### items `Telerik.Charting.ChartSeriesItemsCollection`

Series items with values in current segment diapason

#### isOptimizeMax `System.Boolean`

Should max value optimization be done or not

#### Returns

`System.Void` 

###  OptimizeNumber

Getting the better value

#### Parameters

#### number `System.Double`

Number

#### toLarge `System.Nullable{System.Boolean}`

Should get biggest number or not

#### Returns

`System.Double` Number

###  GetAxisItems

Create axis items

#### Parameters

#### axis `Telerik.Charting.ChartAxis`

Axis

#### Returns

`System.Double` Final value

###  IsIntersection

Check segments on a intersections

#### Parameters

#### segment `Telerik.Charting.AxisSegment`

Any other segment

#### Returns

`System.Boolean` True if segments intersect

###  GetPath

Return a path around segments rectangle

#### Parameters

#### linePath `System.Drawing.Drawing2D.GraphicsPath`

Path depending of scale break line type

#### startLine `System.Boolean`

Should start segment line as scale break line type be created

#### endLine `System.Boolean`

Should end segment line as scale break line type be created

#### isHorizontal `System.Boolean`

Plot area series orientation, true if horizontal

#### Returns

`System.Drawing.Drawing2D.GraphicsPath` Segments path

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

