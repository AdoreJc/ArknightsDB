# ReedTile

**Namespace:** ` `


## Fields

- `String _igniteDurationKey`

- `String _extinctDurationKey`

- `String _coolDownDurationKey`

- `Range _reedRange`

- `Int32 m_currIgniteEffectIndex`

- `ReedTileTicker m_igniteTicker`

- `ReedTileTicker m_extinctTicker`

- `ReedTileTicker m_coolDownTicker`

- `Boolean m_canIgniteOtherTiles`


## Methods

- `Void OnFixedUpdate(FP)`

- `Void _igniteSurroundReedTiles()`

- `Boolean _ValidateTile(ReedTile)`

- `Void _SwitchToIgniteMode(ReedTile)`

- `Void _ResetAllTicker()`

- `Void _UpdateTickersInIgniteMode(Boolean)`

- `Void SwitchToOriginalIgniteMode()`

- `Void _FindSurroundReedTiles()`

- `Void _UpdateIgniteEffect()`

- `Void _SwitchIgniteEffect(Int32)`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`

- `Void <>xLuaBaseProxy_OnCharacterEnter(Character, Character)`

- `Void <>xLuaBaseProxy_OnCharacterLeave(Character)`

- `Void <>xLuaBaseProxy_OnSwitchMode(Int32)`

- `Void <>xLuaBaseProxy__UpdateEffects()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ReedTile : DynamicBuffTileFixed, IUpdateable
{
	private String _igniteDurationKey; // 0x1d0
	private String _extinctDurationKey; // 0x1d8
	private String _coolDownDurationKey; // 0x1e0
	private Range _reedRange; // 0x1e8
	private String[] _igniteEffectGroup; // 0x1f0
	private const Int32 EXTINCT_MODE_INDEX; // 0x0
	private const Int32 IGNITE_MODE_INDEX; // 0x0
	private const Int32 COOLDOWN_MODE_INDEX; // 0x0
	private const Int32 HIGHEST_INTENSITY_EFFECT_INDEX; // 0x0
	private const Single IGNITE_EFFECT_CHECK_POINT; // 0x0
	private Int32 m_currIgniteEffectIndex; // 0x1f8
	private ReedTileTicker m_igniteTicker; // 0x200
	private ReedTileTicker m_extinctTicker; // 0x208
	private ReedTileTicker m_coolDownTicker; // 0x210
	private Boolean m_canIgniteOtherTiles; // 0x218
	private List`1 m_surroundTiles; // 0x220
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnCharacterEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnCharacterLeave; // 0x10
	private static DelegateBridge __Hotfix0_OnSwitchMode; // 0x18
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x20
	private static DelegateBridge __Hotfix0__igniteSurroundReedTiles; // 0x28
	private static DelegateBridge __Hotfix0__ValidateTile; // 0x30
	private static DelegateBridge __Hotfix0__SwitchToIgniteMode; // 0x38
	private static DelegateBridge __Hotfix0__ResetAllTicker; // 0x40
	private static DelegateBridge __Hotfix0__UpdateTickersInIgniteMode; // 0x48
	private static DelegateBridge __Hotfix0_SwitchToOriginalIgniteMode; // 0x50
	private static DelegateBridge __Hotfix0__FindSurroundReedTiles; // 0x58
	private static DelegateBridge __Hotfix0__UpdateEffects; // 0x60
	private static DelegateBridge __Hotfix0__UpdateIgniteEffect; // 0x68
	private static DelegateBridge __Hotfix0__SwitchIgniteEffect; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x1b284e8 VA: 0x75941404e8
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x1b28a0c VA: 0x7594140a0c
	protected override Void OnCharacterEnter(Character newChar, Character oldChar) { }
	// RVA: 0x1b28ba0 VA: 0x7594140ba0
	protected override Void OnCharacterLeave(Character character) { }
	// RVA: 0x1b28c5c VA: 0x7594140c5c
	protected override Void OnSwitchMode(Int32 mode) { }
	// RVA: 0x1b28e04 VA: 0x7594140e04
	public Void OnFixedUpdate(FP fixedDeltaTime) { }
	// RVA: 0x1b29030 VA: 0x7594141030
	private Void _igniteSurroundReedTiles() { }
	// RVA: 0x1b29274 VA: 0x7594141274
	private Boolean _ValidateTile(ReedTile tile) { }
	// RVA: 0x1b29350 VA: 0x7594141350
	private Void _SwitchToIgniteMode(ReedTile reedTile) { }
	// RVA: 0x1b28d7c VA: 0x7594140d7c
	private Void _ResetAllTicker() { }
	// RVA: 0x1b28afc VA: 0x7594140afc
	private Void _UpdateTickersInIgniteMode(Boolean hasCharacter) { }
	// RVA: 0x1b294e0 VA: 0x75941414e0
	public Void SwitchToOriginalIgniteMode() { }
	// RVA: 0x1b287fc VA: 0x75941407fc
	private Void _FindSurroundReedTiles() { }
	// RVA: 0x1b295d8 VA: 0x75941415d8
	protected override Void _UpdateEffects() { }
	// RVA: 0x1b29140 VA: 0x7594141140
	private Void _UpdateIgniteEffect() { }
	// RVA: 0x1b29674 VA: 0x7594141674
	private Void _SwitchIgniteEffect(Int32 index) { }
	// RVA: 0x1b29a20 VA: 0x7594141a20
	public Void .ctor() { }
	// RVA: 0x1b29aec VA: 0x7594141aec
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
	// RVA: 0x1b29af4 VA: 0x7594141af4
	private Void <>xLuaBaseProxy_OnCharacterEnter(Character P0, Character P1) { }
	// RVA: 0x1b29afc VA: 0x7594141afc
	private Void <>xLuaBaseProxy_OnCharacterLeave(Character P0) { }
	// RVA: 0x1b29b04 VA: 0x7594141b04
	private Void <>xLuaBaseProxy_OnSwitchMode(Int32 P0) { }
	// RVA: 0x1b29b0c VA: 0x7594141b0c
	private Void <>xLuaBaseProxy__UpdateEffects() { }
}
```