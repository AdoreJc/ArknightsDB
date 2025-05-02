# MeshTileGraphic

**Namespace:** `Torappu.Battle.Tiles`


## Fields

- `Renderer m_renderer`

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
public class MeshTileGraphic : TileGraphic
{
	private const String BUILDABLE_MATERIAL_KEY; // 0x0
	private const String FOCUSED_MATERIAL_KEY; // 0x0
	private const String REPLACEABLE_MATERIAL_KEY; // 0x0
	private const Single TWEEN_LOOP_TIME; // 0x0
	private static readonly Color FOCUSED_COLOR; // 0x0
	private static readonly Color EMISSION_COLOR; // 0x10
	private static readonly Color EMISSION_CLEAR_COLOR; // 0x20
	private Renderer m_renderer; // 0x38
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


	// RVA: 0x1daff5c VA: 0x75943c7f5c
	protected override Boolean SetHighlight(HighlightType value, Boolean force) { }
	// RVA: 0x1db017c VA: 0x75943c817c
	public override Void ResetTile() { }
	// RVA: 0x1db0204 VA: 0x75943c8204
	public override Void RefreshThemeConfig() { }
	// RVA: 0x1db0308 VA: 0x75943c8308
	private Void Awake() { }
	// RVA: 0x1db06c4 VA: 0x75943c86c4
	public Void .ctor() { }
	// RVA: 0x1db0768 VA: 0x75943c8768
	private static Void .cctor() { }
	// RVA: 0x1db0810 VA: 0x75943c8810
	private Tween <SetHighlight>b__13_0(Material _) { }
	// RVA: 0x1db09dc VA: 0x75943c89dc
	private Void <SetHighlight>b__13_2(Single val) { }
	// RVA: 0x1db0a9c VA: 0x75943c8a9c
	private Boolean <>xLuaBaseProxy_SetHighlight(HighlightType P0, Boolean P1) { }
	// RVA: 0x1db0aa8 VA: 0x75943c8aa8
	private Void <>xLuaBaseProxy_ResetTile() { }
	// RVA: 0x1db0ab0 VA: 0x75943c8ab0
	private Void <>xLuaBaseProxy_RefreshThemeConfig() { }
}
```