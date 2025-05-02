# Trap

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _withdrawable`

- `Boolean _ignoreParentWithdrawable`

- `Boolean _rewriteTileOptions`

- `Boolean _rewriteTileHeightTypeOnMode`

- `Boolean _rewriteTileHeightTypeOnModeBySelf`

- `Boolean _ignoreBlockAnyRoutes`

- `Single _blockRadiusSquare`

- `Boolean _hideTileOptions`

- `Boolean _hideSpBarWhenEmpty`

- `Boolean _hideSpBarWhenFull`

- `Boolean _hideSpBarWhenSkill`

- `Boolean _hideSpBarWhenNotHaveSkill`

- `Boolean _syncSpViaTiles`

- `Boolean _disableUIHub`

- `String _hitRangeId`

- `SideType m_sideType`

- `Boolean <fogHideUIFlag>k__BackingField`


## Properties

- `Boolean isGiantTrap`

- `Boolean syncSpViaTiles`

- `Boolean hideSpBarWhenEmpty`

- `Boolean hideSpBarWhenFull`

- `Boolean hideSpBarWhenSkill`

- `Boolean hideSpBarWhenNotHaveSkill`

- `Boolean disableUIHub`

- `Boolean fogHideUIFlag`

- `Boolean rewriteTileOptions`

- `Boolean ignoreBlockAnyRoutes`

- `Options tileOptions`

- `Boolean keepCurrentPassableMask`

- `Boolean rewriteTileHeightType`

- `Boolean rewriteTileHeight`

- `Single rewriteHeight`

- `Boolean rewriteTileAdvancedBuildMask`


## Methods

- `Boolean get_isGiantTrap()`

- `Boolean get_syncSpViaTiles()`

- `Boolean get_hideSpBarWhenEmpty()`

- `Boolean get_hideSpBarWhenFull()`

- `Boolean get_hideSpBarWhenSkill()`

- `Boolean get_hideSpBarWhenNotHaveSkill()`

- `Boolean get_disableUIHub()`

- `Boolean get_fogHideUIFlag()`

- `Void set_fogHideUIFlag(Boolean)`

- `Boolean get_rewriteTileOptions()`

- `Boolean get_ignoreBlockAnyRoutes()`

- `Options get_tileOptions()`

- `Boolean get_keepCurrentPassableMask()`

- `Boolean get_rewriteTileHeightType()`

- `Boolean get_rewriteTileHeight()`

- `Single get_rewriteHeight()`

- `Boolean get_rewriteTileAdvancedBuildMask()`

- `Void _ResetHitRangeGrids()`

- `Boolean <>xLuaBaseProxy_get_hideTileOption()`

- `String <>xLuaBaseProxy_get_hitRangeId()`

- `Boolean <>xLuaBaseProxy_SetSpInternal(FP, Boolean)`

- `SideType <>xLuaBaseProxy_get_initSideType()`

- `Boolean <>xLuaBaseProxy_get_withdrawable()`

- `Single <>xLuaBaseProxy_get_blockRadiusSquare()`

- `String <>xLuaBaseProxy_get_startEffect()`

- `String <>xLuaBaseProxy_get_deadEffect()`

- `Void <>xLuaBaseProxy_OnInit(Single)`

- `Void <>xLuaBaseProxy_OnSwitchMode(UnitMode, UnitMode, Boolean)`

- `Boolean <>xLuaBaseProxy_CheckHasFilterTag(String)`

- `Boolean <>xLuaBaseProxy_IsInHitRange(HitRangeOption)`

- `Void <>xLuaBaseProxy_SwitchSide(SideType)`

- `Void <>xLuaBaseProxy_OnDirectionChanged()`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Trap : Token
{
	private Boolean _withdrawable; // 0x4b4
	private Boolean _ignoreParentWithdrawable; // 0x4b5
	private Boolean _rewriteTileOptions; // 0x4b6
	private Boolean _rewriteTileHeightTypeOnMode; // 0x4b7
	private Boolean _rewriteTileHeightTypeOnModeBySelf; // 0x4b8
	private Boolean _ignoreBlockAnyRoutes; // 0x4b9
	private Single _blockRadiusSquare; // 0x4bc
	private String[] _filterTag; // 0x4c0
	private Boolean _hideTileOptions; // 0x4c8
	private Boolean _hideSpBarWhenEmpty; // 0x4c9
	private Boolean _hideSpBarWhenFull; // 0x4ca
	private Boolean _hideSpBarWhenSkill; // 0x4cb
	private Boolean _hideSpBarWhenNotHaveSkill; // 0x4cc
	public Boolean _syncSpViaTiles; // 0x4cd
	private Boolean _disableUIHub; // 0x4ce
	private String _hitRangeId; // 0x4d0
	private List`1 m_hitRangeGrids; // 0x4d8
	private SideType m_sideType; // 0x4e0
	private ListSet`1 m_syncSpList; // 0x4e8
	private Boolean <fogHideUIFlag>k__BackingField; // 0x4f0
	private static DelegateBridge __Hotfix0_get_isGiantTrap; // 0x0
	private static DelegateBridge __Hotfix0_get_syncSpViaTiles; // 0x8
	private static DelegateBridge __Hotfix0_get_hideTileOption; // 0x10
	private static DelegateBridge __Hotfix0_get_hideSpBarWhenEmpty; // 0x18
	private static DelegateBridge __Hotfix0_get_hideSpBarWhenFull; // 0x20
	private static DelegateBridge __Hotfix0_get_hideSpBarWhenSkill; // 0x28
	private static DelegateBridge __Hotfix0_get_hideSpBarWhenNotHaveSkill; // 0x30
	private static DelegateBridge __Hotfix0_get_hitRangeId; // 0x38
	private static DelegateBridge __Hotfix0_SetSpInternal; // 0x40
	private static DelegateBridge __Hotfix0_get_initSideType; // 0x48
	private static DelegateBridge __Hotfix0_get_disableUIHub; // 0x50
	private static DelegateBridge __Hotfix0_get_fogHideUIFlag; // 0x58
	private static DelegateBridge __Hotfix0_set_fogHideUIFlag; // 0x60
	private static DelegateBridge __Hotfix0_get_withdrawable; // 0x68
	private static DelegateBridge __Hotfix0_get_blockRadiusSquare; // 0x70
	private static DelegateBridge __Hotfix0_get_rewriteTileOptions; // 0x78
	private static DelegateBridge __Hotfix0_get_ignoreBlockAnyRoutes; // 0x80
	private static DelegateBridge __Hotfix0_get_tileOptions; // 0x88
	private static DelegateBridge __Hotfix0_get_keepCurrentPassableMask; // 0x90
	private static DelegateBridge __Hotfix0_get_rewriteTileHeightType; // 0x98
	private static DelegateBridge __Hotfix0_get_rewriteTileHeight; // 0xa0
	private static DelegateBridge __Hotfix0_get_rewriteHeight; // 0xa8
	private static DelegateBridge __Hotfix0_get_rewriteTileAdvancedBuildMask; // 0xb0
	private static DelegateBridge __Hotfix0_get_startEffect; // 0xb8
	private static DelegateBridge __Hotfix0_get_deadEffect; // 0xc0
	private static DelegateBridge __Hotfix0_OnInit; // 0xc8
	private static DelegateBridge __Hotfix0_OnSwitchMode; // 0xd0
	private static DelegateBridge __Hotfix0_CheckHasFilterTag; // 0xd8
	private static DelegateBridge __Hotfix0_IsInHitRange; // 0xe0
	private static DelegateBridge __Hotfix0__ResetHitRangeGrids; // 0xe8
	private static DelegateBridge __Hotfix0_SwitchSide; // 0xf0
	private static DelegateBridge __Hotfix0_OnDirectionChanged; // 0xf8
	private static DelegateBridge __Hotfix0_OnReset; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	protected Boolean isGiantTrap { get; }
	public Boolean syncSpViaTiles { get; }
	public override Boolean hideTileOption { get; }
	public Boolean hideSpBarWhenEmpty { get; }
	public Boolean hideSpBarWhenFull { get; }
	public Boolean hideSpBarWhenSkill { get; }
	public Boolean hideSpBarWhenNotHaveSkill { get; }
	public override String hitRangeId { get; }
	protected override SideType initSideType { get; }
	public Boolean disableUIHub { get; }
	public Boolean fogHideUIFlag { get; set; }
	public override Boolean withdrawable { get; }
	public override Single blockRadiusSquare { get; }
	public Boolean rewriteTileOptions { get; }
	public Boolean ignoreBlockAnyRoutes { get; }
	public Options tileOptions { get; }
	public Boolean keepCurrentPassableMask { get; }
	public Boolean rewriteTileHeightType { get; }
	public Boolean rewriteTileHeight { get; }
	public Single rewriteHeight { get; }
	public Boolean rewriteTileAdvancedBuildMask { get; }
	protected override String startEffect { get; }
	protected override String deadEffect { get; }

	// RVA: 0x1c2ab68 VA: 0x7594242b68
	protected Boolean get_isGiantTrap() { }
	// RVA: 0x1c2ac18 VA: 0x7594242c18
	public Boolean get_syncSpViaTiles() { }
	// RVA: 0x1c2ac80 VA: 0x7594242c80
	public override Boolean get_hideTileOption() { }
	// RVA: 0x1c2ace8 VA: 0x7594242ce8
	public Boolean get_hideSpBarWhenEmpty() { }
	// RVA: 0x1c2ad50 VA: 0x7594242d50
	public Boolean get_hideSpBarWhenFull() { }
	// RVA: 0x1c2adb8 VA: 0x7594242db8
	public Boolean get_hideSpBarWhenSkill() { }
	// RVA: 0x1c2ae20 VA: 0x7594242e20
	public Boolean get_hideSpBarWhenNotHaveSkill() { }
	// RVA: 0x1c2ae88 VA: 0x7594242e88
	public override String get_hitRangeId() { }
	// RVA: 0x1c2aef0 VA: 0x7594242ef0
	protected override Boolean SetSpInternal(FP value, Boolean force) { }
	// RVA: 0x1c2b1fc VA: 0x75942431fc
	protected override SideType get_initSideType() { }
	// RVA: 0x1c2b278 VA: 0x7594243278
	public Boolean get_disableUIHub() { }
	// RVA: 0x1c2b2f8 VA: 0x75942432f8
	public Boolean get_fogHideUIFlag() { }
	// RVA: 0x1c2b360 VA: 0x7594243360
	public Void set_fogHideUIFlag(Boolean value) { }
	// RVA: 0x1c25210 VA: 0x759423d210
	public override Boolean get_withdrawable() { }
	// RVA: 0x1c21e34 VA: 0x7594239e34
	public override Single get_blockRadiusSquare() { }
	// RVA: 0x1c2b3e0 VA: 0x75942433e0
	public Boolean get_rewriteTileOptions() { }
	// RVA: 0x1c2b448 VA: 0x7594243448
	public Boolean get_ignoreBlockAnyRoutes() { }
	// RVA: 0x1c2b4b0 VA: 0x75942434b0
	public Options get_tileOptions() { }
	// RVA: 0x1c2b5f4 VA: 0x75942435f4
	public Boolean get_keepCurrentPassableMask() { }
	// RVA: 0x1c2b710 VA: 0x7594243710
	public Boolean get_rewriteTileHeightType() { }
	// RVA: 0x1c2b82c VA: 0x759424382c
	public Boolean get_rewriteTileHeight() { }
	// RVA: 0x1c2b948 VA: 0x7594243948
	public Single get_rewriteHeight() { }
	// RVA: 0x1c2ba64 VA: 0x7594243a64
	public Boolean get_rewriteTileAdvancedBuildMask() { }
	// RVA: 0x1c2bb80 VA: 0x7594243b80
	protected override String get_startEffect() { }
	// RVA: 0x1c2bbe8 VA: 0x7594243be8
	protected override String get_deadEffect() { }
	// RVA: 0x1c267bc VA: 0x759423e7bc
	protected override Void OnInit(Single initHeight) { }
	// RVA: 0x1c2bff8 VA: 0x7594243ff8
	protected override Void OnSwitchMode(UnitMode next, UnitMode last, Boolean restartFSM) { }
	// RVA: 0x1c2c3f4 VA: 0x75942443f4
	public override Boolean CheckHasFilterTag(String unitTag) { }
	// RVA: 0x1c2c4a0 VA: 0x75942444a0
	public override Boolean IsInHitRange(HitRangeOption options) { }
	// RVA: 0x1c2bc50 VA: 0x7594243c50
	private Void _ResetHitRangeGrids() { }
	// RVA: 0x1c2c5c0 VA: 0x75942445c0
	public override Void SwitchSide(SideType newSide) { }
	// RVA: 0x1c2c724 VA: 0x7594244724
	public override Void OnDirectionChanged() { }
	// RVA: 0x1c2c798 VA: 0x7594244798
	protected override Void OnReset() { }
	// RVA: 0x1c24310 VA: 0x759423c310
	public Void .ctor() { }
	// RVA: 0x1c2c814 VA: 0x7594244814
	private Boolean <>xLuaBaseProxy_get_hideTileOption() { }
	// RVA: 0x1c2c81c VA: 0x759424481c
	private String <>xLuaBaseProxy_get_hitRangeId() { }
	// RVA: 0x1c2c8a4 VA: 0x75942448a4
	private Boolean <>xLuaBaseProxy_SetSpInternal(FP P0, Boolean P1) { }
	// RVA: 0x1c2c8b0 VA: 0x75942448b0
	private SideType <>xLuaBaseProxy_get_initSideType() { }
	// RVA: 0x1c2c8b4 VA: 0x75942448b4
	private Boolean <>xLuaBaseProxy_get_withdrawable() { }
	// RVA: 0x1c2c8bc VA: 0x75942448bc
	private Single <>xLuaBaseProxy_get_blockRadiusSquare() { }
	// RVA: 0x1c2c8c4 VA: 0x75942448c4
	private String <>xLuaBaseProxy_get_startEffect() { }
	// RVA: 0x1c2c8cc VA: 0x75942448cc
	private String <>xLuaBaseProxy_get_deadEffect() { }
	// RVA: 0x1c2c8d4 VA: 0x75942448d4
	private Void <>xLuaBaseProxy_OnInit(Single P0) { }
	// RVA: 0x1c2c8dc VA: 0x75942448dc
	private Void <>xLuaBaseProxy_OnSwitchMode(UnitMode P0, UnitMode P1, Boolean P2) { }
	// RVA: 0x1c2c8e4 VA: 0x75942448e4
	private Boolean <>xLuaBaseProxy_CheckHasFilterTag(String P0) { }
	// RVA: 0x1c2c8ec VA: 0x75942448ec
	private Boolean <>xLuaBaseProxy_IsInHitRange(HitRangeOption P0) { }
	// RVA: 0x1c2c928 VA: 0x7594244928
	private Void <>xLuaBaseProxy_SwitchSide(SideType P0) { }
	// RVA: 0x1c2c92c VA: 0x759424492c
	private Void <>xLuaBaseProxy_OnDirectionChanged() { }
	// RVA: 0x1c2c934 VA: 0x7594244934
	private Void <>xLuaBaseProxy_OnReset() { }
}
```