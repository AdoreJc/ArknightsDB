# Thorn2CardModifier

**Namespace:** ` `


## Fields

- `Int32 m_passableCnt`

- `MotionMode m_motion`

- `Character m_owner`

- `ChoseTileDatas cardTileData`


## Methods

- `Void PreproccesssTileInfo()`

- `Void _CheckTileValidRow(Int32, Int32)`

- `Void _CheckTileValidCol(Int32, Int32)`

- `Void _SetTilesCollider()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Thorn2CardModifier : CardHoldDataModifier
{
	private Int32 m_passableCnt; // 0x10
	private MotionMode m_motion; // 0x14
	private Character m_owner; // 0x18
	private TileStatus[,] m_passableCntMapsRow; // 0x20
	private TileStatus[,] m_passableCntMapsCol; // 0x28
	public List`1 m_tilesRow; // 0x30
	public List`1 m_tilesCol; // 0x38
	private Dictionary`2 m_collidersRow; // 0x40
	private Dictionary`2 m_collidersCol; // 0x48
	private ChoseTileDatas cardTileData; // 0x50
	private List`1 m_tempTile; // 0x58


	// RVA: 0x1b7a8d0 VA: 0x75941928d0
	public Void .ctor(Int32 passableCnt, MotionMode motion, Character unit) { }
	// RVA: 0x1b7b12c VA: 0x759419312c
	public override Void OnTick(Card card, FP deltaTime) { }
	// RVA: 0x1b7aa94 VA: 0x7594192a94
	public Void PreproccesssTileInfo() { }
	// RVA: 0x1b7b130 VA: 0x7594193130
	private Void _CheckTileValidRow(Int32 height, Int32 width) { }
	// RVA: 0x1b7b5a8 VA: 0x75941935a8
	private Void _CheckTileValidCol(Int32 height, Int32 width) { }
	// RVA: 0x1b7ba20 VA: 0x7594193a20
	private Void _SetTilesCollider() { }
}
```