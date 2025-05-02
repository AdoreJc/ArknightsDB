# Trail

**Namespace:** ` `


## Fields

- `Single timer`

- `Point tail`


## Methods

- `Void Reset(TrailContext)`

- `Void AddPosition(TrailContext, Vector3)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class Trail
{
	public Single timer; // 0x10
	public Queue`1 buffer; // 0x18
	public Point tail; // 0x20


	// RVA: 0x6778400 VA: 0x7598d90400
	public Void Reset(TrailContext context) { }
	// RVA: 0x6778738 VA: 0x7598d90738
	public Void AddPosition(TrailContext context, Vector3 position) { }
	// RVA: 0x67782cc VA: 0x7598d902cc
	public Void .ctor() { }
}
```