# UlpiaS3CastSkill

**Namespace:** `Torappu.Battle`


## Fields

- `Ability _restoreAbility`

- `Boolean _isManuallyDiscardable`

- `String _respawnPlaceTokenBuffKey`

- `String _respawnBBKey`

- `String _restoreBBKey`

- `String _skillProgressBBKey`

- `String _colBBKey`

- `String _rowBBKey`

- `String _locatedColBBKey`

- `String _locatedRowBBKey`

- `String _respawnInPlaceBBKey`

- `Boolean m_isCharacterResapwn`

- `FP m_respawnSkillProgress`

- `PeriodicTimer m_timer`


## Methods

- `Void _ResetSharedData(Blackboard)`

- `Boolean _RespawnToLocatedPos()`

- `Void _KillToken()`

- `Void _AddDynamicBuffTileExcludeCharacter(Character)`

- `Void _RemoveDynamicBuffTileExcludeCharacter(Character)`

- `Boolean _TriggerAbility()`

- `Boolean <>xLuaBaseProxy_IsDiscardable()`

- `FP <>xLuaBaseProxy_get_remainingProgress()`

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `Void <>xLuaBaseProxy_AssignData(SkillData, Character, Blackboard, Delta)`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Void <>xLuaBaseProxy_InterruptIfNot()`

- `Boolean <>xLuaBaseProxy_UseSkill(PlayerSide)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnOwnerFinish(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UlpiaS3CastSkill : CastSkillWithSuspendable
{
	private Ability _restoreAbility; // 0x128
	private Boolean _isManuallyDiscardable; // 0x130
	private String _respawnPlaceTokenBuffKey; // 0x138
	private String _respawnBBKey; // 0x140
	private String _restoreBBKey; // 0x148
	private String _skillProgressBBKey; // 0x150
	private String _colBBKey; // 0x158
	private String _rowBBKey; // 0x160
	private String _locatedColBBKey; // 0x168
	private String _locatedRowBBKey; // 0x170
	private String _respawnInPlaceBBKey; // 0x178
	public List`1 _resetBlackboard; // 0x180
	public List`1 _addRespawnBlackboard; // 0x188
	public List`1 _removeRespawnBlackboard; // 0x190
	private Boolean m_isCharacterResapwn; // 0x198
	private FP m_respawnSkillProgress; // 0x1a0
	private PeriodicTimer m_timer; // 0x1a8
	private List`1 m_tokens; // 0x1b0
	private static DelegateBridge __Hotfix0_IsDiscardable; // 0x0
	private static DelegateBridge __Hotfix0_get_remainingProgress; // 0x8
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x10
	private static DelegateBridge __Hotfix0_AssignData; // 0x18
	private static DelegateBridge __Hotfix0_OnBorn; // 0x20
	private static DelegateBridge __Hotfix0_InterruptIfNot; // 0x28
	private static DelegateBridge __Hotfix0_UseSkill; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_OnOwnerFinish; // 0x40
	private static DelegateBridge __Hotfix0__ResetSharedData; // 0x48
	private static DelegateBridge __Hotfix0__RespawnToLocatedPos; // 0x50
	private static DelegateBridge __Hotfix0__KillToken; // 0x58
	private static DelegateBridge __Hotfix0__AddDynamicBuffTileExcludeCharacter; // 0x60
	private static DelegateBridge __Hotfix0__RemoveDynamicBuffTileExcludeCharacter; // 0x68
	private static DelegateBridge __Hotfix0__TriggerAbility; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override FP remainingProgress { get; }
	public override Boolean isAffecting { get; }

	// RVA: 0x1b72ddc VA: 0x759418addc
	public override Boolean IsDiscardable() { }
	// RVA: 0x1b72e60 VA: 0x759418ae60
	public override FP get_remainingProgress() { }
	// RVA: 0x1b72f38 VA: 0x759418af38
	public override Boolean get_isAffecting() { }
	// RVA: 0x1b72fbc VA: 0x759418afbc
	public override Void AssignData(SkillData data, Character owner, Blackboard externalBlackboard, Delta modifier) { }
	// RVA: 0x1b73358 VA: 0x759418b358
	public override Void OnBorn() { }
	// RVA: 0x1b7354c VA: 0x759418b54c
	public override Void InterruptIfNot() { }
	// RVA: 0x1b738a0 VA: 0x759418b8a0
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x1b73964 VA: 0x759418b964
	protected override Void OnTick(FP deltaTime) { }
	// RVA: 0x1b73a58 VA: 0x759418ba58
	public override Void OnOwnerFinish(FinishReason reason) { }
	// RVA: 0x1b731f8 VA: 0x759418b1f8
	private Void _ResetSharedData(Blackboard blackboard) { }
	// RVA: 0x1b735d8 VA: 0x759418b5d8
	private Boolean _RespawnToLocatedPos() { }
	// RVA: 0x1b73ed8 VA: 0x759418bed8
	private Void _KillToken() { }
	// RVA: 0x1b73bf8 VA: 0x759418bbf8
	private Void _AddDynamicBuffTileExcludeCharacter(Character character) { }
	// RVA: 0x1b73d68 VA: 0x759418bd68
	private Void _RemoveDynamicBuffTileExcludeCharacter(Character character) { }
	// RVA: 0x1b7408c VA: 0x759418c08c
	private Boolean _TriggerAbility() { }
	// RVA: 0x1b74174 VA: 0x759418c174
	public Void .ctor() { }
	// RVA: 0x1b74374 VA: 0x759418c374
	private Boolean <>xLuaBaseProxy_IsDiscardable() { }
	// RVA: 0x1b7437c VA: 0x759418c37c
	private FP <>xLuaBaseProxy_get_remainingProgress() { }
	// RVA: 0x1b74384 VA: 0x759418c384
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x1b7438c VA: 0x759418c38c
	private Void <>xLuaBaseProxy_AssignData(SkillData P0, Character P1, Blackboard P2, Delta P3) { }
	// RVA: 0x1b74394 VA: 0x759418c394
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x1b7439c VA: 0x759418c39c
	private Void <>xLuaBaseProxy_InterruptIfNot() { }
	// RVA: 0x1b743a4 VA: 0x759418c3a4
	private Boolean <>xLuaBaseProxy_UseSkill(PlayerSide P0) { }
	// RVA: 0x1b743ac VA: 0x759418c3ac
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1b743b4 VA: 0x759418c3b4
	private Void <>xLuaBaseProxy_OnOwnerFinish(FinishReason P0) { }
}
```