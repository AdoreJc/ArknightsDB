# TrailContext

**Namespace:** `Torappu`


## Methods

- `Void _ResizeTrails(Int32)`

- `Trail _AllocTrail()`

- `Point _AllocPoint()`

- `Void _DellocTrail(Trail)`

- `Void _DellocPoint(Point)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class TrailContext
{
	public List`1 trails; // 0x10
	private Queue`1 m_pointPool; // 0x18
	private Queue`1 m_trailPool; // 0x20


	// RVA: 0x6777fb0 VA: 0x7598d8ffb0
	private Void _ResizeTrails(Int32 targetCount) { }
	// RVA: 0x677822c VA: 0x7598d9022c
	private Trail _AllocTrail() { }
	// RVA: 0x6778354 VA: 0x7598d90354
	private Point _AllocPoint() { }
	// RVA: 0x67781c4 VA: 0x7598d901c4
	private Void _DellocTrail(Trail trail) { }
	// RVA: 0x67785b0 VA: 0x7598d905b0
	private Void _DellocPoint(Point point) { }
	// RVA: 0x6778610 VA: 0x7598d90610
	public Void .ctor() { }
}
```