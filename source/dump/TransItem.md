# TransItem

**Namespace:** ` `


## Fields

- `UISelectionState selectionState`

- `TransType transType`

- `Color transColor`


## Properties

- `Boolean showAnimPathProperty`

- `String animPath`


## Methods

- `Boolean get_showAnimPathProperty()`

- `String get_animPath()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class TransItem
{
	public UISelectionState selectionState; // 0x10
	public TransType transType; // 0x14
	public Color transColor; // 0x18

	public Boolean showAnimPathProperty { get; }
	public String animPath { get; }

	// RVA: 0x677d9d0 VA: 0x7598d959d0
	public Boolean get_showAnimPathProperty() { }
	// RVA: 0x677d428 VA: 0x7598d95428
	public String get_animPath() { }
	// RVA: 0x677d9c8 VA: 0x7598d959c8
	public Void .ctor() { }
}
```