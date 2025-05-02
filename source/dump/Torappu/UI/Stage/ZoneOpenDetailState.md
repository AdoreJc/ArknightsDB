# ZoneOpenDetailState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneOpenState openState`

- `Int64 openTimeStamp`

- `Int64 closeTimeStamp`


## Properties

- `Boolean isOpen`

- `Boolean willOpenToday`

- `Boolean isForcedOpen`


## Methods

- `Boolean get_isOpen()`

- `Boolean get_willOpenToday()`

- `Boolean get_isForcedOpen()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneOpenDetailState
{
	public ZoneOpenState openState; // 0x10
	public Int64 openTimeStamp; // 0x18
	public Int64 closeTimeStamp; // 0x20

	public Boolean isOpen { get; }
	public Boolean willOpenToday { get; }
	public Boolean isForcedOpen { get; }

	// RVA: 0x2fca884 VA: 0x75955e2884
	public Boolean get_isOpen() { }
	// RVA: 0x2fca918 VA: 0x75955e2918
	public Boolean get_willOpenToday() { }
	// RVA: 0x2fca99c VA: 0x75955e299c
	public Boolean get_isForcedOpen() { }
	// RVA: 0x2fcaa24 VA: 0x75955e2a24
	public Void .ctor() { }
}
```