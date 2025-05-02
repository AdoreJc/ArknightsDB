# Talent

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _attachInDummy`

- `Int32 _defaultModeIndex`

- `Int32 _attackBlackboardModeIndex`

- `Boolean _overrideDefaultRangeId`

- `Boolean _applyTalentScale`

- `Boolean _influenceSkillBlackboard`

- `Boolean _applyTalentRange`

- `Boolean _applyBlackboardBySkill`

- `Boolean _applyStrBlackboardBySkill`

- `Boolean _writeRangeIdToProjectileBlackboard`

- `Boolean _affectWhenNotRootTalent`

- `Boolean _scaleCertainKeyFlag`

- `Boolean _scaleCertainMode`


## Properties

- `Boolean scaleCertainMode`

- `Boolean useAttackBlackboardModeIndex`

- `Boolean applyTalentScaleModeValid`


## Methods

- `Boolean get_scaleCertainMode()`

- `Boolean get_useAttackBlackboardModeIndex()`

- `Boolean get_applyTalentScaleModeValid()`

- `Boolean <>xLuaBaseProxy_get_attachInDummy()`

- `Boolean <>xLuaBaseProxy_get_affectWhenNotRootTalent()`

- `Boolean <>xLuaBaseProxy_get_overrideDefaultRangeId()`

- `Boolean <>xLuaBaseProxy_get_applyTalentScale()`

- `Int32 <>xLuaBaseProxy_get_defaultModeIndex()`

- `Boolean <>xLuaBaseProxy_get_scaleCertainKeyFlag()`

- `Boolean <>xLuaBaseProxy_get_applyTalentRangeBySkill()`

- `Boolean <>xLuaBaseProxy_get_applyBlackboardBySkill()`

- `Boolean <>xLuaBaseProxy_get_applyStrBlackboardBySkill()`

- `Boolean <>xLuaBaseProxy_get_writeRangeIdToProjectileBlackboard()`

- `Blackboard <>xLuaBaseProxy_GenerateAttackBlackboard(UnitMode)`

- `Blackboard <>xLuaBaseProxy_GetSkillBlackboardFromRawData(TalentData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Talent : BasicTalent
{
	private Boolean _attachInDummy; // 0x48
	private Int32 _defaultModeIndex; // 0x4c
	private Int32 _attackBlackboardModeIndex; // 0x50
	private Int32[] _extraAttackBlackboardModeIndices; // 0x58
	private Boolean _overrideDefaultRangeId; // 0x60
	private Boolean _applyTalentScale; // 0x61
	private Boolean _influenceSkillBlackboard; // 0x62
	private Boolean _applyTalentRange; // 0x63
	private Boolean _applyBlackboardBySkill; // 0x64
	private Boolean _applyStrBlackboardBySkill; // 0x65
	private Boolean _writeRangeIdToProjectileBlackboard; // 0x66
	private Boolean _affectWhenNotRootTalent; // 0x67
	private Boolean _scaleCertainKeyFlag; // 0x68
	private String[] _scaleCertainKeyList; // 0x70
	private Boolean _scaleCertainMode; // 0x78
	private List`1 _scaleModeIndices; // 0x80
	private static DelegateBridge __Hotfix0_get_attachInDummy; // 0x0
	private static DelegateBridge __Hotfix0_get_affectWhenNotRootTalent; // 0x8
	private static DelegateBridge __Hotfix0_get_overrideDefaultRangeId; // 0x10
	private static DelegateBridge __Hotfix0_get_applyTalentScale; // 0x18
	private static DelegateBridge __Hotfix0_get_scaleCertainMode; // 0x20
	private static DelegateBridge __Hotfix0_get_defaultModeIndex; // 0x28
	private static DelegateBridge __Hotfix0_get_scaleCertainKeyFlag; // 0x30
	private static DelegateBridge __Hotfix0_get_scaleCertainKeyList; // 0x38
	private static DelegateBridge __Hotfix0_get_applyTalentRangeBySkill; // 0x40
	private static DelegateBridge __Hotfix0_get_applyBlackboardBySkill; // 0x48
	private static DelegateBridge __Hotfix0_get_applyStrBlackboardBySkill; // 0x50
	private static DelegateBridge __Hotfix0_get_writeRangeIdToProjectileBlackboard; // 0x58
	private static DelegateBridge __Hotfix0_get_useAttackBlackboardModeIndex; // 0x60
	private static DelegateBridge __Hotfix0_get_applyTalentScaleModeValid; // 0x68
	private static DelegateBridge __Hotfix0_GenerateAttackBlackboard; // 0x70
	private static DelegateBridge __Hotfix0_GetSkillBlackboardFromRawData; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public override Boolean attachInDummy { get; }
	public override Boolean affectWhenNotRootTalent { get; }
	public override Boolean overrideDefaultRangeId { get; }
	public override Boolean applyTalentScale { get; }
	public Boolean scaleCertainMode { get; }
	public override Int32 defaultModeIndex { get; }
	public override Boolean scaleCertainKeyFlag { get; }
	protected override String[] scaleCertainKeyList { get; }
	public override Boolean applyTalentRangeBySkill { get; }
	public override Boolean applyBlackboardBySkill { get; }
	public override Boolean applyStrBlackboardBySkill { get; }
	public override Boolean writeRangeIdToProjectileBlackboard { get; }
	private Boolean useAttackBlackboardModeIndex { get; }
	private Boolean applyTalentScaleModeValid { get; }

	// RVA: 0x1b81008 VA: 0x7594199008
	public override Boolean get_attachInDummy() { }
	// RVA: 0x1b81070 VA: 0x7594199070
	public override Boolean get_affectWhenNotRootTalent() { }
	// RVA: 0x1b810d8 VA: 0x75941990d8
	public override Boolean get_overrideDefaultRangeId() { }
	// RVA: 0x1b81140 VA: 0x7594199140
	public override Boolean get_applyTalentScale() { }
	// RVA: 0x1b811d4 VA: 0x75941991d4
	public Boolean get_scaleCertainMode() { }
	// RVA: 0x1b81354 VA: 0x7594199354
	public override Int32 get_defaultModeIndex() { }
	// RVA: 0x1b813bc VA: 0x75941993bc
	public override Boolean get_scaleCertainKeyFlag() { }
	// RVA: 0x1b81424 VA: 0x7594199424
	protected override String[] get_scaleCertainKeyList() { }
	// RVA: 0x1b8148c VA: 0x759419948c
	public override Boolean get_applyTalentRangeBySkill() { }
	// RVA: 0x1b814f4 VA: 0x75941994f4
	public override Boolean get_applyBlackboardBySkill() { }
	// RVA: 0x1b8155c VA: 0x759419955c
	public override Boolean get_applyStrBlackboardBySkill() { }
	// RVA: 0x1b815c4 VA: 0x75941995c4
	public override Boolean get_writeRangeIdToProjectileBlackboard() { }
	// RVA: 0x1b8162c VA: 0x759419962c
	private Boolean get_useAttackBlackboardModeIndex() { }
	// RVA: 0x1b8123c VA: 0x759419923c
	private Boolean get_applyTalentScaleModeValid() { }
	// RVA: 0x1b8169c VA: 0x759419969c
	public override Blackboard GenerateAttackBlackboard(UnitMode mode) { }
	// RVA: 0x1b817c0 VA: 0x75941997c0
	public override Blackboard GetSkillBlackboardFromRawData(TalentData talentData) { }
	// RVA: 0x1b7517c VA: 0x759418d17c
	public Void .ctor() { }
	// RVA: 0x1b8189c VA: 0x759419989c
	private Boolean <>xLuaBaseProxy_get_attachInDummy() { }
	// RVA: 0x1b818a0 VA: 0x75941998a0
	private Boolean <>xLuaBaseProxy_get_affectWhenNotRootTalent() { }
	// RVA: 0x1b818a4 VA: 0x75941998a4
	private Boolean <>xLuaBaseProxy_get_overrideDefaultRangeId() { }
	// RVA: 0x1b818a8 VA: 0x75941998a8
	private Boolean <>xLuaBaseProxy_get_applyTalentScale() { }
	// RVA: 0x1b818ac VA: 0x75941998ac
	private Int32 <>xLuaBaseProxy_get_defaultModeIndex() { }
	// RVA: 0x1b818b0 VA: 0x75941998b0
	private Boolean <>xLuaBaseProxy_get_scaleCertainKeyFlag() { }
	// RVA: 0x1b818b4 VA: 0x75941998b4
	private String[] <>xLuaBaseProxy_get_scaleCertainKeyList() { }
	// RVA: 0x1b818b8 VA: 0x75941998b8
	private Boolean <>xLuaBaseProxy_get_applyTalentRangeBySkill() { }
	// RVA: 0x1b818bc VA: 0x75941998bc
	private Boolean <>xLuaBaseProxy_get_applyBlackboardBySkill() { }
	// RVA: 0x1b818c0 VA: 0x75941998c0
	private Boolean <>xLuaBaseProxy_get_applyStrBlackboardBySkill() { }
	// RVA: 0x1b818c4 VA: 0x75941998c4
	private Boolean <>xLuaBaseProxy_get_writeRangeIdToProjectileBlackboard() { }
	// RVA: 0x1b818c8 VA: 0x75941998c8
	private Blackboard <>xLuaBaseProxy_GenerateAttackBlackboard(UnitMode P0) { }
	// RVA: 0x1b818cc VA: 0x75941998cc
	private Blackboard <>xLuaBaseProxy_GetSkillBlackboardFromRawData(TalentData P0) { }
}
```