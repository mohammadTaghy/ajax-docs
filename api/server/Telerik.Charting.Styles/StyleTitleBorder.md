---
title: Telerik.Charting.Styles.StyleTitleBorder
page_title: Telerik.Charting.Styles.StyleTitleBorder
description: Telerik.Charting.Styles.StyleTitleBorder
---

# Telerik.Charting.Styles.StyleTitleBorder

Title border specific style

## Inheritance Hierarchy

* System.Object
* Telerik.Charting.StateManagedObject : IChartingStateManagedItem, IChartingStateManager, IDisposable
* Telerik.Charting.Styles.StyleBorder : ICloneable
* Telerik.Charting.Styles.StyleTitleBorder

## Properties

###  Color `Color`

Specifies the line color property

###  PenStyle `DashStyle`

Specifies the pen style property

###  Width `Single`

Specifies the width property

###  Visible `Boolean`

Visibility

###  Item `Object`

Gets property value by name

###  ViewStateIgnoresCase `Boolean`

Gets if view sate should ignore case

###  ViewState `StateBag`

Sate bag to store view state content

## Methods

###  IsVisible

Determines whether this instance is visible.

#### Returns

`System.Boolean` true if this instance is visible; otherwise, false.

###  Reset

Reset to default settings

#### Returns

`System.Void` 

###  Equals

Compare two objects

#### Parameters

#### obj `System.Object`

Object tot compare

#### Returns

`System.Boolean` Result of comparing

###  GetHashCode

Gets hash code

#### Returns

`System.Int32` Hash code

###  Clone

Clone this object

#### Returns

`System.Object` Object with the same fields as this one

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
