# Tiles2D

**Namespace:** ` `


## Fields

- `Int32 _width`

- `Int32 _height`


## Properties

- `Int32 width`

- `Int32 height`

- `Tile Item`


## Methods

- `Int32 get_width()`

- `Int32 get_height()`

- `Tile get_Item(Int32, Int32)`

- `Void set_Item(Int32, Int32, Tile)`

- `Boolean CheckValid(GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Tiles2D
{
	public Tile[] _tiles; // 0x10
	private Int32 _width; // 0x18
	private Int32 _height; // 0x1c

	public Int32 width { get; }
	public Int32 height { get; }
	public Tile Item { get; set; }

	// RVA: 0x4079080 VA: 0x7596691080
	public Int32 get_width() { }
	// RVA: 0x4079088 VA: 0x7596691088
	public Int32 get_height() { }
	// RVA: 0x406e774 VA: 0x7596686774
	public Tile get_Item(Int32 row, Int32 col) { }
	// RVA: 0x4072bf0 VA: 0x759668abf0
	public Void set_Item(Int32 row, Int32 col, Tile value) { }
	// RVA: 0x4072ad0 VA: 0x759668aad0
	public Void .ctor(Int32 width, Int32 height) { }
	// RVA: 0x4076850 VA: 0x759668e850
	public Boolean CheckValid(GridPosition pos) { }
	// RVA: 0x4079090 VA: 0x7596691090
	public override String ToString() { }
}
```