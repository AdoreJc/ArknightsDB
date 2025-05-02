# TileInfoController

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Tile m_selectedTile`

- `Int32 m_popupId`


## Methods

- `Void Reset()`

- `Void OnBottomMaskDown()`

- `Void OnBottomMaskUp()`

- `Void _SelectTile(Tile)`

- `Void _UnselectTile()`

- `Boolean _CheckStateValid(UIStateEnum)`

- `Void _ClearSelectedTile()`

- `Void _OnUIStateChanged(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class TileInfoController
{
	private Tile m_selectedTile; // 0x10
	private Int32 m_popupId; // 0x18


	// RVA: 0x205d214 VA: 0x7594675214
	public Void Reset() { }
	// RVA: 0x205d2f8 VA: 0x75946752f8
	public Void OnBottomMaskDown() { }
	// RVA: 0x205d6a8 VA: 0x75946756a8
	public Void OnBottomMaskUp() { }
	// RVA: 0x205d418 VA: 0x7594675418
	private Void _SelectTile(Tile tile) { }
	// RVA: 0x205d6ac VA: 0x75946756ac
	private Void _UnselectTile() { }
	// RVA: 0x205d3b0 VA: 0x75946753b0
	private Boolean _CheckStateValid(UIStateEnum state) { }
	// RVA: 0x205d6b0 VA: 0x75946756b0
	private Void _ClearSelectedTile() { }
	// RVA: 0x205d7b0 VA: 0x75946757b0
	private Void _OnUIStateChanged(Object arg) { }
	// RVA: 0x205d83c VA: 0x759467583c
	public Void .ctor() { }
}
```