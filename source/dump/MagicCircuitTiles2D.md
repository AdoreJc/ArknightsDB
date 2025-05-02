# MagicCircuitTiles2D

**Namespace:** ` `


## Fields

- `Int32 _width`

- `Int32 _height`


## Properties

- `Int32 width`

- `Int32 height`

- `MagicCircuitTile Item`

- `MagicCircuitTile Item`


## Methods

- `Int32 get_width()`

- `Int32 get_height()`

- `MagicCircuitTile get_Item(Int32, Int32)`

- `Void set_Item(Int32, Int32, MagicCircuitTile)`

- `MagicCircuitTile get_Item(GridPosition)`

- `Void set_Item(GridPosition, MagicCircuitTile)`

- `Boolean CheckValid(GridPosition)`

- `Boolean IsEdge(GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MagicCircuitTiles2D : IHotfixable
{
	private Int32 _width; // 0x10
	private Int32 _height; // 0x14
	public MagicCircuitTile[] _tiles; // 0x18
	private static DelegateBridge __Hotfix0_get_width; // 0x0
	private static DelegateBridge __Hotfix0_get_height; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_get_Item; // 0x18
	private static DelegateBridge __Hotfix0_set_Item; // 0x20
	private static DelegateBridge __Hotfix1_get_Item; // 0x28
	private static DelegateBridge __Hotfix1_set_Item; // 0x30
	private static DelegateBridge __Hotfix0_CheckValid; // 0x38
	private static DelegateBridge __Hotfix0_IsEdge; // 0x40

	public Int32 width { get; }
	public Int32 height { get; }
	public MagicCircuitTile Item { get; set; }
	public MagicCircuitTile Item { get; set; }

	// RVA: 0x4010d64 VA: 0x7596628d64
	public Int32 get_width() { }
	// RVA: 0x4010dcc VA: 0x7596628dcc
	public Int32 get_height() { }
	// RVA: 0x400b660 VA: 0x7596623660
	public Void .ctor(Int32 width, Int32 height, MagicCircuitController controller) { }
	// RVA: 0x4010f50 VA: 0x7596628f50
	public MagicCircuitTile get_Item(Int32 row, Int32 col) { }
	// RVA: 0x4010e34 VA: 0x7596628e34
	public Void set_Item(Int32 row, Int32 col, MagicCircuitTile value) { }
	// RVA: 0x4009ee0 VA: 0x7596621ee0
	public MagicCircuitTile get_Item(GridPosition pos) { }
	// RVA: 0x40110f0 VA: 0x75966290f0
	public Void set_Item(GridPosition pos, MagicCircuitTile value) { }
	// RVA: 0x401103c VA: 0x759662903c
	public Boolean CheckValid(GridPosition pos) { }
	// RVA: 0x4010858 VA: 0x7596628858
	public Boolean IsEdge(GridPosition pos) { }
}
```