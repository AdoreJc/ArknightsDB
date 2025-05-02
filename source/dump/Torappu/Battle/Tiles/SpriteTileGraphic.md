# SpriteTileGraphic

**Namespace:** `Torappu.Battle.Tiles`


## Fields

- `SpriteRenderer _sprite`

- `Color _buildableColor`

- `Color _focusColor`

- `Color _brightColor`

- `Color m_originColor`


## Properties

- `SpriteRenderer sprite`


## Methods

- `SpriteRenderer get_sprite()`

- `Void Awake()`

- `Boolean <>xLuaBaseProxy_SetHighlight(HighlightType, Boolean)`

- `Void <>xLuaBaseProxy_SetLitState(Boolean)`

- `Void <>xLuaBaseProxy_SetLitState(Int32)`

- `Void <>xLuaBaseProxy_SetLitStrength(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Tiles
public class SpriteTileGraphic : TileGraphic
{
	private SpriteRenderer _sprite; // 0x38
	private Color _buildableColor; // 0x40
	private Color _focusColor; // 0x50
	private Color _brightColor; // 0x60
	private Color m_originColor; // 0x70
	private static DelegateBridge __Hotfix0_get_sprite; // 0x0
	private static DelegateBridge __Hotfix0_SetHighlight; // 0x8
	private static DelegateBridge __Hotfix0_SetLitState; // 0x10
	private static DelegateBridge __Hotfix1_SetLitState; // 0x18
	private static DelegateBridge __Hotfix0_SetLitStrength; // 0x20
	private static DelegateBridge __Hotfix0_Awake; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected SpriteRenderer sprite { get; }

	// RVA: 0x1db1ad4 VA: 0x75943c9ad4
	protected SpriteRenderer get_sprite() { }
	// RVA: 0x1db1b3c VA: 0x75943c9b3c
	protected override Boolean SetHighlight(HighlightType value, Boolean force) { }
	// RVA: 0x1db1cb8 VA: 0x75943c9cb8
	public override Void SetLitState(Boolean state) { }
	// RVA: 0x1db1d88 VA: 0x75943c9d88
	public override Void SetLitState(Int32 litLevel) { }
	// RVA: 0x1db1e58 VA: 0x75943c9e58
	public override Void SetLitStrength(Single strength) { }
	// RVA: 0x1db1fa0 VA: 0x75943c9fa0
	private Void Awake() { }
	// RVA: 0x1db2020 VA: 0x75943ca020
	public Void .ctor() { }
	// RVA: 0x1db2100 VA: 0x75943ca100
	private Boolean <>xLuaBaseProxy_SetHighlight(HighlightType P0, Boolean P1) { }
	// RVA: 0x1db210c VA: 0x75943ca10c
	private Void <>xLuaBaseProxy_SetLitState(Boolean P0) { }
	// RVA: 0x1db2118 VA: 0x75943ca118
	private Void <>xLuaBaseProxy_SetLitState(Int32 P0) { }
	// RVA: 0x1db2120 VA: 0x75943ca120
	private Void <>xLuaBaseProxy_SetLitStrength(Single P0) { }
}
```