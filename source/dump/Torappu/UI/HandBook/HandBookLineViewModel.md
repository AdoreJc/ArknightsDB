# HandBookLineViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Int32 ID`

- `String point1`

- `String point2`

- `Int32 lineType`

- `Int32 point1NextID`

- `Int32 point2NextID`


## Methods

- `Int32 GetNextID(String)`

- `Boolean Contain(String)`

- `String GetAnotherPoint(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookLineViewModel
{
	public Int32 ID; // 0x10
	public String point1; // 0x18
	public String point2; // 0x20
	public Int32 lineType; // 0x28
	public Int32 point1NextID; // 0x2c
	public Int32 point2NextID; // 0x30


	// RVA: 0x2ebfa30 VA: 0x75954d7a30
	public Int32 GetNextID(String point) { }
	// RVA: 0x2eb6548 VA: 0x75954ce548
	public Boolean Contain(String point) { }
	// RVA: 0x2eb6518 VA: 0x75954ce518
	public String GetAnotherPoint(String point) { }
	// RVA: 0x2ebfa68 VA: 0x75954d7a68
	public Void .ctor() { }
}
```