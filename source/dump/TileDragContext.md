# TileDragContext

**Namespace:** ` `


## Fields

- `Character dummy`

- `Param param`

- `Tile beginTile`

- `Tile currentTile`

- `Vector2 tileStartScreenPos`

- `Vector2 targetStartPos`

- `Boolean isDragging`

- `AutoChessUnitQuery dummyQuery`


## Methods

- `Void Reset()`

- `Vector2 _ConvertToScreenPos(Vector2, Vector2, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TileDragContext : DragContext
{
	private const Single DRAG_UNHOOK_RADIUS_SQR; // 0x0
	public Character dummy; // 0x18
	public Param param; // 0x20
	public Tile beginTile; // 0x28
	public Tile currentTile; // 0x30
	public Vector2 tileStartScreenPos; // 0x38
	public Vector2 targetStartPos; // 0x40
	public Boolean isDragging; // 0x48
	public AutoChessUnitQuery dummyQuery; // 0x50
	private static DelegateBridge __Hotfix0_InitDragContext; // 0x0
	private static DelegateBridge __Hotfix0_UpdateDragContext; // 0x8
	private static DelegateBridge __Hotfix0_ClearDragContext; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0__ConvertToScreenPos; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2024ee4 VA: 0x759463cee4
	public override Boolean InitDragContext(ValueBundle bundle) { }
	// RVA: 0x2025438 VA: 0x759463d438
	public override Boolean UpdateDragContext() { }
	// RVA: 0x20258a8 VA: 0x759463d8a8
	public override Void ClearDragContext() { }
	// RVA: 0x2022574 VA: 0x759463a574
	public Void Reset() { }
	// RVA: 0x2025294 VA: 0x759463d294
	private Vector2 _ConvertToScreenPos(Vector2 localPos, Vector2 offset, Boolean isInit) { }
	// RVA: 0x2024db8 VA: 0x759463cdb8
	public Void .ctor() { }
}
```