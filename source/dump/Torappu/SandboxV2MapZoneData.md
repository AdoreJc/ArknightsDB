# SandboxV2MapZoneData

**Namespace:** `Torappu`


## Fields

- `String zoneId`

- `Vector2 center`

- `Boolean hasBorder`


## Methods

- `Boolean ShouldSerializecenter()`

- `Boolean ShouldSerializevertices()`

- `Boolean ShouldSerializetriangles()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2MapZoneData
{
	public String zoneId; // 0x10
	public Vector2 center; // 0x18
	public List`1 vertices; // 0x20
	public List`1 triangles; // 0x28
	public Boolean hasBorder; // 0x30


	// RVA: 0x34b22cc VA: 0x7595aca2cc
	public Boolean ShouldSerializecenter() { }
	// RVA: 0x34b22d4 VA: 0x7595aca2d4
	public Boolean ShouldSerializevertices() { }
	// RVA: 0x34b22dc VA: 0x7595aca2dc
	public Boolean ShouldSerializetriangles() { }
	// RVA: 0x34b22e4 VA: 0x7595aca2e4
	public Void .ctor() { }
}
```