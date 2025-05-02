# RebornTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _maxRespawnCnt`

- `Int32 _modeIndex`

- `Boolean _keepAlive`

- `Boolean _clearEffectsAfterReborn`

- `Boolean _useAbilityToHandle`

- `String _abilityName`

- `Boolean _finishHandleAbilityAfterReborn`

- `Single _hpRechargeRatio`

- `Boolean _detachAbilityWhenReborn`

- `Boolean _rebornAfterWave`

- `Int32 _rebornAfterWaveCnt`

- `String _validWhenContainsBuff`

- `Int32 m_maxRespawnCnt`

- `Int32 m_respawnCnt`

- `RebornData m_defaultRespawnData`


## Properties

- `Boolean useAbilityToHandle`

- `Boolean needPlayEffectWhenReborn`


## Methods

- `Boolean get_useAbilityToHandle()`

- `Boolean get_needPlayEffectWhenReborn()`

- `Void ModifyHpRatio(FP)`

- `Void _OnRebornAfterFakeDeath(Object)`

- `Void _OnAfterReborn(Object)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Boolean <>xLuaBaseProxy_CheckReborn(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RebornTalent : Talent
{
	private Int32 _maxRespawnCnt; // 0x88
	private Int32 _modeIndex; // 0x8c
	private Boolean _keepAlive; // 0x90
	private BuffData[] _buffs; // 0x98
	private String[] _effects; // 0xa0
	private Boolean _clearEffectsAfterReborn; // 0xa8
	private Boolean _useAbilityToHandle; // 0xa9
	private String _abilityName; // 0xb0
	private Boolean _finishHandleAbilityAfterReborn; // 0xb8
	private Single _hpRechargeRatio; // 0xbc
	private List`1 _buffsRetainedWhenReborn; // 0xc0
	private Boolean _detachAbilityWhenReborn; // 0xc8
	private Boolean _rebornAfterWave; // 0xc9
	private Int32 _rebornAfterWaveCnt; // 0xcc
	private String _validWhenContainsBuff; // 0xd0
	private List`1 _extraRebornDataPresets; // 0xd8
	protected Int32 m_maxRespawnCnt; // 0xe0
	protected Int32 m_respawnCnt; // 0xe4
	protected RebornData m_defaultRespawnData; // 0xe8
	protected List`1 m_respawnDataList; // 0x130
	private ObjectPtr`1 m_handleAbility; // 0x138
	private static DelegateBridge __Hotfix0_get_useAbilityToHandle; // 0x0
	private static DelegateBridge __Hotfix0_get_needPlayEffectWhenReborn; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x18
	private static DelegateBridge __Hotfix0_AssignData; // 0x20
	private static DelegateBridge __Hotfix0_DoAttach; // 0x28
	private static DelegateBridge __Hotfix0_DoDetach; // 0x30
	private static DelegateBridge __Hotfix0_CheckReborn; // 0x38
	private static DelegateBridge __Hotfix0_ModifyHpRatio; // 0x40
	private static DelegateBridge __Hotfix0__OnRebornAfterFakeDeath; // 0x48
	private static DelegateBridge __Hotfix0__OnAfterReborn; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected Boolean useAbilityToHandle { get; }
	protected Boolean needPlayEffectWhenReborn { get; }

	// RVA: 0x1b7e42c VA: 0x759419642c
	protected Boolean get_useAbilityToHandle() { }
	// RVA: 0x1b7e494 VA: 0x7594196494
	protected Boolean get_needPlayEffectWhenReborn() { }
	// RVA: 0x1b7e53c VA: 0x759419653c
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1b7e6dc VA: 0x75941966dc
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1b7e868 VA: 0x7594196868
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b7eedc VA: 0x7594196edc
	protected override Void DoAttach() { }
	// RVA: 0x1b7f04c VA: 0x759419704c
	protected override Void DoDetach() { }
	// RVA: 0x1b7ce7c VA: 0x7594194e7c
	public override Boolean CheckReborn(out RebornData respawnData) { }
	// RVA: 0x1b7f1bc VA: 0x75941971bc
	public Void ModifyHpRatio(FP hpRatio) { }
	// RVA: 0x1b7f3a0 VA: 0x75941973a0
	private Void _OnRebornAfterFakeDeath(Object arg) { }
	// RVA: 0x1b7f5e4 VA: 0x75941975e4
	private Void _OnAfterReborn(Object arg) { }
	// RVA: 0x1b7cdf8 VA: 0x7594194df8
	public Void .ctor() { }
	// RVA: 0x1b7f6ec VA: 0x75941976ec
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1b7f6f0 VA: 0x75941976f0
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1b7f6f4 VA: 0x75941976f4
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
	// RVA: 0x1b7f6f8 VA: 0x75941976f8
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b7f6fc VA: 0x75941976fc
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1b7f700 VA: 0x7594197700
	private Boolean <>xLuaBaseProxy_CheckReborn(out RebornData P0) { }
}
```