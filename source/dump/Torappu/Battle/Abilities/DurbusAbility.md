# DurbusAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _randomOffsetBound`

- `TargetValidator _targetValidator`

- `Boolean _useHostRoute`

- `Boolean _appearOnTileCenter`

- `Boolean _passengerToNearestEndPoint`

- `Boolean _passengerUseBranchRoute`

- `Single _delayToReleasePassengers`

- `Boolean _onlySearchPassengerInSpecifiedMode`

- `Int32 _modeIndex`

- `Boolean _disablePassengerAppearColor`

- `String _effectOnPassengerWhenRelease`

- `String _effectWhenAddPassenger`

- `Boolean _setToHostPosBeforeReassignRoute`

- `Boolean _assignPassengerCountToBb`

- `Boolean _passengerAsCarryBuffSource`

- `Boolean _ignoreHost`

- `Int32 m_maxCount`

- `Int32 m_passengerEffectIndex`

- `Enemy m_host`

- `Boolean m_searchPassengersStatus`


## Methods

- `Void _UpdatePassengerEffect()`

- `Void _FinishPassengerEffect()`

- `Boolean _VerifyCurrentMode(Int32)`

- `Boolean _SearchPassengers()`

- `Void ReleaseAllPassengers(Boolean, Nullable`1, Boolean)`

- `Boolean ReleaseLastPassenger(Boolean, Nullable`1, Boolean)`

- `Boolean KillLastPassenger()`

- `Boolean CheckPassengersExits()`

- `Void MarkCurrentPassengers()`

- `Void SetSearchPassengersStatus(Boolean)`

- `Void _ReleasePassenger(Enemy, Boolean, Nullable`1)`

- `Void _DoReleasePassengers(Enemy, Vector2)`

- `SelectTargetTiming <>xLuaBaseProxy_get_selectTargetTiming()`

- `Boolean <>xLuaBaseProxy_get_allowNoTarget()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class DurbusAbility : AbilityStandard
{
	private Single _randomOffsetBound; // 0x108
	private String[] _passengerEffects; // 0x110
	protected BuffData[] _passiveBuffs; // 0x118
	private TargetValidator _targetValidator; // 0x120
	private Boolean _useHostRoute; // 0x128
	private Boolean _appearOnTileCenter; // 0x129
	private Boolean _passengerToNearestEndPoint; // 0x12a
	private Boolean _passengerUseBranchRoute; // 0x12b
	private Single _delayToReleasePassengers; // 0x12c
	private Boolean _onlySearchPassengerInSpecifiedMode; // 0x130
	private Int32 _modeIndex; // 0x134
	private Int32[] _extraModeIndex; // 0x138
	private Boolean _disablePassengerAppearColor; // 0x140
	private String _effectOnPassengerWhenRelease; // 0x148
	private String _effectWhenAddPassenger; // 0x150
	private Boolean _setToHostPosBeforeReassignRoute; // 0x158
	private Boolean _assignPassengerCountToBb; // 0x159
	private BuffData[] _buffsWhenCarryPassenger; // 0x160
	private Boolean _passengerAsCarryBuffSource; // 0x168
	private BuffData[] _buffsToReleasedPassenger; // 0x170
	private Boolean _ignoreHost; // 0x178
	private Int32 m_maxCount; // 0x17c
	private readonly List`1 m_passengers; // 0x180
	private List`1 m_passengersMark; // 0x188
	private Int32 m_passengerEffectIndex; // 0x190
	private ObjectPtr`1 m_passengerEffect; // 0x198
	private Enemy m_host; // 0x1a8
	private Boolean m_searchPassengersStatus; // 0x1b0
	private static DelegateBridge __Hotfix0_get_category; // 0x0
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetTiming; // 0x18
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x20
	private static DelegateBridge __Hotfix0_get_allowNoTarget; // 0x28
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x30
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x40
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x48
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x50
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x58
	private static DelegateBridge __Hotfix0__UpdatePassengerEffect; // 0x60
	private static DelegateBridge __Hotfix0__FinishPassengerEffect; // 0x68
	private static DelegateBridge __Hotfix0__VerifyCurrentMode; // 0x70
	private static DelegateBridge __Hotfix0__SearchPassengers; // 0x78
	private static DelegateBridge __Hotfix0_DoSetData; // 0x80
	private static DelegateBridge __Hotfix0_DoAttach; // 0x88
	private static DelegateBridge __Hotfix0_OnDetached; // 0x90
	private static DelegateBridge __Hotfix0_ReleaseAllPassengers; // 0x98
	private static DelegateBridge __Hotfix0_ReleaseLastPassenger; // 0xa0
	private static DelegateBridge __Hotfix0_KillLastPassenger; // 0xa8
	private static DelegateBridge __Hotfix0_CheckPassengersExits; // 0xb0
	private static DelegateBridge __Hotfix0_MarkCurrentPassengers; // 0xb8
	private static DelegateBridge __Hotfix0_SetSearchPassengersStatus; // 0xc0
	private static DelegateBridge __Hotfix0__ReleasePassenger; // 0xc8
	private static DelegateBridge __Hotfix0__DoReleasePassengers; // 0xd0
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0xd8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0xe0
	private static DelegateBridge __Hotfix0_OnTick; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	public override Category category { get; }
	public override FP cooldown { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override SelectTargetTiming selectTargetTiming { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public override Boolean allowNoTarget { get; }

	// RVA: 0x1e48988 VA: 0x7594460988
	public override Category get_category() { }
	// RVA: 0x1e489f0 VA: 0x75944609f0
	public override FP get_cooldown() { }
	// RVA: 0x1e48a80 VA: 0x7594460a80
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e48ae8 VA: 0x7594460ae8
	public override SelectTargetTiming get_selectTargetTiming() { }
	// RVA: 0x1e48b4c VA: 0x7594460b4c
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e48bb0 VA: 0x7594460bb0
	public override Boolean get_allowNoTarget() { }
	// RVA: 0x1e48c14 VA: 0x7594460c14
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e48c7c VA: 0x7594460c7c
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e48ce0 VA: 0x7594460ce0
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e48d58 VA: 0x7594460d58
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e48dd8 VA: 0x7594460dd8
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e48e9c VA: 0x7594460e9c
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e48f60 VA: 0x7594460f60
	private Void _UpdatePassengerEffect() { }
	// RVA: 0x1e49114 VA: 0x7594461114
	private Void _FinishPassengerEffect() { }
	// RVA: 0x1e49254 VA: 0x7594461254
	private Boolean _VerifyCurrentMode(Int32 currentMode) { }
	// RVA: 0x1e4932c VA: 0x759446132c
	private Boolean _SearchPassengers() { }
	// RVA: 0x1e49eb8 VA: 0x7594461eb8
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e49f9c VA: 0x7594461f9c
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e4a188 VA: 0x7594462188
	protected override Void OnDetached() { }
	// RVA: 0x1e499a8 VA: 0x75944619a8
	public Void ReleaseAllPassengers(Boolean immediately, Nullable`1 releasePos, Boolean needMarked) { }
	// RVA: 0x1e4a4e0 VA: 0x75944624e0
	public Boolean ReleaseLastPassenger(Boolean immediately, Nullable`1 releasePos, Boolean needMarked) { }
	// RVA: 0x1e4a758 VA: 0x7594462758
	public Boolean KillLastPassenger() { }
	// RVA: 0x1e4a960 VA: 0x7594462960
	public Boolean CheckPassengersExits() { }
	// RVA: 0x1e4a9e8 VA: 0x75944629e8
	public Void MarkCurrentPassengers() { }
	// RVA: 0x1e4aaac VA: 0x7594462aac
	public Void SetSearchPassengersStatus(Boolean status) { }
	// RVA: 0x1e4a20c VA: 0x759446220c
	private Void _ReleasePassenger(Enemy enemy, Boolean immediately, Nullable`1 releasePos) { }
	// RVA: 0x1e4ab34 VA: 0x7594462b34
	private Void _DoReleasePassengers(Enemy enemy, Vector2 pos) { }
	// RVA: 0x1e4afac VA: 0x7594462fac
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e4b06c VA: 0x759446306c
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e4b220 VA: 0x7594463220
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e4b374 VA: 0x7594463374
	public Void .ctor() { }
	// RVA: 0x1e4b52c VA: 0x759446352c
	private SelectTargetTiming <>xLuaBaseProxy_get_selectTargetTiming() { }
	// RVA: 0x1e4b534 VA: 0x7594463534
	private Boolean <>xLuaBaseProxy_get_allowNoTarget() { }
	// RVA: 0x1e4b53c VA: 0x759446353c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e4b564 VA: 0x7594463564
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e4b56c VA: 0x759446356c
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e4b574 VA: 0x7594463574
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e4b57c VA: 0x759446357c
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1e4b584 VA: 0x7594463584
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```