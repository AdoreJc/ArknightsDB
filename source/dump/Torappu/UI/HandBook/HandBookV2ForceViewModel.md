# HandBookV2ForceViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2ForceData forceData`

- `Int32 favorSum`

- `Int32 charOwn`

- `Int32 charSum`


## Properties

- `String forceId`

- `Int32 forceIndex`

- `String color`

- `String cardColor`

- `Boolean isAvail`

- `Boolean isComplete`

- `Boolean isEmpty`

- `Int32 favorAvg`


## Methods

- `String get_forceId()`

- `Int32 get_forceIndex()`

- `String get_color()`

- `String get_cardColor()`

- `Boolean get_isAvail()`

- `Boolean get_isComplete()`

- `Boolean get_isEmpty()`

- `Int32 get_favorAvg()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2ForceViewModel
{
	public HandBookV2ForceData forceData; // 0x10
	public List`1 ownCharIdList; // 0x18
	public List`1 ownNPCIdList; // 0x20
	public List`1 allCharIdList; // 0x28
	public List`1 allNPCIdList; // 0x30
	public Int32 favorSum; // 0x38
	public Int32 charOwn; // 0x3c
	public Int32 charSum; // 0x40

	public String forceId { get; }
	public Int32 forceIndex { get; }
	public String color { get; }
	public String cardColor { get; }
	public List`1 pointList { get; }
	public Boolean isAvail { get; }
	public Boolean isComplete { get; }
	public Boolean isEmpty { get; }
	public Int32 favorAvg { get; }

	// RVA: 0x2edc46c VA: 0x75954f446c
	public String get_forceId() { }
	// RVA: 0x2edc488 VA: 0x75954f4488
	public Int32 get_forceIndex() { }
	// RVA: 0x2edc4a4 VA: 0x75954f44a4
	public String get_color() { }
	// RVA: 0x2edc4c0 VA: 0x75954f44c0
	public String get_cardColor() { }
	// RVA: 0x2edc4dc VA: 0x75954f44dc
	public List`1 get_pointList() { }
	// RVA: 0x2edc4f8 VA: 0x75954f44f8
	public Boolean get_isAvail() { }
	// RVA: 0x2edc508 VA: 0x75954f4508
	public Boolean get_isComplete() { }
	// RVA: 0x2edc518 VA: 0x75954f4518
	public Boolean get_isEmpty() { }
	// RVA: 0x2edc528 VA: 0x75954f4528
	public Int32 get_favorAvg() { }
	// RVA: 0x2edc578 VA: 0x75954f4578
	public Void .ctor() { }
}
```