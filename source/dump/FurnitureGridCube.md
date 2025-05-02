# FurnitureGridCube

**Namespace:** ` `


## Fields

- `Furniture m_furniture`

- `Int32 m_roomHeigit`


## Properties

- `Furniture furniture`

- `Int32 x`

- `Int32 y`

- `Int32 z`

- `Int32 w`

- `Int32 h`

- `Int32 d`


## Methods

- `Furniture get_furniture()`

- `Int32 get_x()`

- `Int32 get_y()`

- `Int32 get_z()`

- `Int32 get_w()`

- `Int32 get_h()`

- `Int32 get_d()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FurnitureGridCube : IGridCube
{
	private Furniture m_furniture; // 0x10
	private Int32 m_roomHeigit; // 0x18

	public Furniture furniture { get; }
	public Int32 x { get; }
	public Int32 y { get; }
	public Int32 z { get; }
	public Int32 w { get; }
	public Int32 h { get; }
	public Int32 d { get; }

	// RVA: 0x37b67c0 VA: 0x7595dce7c0
	public Void .ctor(Furniture furniture, Int32 roomHeight) { }
	// RVA: 0x37c2894 VA: 0x7595dda894
	public Furniture get_furniture() { }
	// RVA: 0x37c289c VA: 0x7595dda89c
	public Int32 get_x() { }
	// RVA: 0x37c28b8 VA: 0x7595dda8b8
	public Int32 get_y() { }
	// RVA: 0x37c2b58 VA: 0x7595ddab58
	public Int32 get_z() { }
	// RVA: 0x37c2d7c VA: 0x7595ddad7c
	public Int32 get_w() { }
	// RVA: 0x37c2e78 VA: 0x7595ddae78
	public Int32 get_h() { }
	// RVA: 0x37c2f24 VA: 0x7595ddaf24
	public Int32 get_d() { }
}
```