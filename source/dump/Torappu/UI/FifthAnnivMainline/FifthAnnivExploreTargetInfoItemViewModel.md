# FifthAnnivExploreTargetInfoItemViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Boolean hasRequireEvent`

- `Boolean completeRequireEvent`

- `Boolean completeTargetValue`

- `String targetName`

- `String descForRequireEvent`


## Properties

- `Boolean completeTarget`


## Methods

- `Boolean get_completeTarget()`

- `Void LoadData(FifthAnnivExploreTargetData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreTargetInfoItemViewModel
{
	public Boolean hasRequireEvent; // 0x10
	public Boolean completeRequireEvent; // 0x11
	public Boolean completeTargetValue; // 0x12
	public String targetName; // 0x18
	public String descForRequireEvent; // 0x20
	public List`1 valueOrders; // 0x28
	public ListDict`2 exploreValueInfos; // 0x30

	public Boolean completeTarget { get; }

	// RVA: 0x293028c VA: 0x7594f4828c
	public Boolean get_completeTarget() { }
	// RVA: 0x2934330 VA: 0x7594f4c330
	public Void LoadData(FifthAnnivExploreTargetData targetData) { }
	// RVA: 0x2934328 VA: 0x7594f4c328
	public Void .ctor() { }
}
```