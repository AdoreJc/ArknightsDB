# MultiMeshTileGraphic

**Namespace:** `Torappu.Battle.Tiles`


## Fields

- `Material m_replaceableMaterial`

- `Material m_buildableMaterial`

- `Material m_focusedMaterial`

- `Material m_originMaterial`

- `Tween m_tween`


## Methods

- `Void Awake()`

- `Tween <SetHighlight>b__13_0(Material)`

- `Void <SetHighlight>b__13_2(Single)`

- `Boolean <>xLuaBaseProxy_SetHighlight(HighlightType, Boolean)`

- `Void <>xLuaBaseProxy_ResetTile()`

- `Void <>xLuaBaseProxy_RefreshThemeConfig()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Tiles
public class MultiMeshTileGraphic : TileGraphic
{
	private const String BUILDABLE_MATERIAL_KEY; // 0x0
	private const String FOCUSED_MATERIAL_KEY; // 0x0
	private const String REPLACEABLE_MATERIAL_KEY; // 0x0
	private const Single TWEEN_LOOP_TIME; // 0x0
	private static readonly Color FOCUSED_COLOR; // 0x0
	private static readonly Color EMISSION_COLOR; // 0x10
	private static readonly Color EMISSION_CLEAR_COLOR; // 0x20
	private List`1 m_renderers; // 0x38
	private Material m_replaceableMaterial; // 0x40
	private Material m_buildableMaterial; // 0x48
	private Material m_focusedMaterial; // 0x50
	private Material m_originMaterial; // 0x58
	private Tween m_tween; // 0x60
	private static DelegateBridge __Hotfix0_SetHighlight; // 0x30
	private static DelegateBridge __Hotfix0_ResetTile; // 0x38
	private static DelegateBridge __Hotfix0_RefreshThemeConfig; // 0x40
	private static DelegateBridge __Hotfix0_Awake; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x1db0b38 VA: 0x75943c8b38
	protected override Boolean SetHighlight(HighlightType value, Boolean force) { }
	// RVA: 0x1db1078 VA: 0x75943c9078
	public override Void ResetTile() { }
	// RVA: 0x1db1100 VA: 0x75943c9100
	public override Void RefreshThemeConfig() { }
	// RVA: 0x1db1204 VA: 0x75943c9204
	private Void Awake() { }
	// RVA: 0x1db1600 VA: 0x75943c9600
	public Void .ctor() { }
	// RVA: 0x1db1704 VA: 0x75943c9704
	private static Void .cctor() { }
	// RVA: 0x1db17ac VA: 0x75943c97ac
	private Tween <SetHighlight>b__13_0(Material _) { }
	// RVA: 0x1db1978 VA: 0x75943c9978
	private Void <SetHighlight>b__13_2(Single val) { }
	// RVA: 0x1db1a38 VA: 0x75943c9a38
	private Boolean <>xLuaBaseProxy_SetHighlight(HighlightType P0, Boolean P1) { }
	// RVA: 0x1db1a44 VA: 0x75943c9a44
	private Void <>xLuaBaseProxy_ResetTile() { }
	// RVA: 0x1db1a4c VA: 0x75943c9a4c
	private Void <>xLuaBaseProxy_RefreshThemeConfig() { }
}
```