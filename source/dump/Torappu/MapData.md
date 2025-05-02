# MapData

**Namespace:** `Torappu`


## Properties

- `Int32 width`

- `Int32 height`

- `TileData Item`

- `TileData Item`


## Methods

- `Int32 get_width()`

- `Int32 get_height()`

- `TileData get_Item(Int32, Int32)`

- `TileData get_Item(GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class MapData
{
	public Int16[,] map; // 0x10
	public TileData[] tiles; // 0x18
	public Edge[] blockEdges; // 0x20
	public String[] tags; // 0x28
	public MapEffectData[] effects; // 0x30
	public String[] layerRects; // 0x38

	public Int32 width { get; }
	public Int32 height { get; }
	public TileData Item { get; }
	public TileData Item { get; }

	// RVA: 0x34a4d74 VA: 0x7595abcd74
	public Int32 get_width() { }
	// RVA: 0x34a4d94 VA: 0x7595abcd94
	public Int32 get_height() { }
	// RVA: 0x34a4db4 VA: 0x7595abcdb4
	public TileData get_Item(Int32 r, Int32 c) { }
	// RVA: 0x34a4e40 VA: 0x7595abce40
	public TileData get_Item(GridPosition pos) { }
	// RVA: 0x34a4e48 VA: 0x7595abce48
	public Void .ctor() { }
}
```