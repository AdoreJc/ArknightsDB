# Act20sideCartCompSelectViewModel

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String activityId`

- `Boolean isExhibt`

- `CartAccessoryPos selectPos`

- `Boolean isChanged`


## Methods

- `String GetSelectCompId()`

- `CartCompViewModel GetSelectComp()`

- `Void MarkChangeSave()`

- `Void _MarkCurrentSelect()`

- `Void SelectAccess(String)`

- `Void SelectPos(CartAccessoryPos)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCartCompSelectViewModel
{
	public String activityId; // 0x10
	public Boolean isExhibt; // 0x18
	public Dictionary`2 compsOnCar; // 0x20
	public Dictionary`2 cartCompList; // 0x28
	public CartAccessoryPos selectPos; // 0x30
	public Boolean isChanged; // 0x34


	// RVA: 0x32faa88 VA: 0x7595912a88
	public String GetSelectCompId() { }
	// RVA: 0x32fab20 VA: 0x7595912b20
	public CartCompViewModel GetSelectComp() { }
	// RVA: 0x32fab98 VA: 0x7595912b98
	public List`1 InstSelectCartComp() { }
	// RVA: 0x32faef4 VA: 0x7595912ef4
	public Void MarkChangeSave() { }
	// RVA: 0x32faefc VA: 0x7595912efc
	private Void _MarkCurrentSelect() { }
	// RVA: 0x32faf70 VA: 0x7595912f70
	public Void SelectAccess(String compId) { }
	// RVA: 0x32fb354 VA: 0x7595913354
	public Void SelectPos(CartAccessoryPos pos) { }
	// RVA: 0x32fb548 VA: 0x7595913548
	public Void .ctor() { }
}
```