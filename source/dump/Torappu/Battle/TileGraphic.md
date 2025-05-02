# TileGraphic

**Namespace:** `Torappu.Battle`


## Fields

- `Tile _tile`

- `GridPosition _gridPos`

- `Vector2 _mapOffset`

- `HighlightType m_highlightType`


## Properties

- `HighlightType highlightType`

- `GridPosition gridPos`

- `Vector2 mapOffset`


## Methods

- `HighlightType get_highlightType()`

- `Void set_highlightType(HighlightType)`

- `GridPosition get_gridPos()`

- `Vector2 get_mapOffset()`

- `Void SetTile(Tile)`

- `Void UpdateGridPosition(Transform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TileGraphic : MonoBehaviour, IHotfixable
{
	private Tile _tile; // 0x18
	private GridPosition _gridPos; // 0x20
	private Vector2 _mapOffset; // 0x28
	protected HighlightType m_highlightType; // 0x30
	private static readonly String BRIGHT_TILE_KEYWORD; // 0x0
	private static DelegateBridge __Hotfix0_get_highlightType; // 0x8
	private static DelegateBridge __Hotfix0_set_highlightType; // 0x10
	private static DelegateBridge __Hotfix0_get_gridPos; // 0x18
	private static DelegateBridge __Hotfix0_get_mapOffset; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_SetTile; // 0x30
	private static DelegateBridge __Hotfix0_UpdateGridPosition; // 0x38
	private static DelegateBridge __Hotfix0_OnTriggered; // 0x40
	private static DelegateBridge __Hotfix0_RefreshThemeConfig; // 0x48
	private static DelegateBridge __Hotfix0_ResetTile; // 0x50
	private static DelegateBridge __Hotfix0_SetHighlight; // 0x58
	private static DelegateBridge __Hotfix0_SetLitState; // 0x60
	private static DelegateBridge __Hotfix1_SetLitState; // 0x68
	private static DelegateBridge __Hotfix0_SetLitStrength; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public HighlightType highlightType { get; set; }
	public GridPosition gridPos { get; }
	public Vector2 mapOffset { get; }

	// RVA: 0x40940b8 VA: 0x75966ac0b8
	public HighlightType get_highlightType() { }
	// RVA: 0x4094274 VA: 0x75966ac274
	public Void set_highlightType(HighlightType value) { }
	// RVA: 0x4099110 VA: 0x75966b1110
	public GridPosition get_gridPos() { }
	// RVA: 0x4099188 VA: 0x75966b1188
	public Vector2 get_mapOffset() { }
	// RVA: 0x40991fc VA: 0x75966b11fc
	public virtual Void Init() { }
	// RVA: 0x4096db0 VA: 0x75966aedb0
	public Void SetTile(Tile tile) { }
	// RVA: 0x4099284 VA: 0x75966b1284
	public Void UpdateGridPosition(Transform anchor) { }
	// RVA: 0x40993b4 VA: 0x75966b13b4
	public virtual Void OnTriggered(Int32 triggerCnt) { }
	// RVA: 0x409943c VA: 0x75966b143c
	public virtual Void RefreshThemeConfig() { }
	// RVA: 0x40994b0 VA: 0x75966b14b0
	public virtual Void ResetTile() { }
	// RVA: 0x4099524 VA: 0x75966b1524
	protected virtual Boolean SetHighlight(HighlightType value, Boolean force) { }
	// RVA: 0x40995d4 VA: 0x75966b15d4
	public virtual Void SetLitState(Boolean state) { }
	// RVA: 0x40996ec VA: 0x75966b16ec
	public virtual Void SetLitState(Int32 litLevel) { }
	// RVA: 0x40997fc VA: 0x75966b17fc
	public virtual Void SetLitStrength(Single strength) { }
	// RVA: 0x409990c VA: 0x75966b190c
	public Void .ctor() { }
	// RVA: 0x40999c4 VA: 0x75966b19c4
	private static Void .cctor() { }
}
```