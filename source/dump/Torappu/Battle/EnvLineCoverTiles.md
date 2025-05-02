# EnvLineCoverTiles

**Namespace:** `Torappu.Battle`


## Fields

- `String _tileStatusMarkedAsInside`

- `String _tileStatusMarkedAsOutside`

- `String _edgeLineRendererEffectKey`

- `String _disableBlackboardKey`

- `Single _heightOffset`

- `Vector3 _lineOffsetToMapCenter`

- `Int32 m_width`

- `Int32 m_height`

- `Boolean m_needUpdateEdges`

- `Boolean m_isDisabled`


## Methods

- `Void _RenderLine()`

- `Boolean _IsValidMove(GridPosition, GridPosition)`

- `Boolean _IsStraightMove(GridPosition, GridPosition)`

- `Void _UpdateEdgeCornorStatus()`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnEnvChanged(Tile, String)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvLineCoverTiles : EnvEventExecutor
{
	private String _tileStatusMarkedAsInside; // 0x28
	private String _tileStatusMarkedAsOutside; // 0x30
	private String _edgeLineRendererEffectKey; // 0x38
	private String _disableBlackboardKey; // 0x40
	private Single _heightOffset; // 0x48
	private Vector3 _lineOffsetToMapCenter; // 0x4c
	private List`1 m_isEdgePassingCorner; // 0x58
	private List`1 m_isTileInEdges; // 0x60
	private List`1 m_edgeLines; // 0x68
	private List`1 m_edgeEffects; // 0x70
	private Int32 m_width; // 0x78
	private Int32 m_height; // 0x7c
	private Boolean m_needUpdateEdges; // 0x80
	private Boolean m_isDisabled; // 0x81
	private readonly List`1 GRID_POS_OFFSET; // 0x88
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__RenderLine; // 0x18
	private static DelegateBridge __Hotfix0__DFSGetNewLineFromCurrentPoint; // 0x20
	private static DelegateBridge __Hotfix0__IsValidMove; // 0x28
	private static DelegateBridge __Hotfix0__IsStraightMove; // 0x30
	private static DelegateBridge __Hotfix0__UpdateEdgeCornorStatus; // 0x38
	private static DelegateBridge __Hotfix0__ResizeList; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x40231a0 VA: 0x759663b1a0
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x4023398 VA: 0x759663b398
	public override Void OnEnvChanged(Tile tile, String status) { }
	// RVA: 0x40235bc VA: 0x759663b5bc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x402448c VA: 0x759663c48c
	private Void _RenderLine() { }
	// RVA: 0x4024098 VA: 0x759663c098
	private List`1 _DFSGetNewLineFromCurrentPoint(GridPosition currentPos) { }
	// RVA: 0x4024ef0 VA: 0x759663cef0
	private Boolean _IsValidMove(GridPosition pos, GridPosition offset) { }
	// RVA: 0x4024be0 VA: 0x759663cbe0
	private Boolean _IsStraightMove(GridPosition pos, GridPosition offset) { }
	// RVA: 0x402386c VA: 0x759663b86c
	private Void _UpdateEdgeCornorStatus() { }
	// RVA: 0x VA: 0x0
	private static Void _ResizeList(List`1 target, Int32 height, Int32 width) { }
	// RVA: 0x40251d8 VA: 0x759663d1d8
	public Void .ctor() { }
	// RVA: 0x4025660 VA: 0x759663d660
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4025664 VA: 0x759663d664
	private Void <>xLuaBaseProxy_OnEnvChanged(Tile P0, String P1) { }
	// RVA: 0x4025668 VA: 0x759663d668
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```