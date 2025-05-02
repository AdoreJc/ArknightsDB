# ActiveBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _waitForCasting`

- `Boolean _updateLifetimeWhenSpellStart`

- `Single _preDelay`

- `Single _escapeTime`

- `Boolean _checkBuffEarlyFinish`

- `Boolean _ignoreInfiniteBuffCooldown`

- `FP m_lifeTime`


## Methods

- `Void SetLifeTime(BuffData[])`

- `Boolean DoOnSpellStart(BuffData[])`

- `Boolean _CheckNotAllFinished()`

- `IEnumerator <>n__0()`

- `IEnumerator <>n__1()`

- `FP <>xLuaBaseProxy_get_escapeTime()`

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `Boolean <>xLuaBaseProxy_get_allowNoTarget()`

- `Void <>xLuaBaseProxy_StopAffect()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`

- `Boolean <>xLuaBaseProxy_OnSpellStart()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ActiveBuffAbility : EasyToStartAbility
{
	private BuffData[] _buffs; // 0x128
	private Boolean _waitForCasting; // 0x130
	private Boolean _updateLifetimeWhenSpellStart; // 0x131
	private Single _preDelay; // 0x134
	private Single _escapeTime; // 0x138
	private Boolean _checkBuffEarlyFinish; // 0x13c
	private BuffData[] _passiveBuffs; // 0x140
	private Boolean _ignoreInfiniteBuffCooldown; // 0x148
	private FP m_lifeTime; // 0x150
	private List`1 m_buffInsts; // 0x158
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x0
	private static DelegateBridge __Hotfix0_get_escapeTime; // 0x8
	private static DelegateBridge __Hotfix0_get_category; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x18
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x28
	private static DelegateBridge __Hotfix0_get_allowNoTarget; // 0x30
	private static DelegateBridge __Hotfix0_get_preDelay; // 0x38
	private static DelegateBridge __Hotfix0_StopAffect; // 0x40
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x48
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x50
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x58
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x60
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x68
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x70
	private static DelegateBridge __Hotfix0_DoSetData; // 0x78
	private static DelegateBridge __Hotfix0_Reset; // 0x80
	private static DelegateBridge __Hotfix0_GetDuration; // 0x88
	private static DelegateBridge __Hotfix0_OnSpellStart; // 0x90
	private static DelegateBridge __Hotfix0_SetLifeTime; // 0x98
	private static DelegateBridge __Hotfix0_DoOnSpellStart; // 0xa0
	private static DelegateBridge __Hotfix0_OnTick; // 0xa8
	private static DelegateBridge __Hotfix0__CheckNotAllFinished; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public override FP cooldown { get; }
	public override FP escapeTime { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override Boolean isAffecting { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public override Boolean allowNoTarget { get; }
	public override FP preDelay { get; }

	// RVA: 0x1e1c610 VA: 0x7594434610
	public override FP get_cooldown() { }
	// RVA: 0x1e1c678 VA: 0x7594434678
	public override FP get_escapeTime() { }
	// RVA: 0x1e1c718 VA: 0x7594434718
	public override Category get_category() { }
	// RVA: 0x1e1c780 VA: 0x7594434780
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e1c7e8 VA: 0x75944347e8
	public override Boolean get_isAffecting() { }
	// RVA: 0x1e1c884 VA: 0x7594434884
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e1c8e8 VA: 0x75944348e8
	public override Boolean get_allowNoTarget() { }
	// RVA: 0x1e1c950 VA: 0x7594434950
	public override FP get_preDelay() { }
	// RVA: 0x1e1c9f0 VA: 0x75944349f0
	public override Void StopAffect() { }
	// RVA: 0x1e1caf4 VA: 0x7594434af4
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e1cb6c VA: 0x7594434b6c
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e1cbec VA: 0x7594434bec
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e1cc54 VA: 0x7594434c54
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e1ccbc VA: 0x7594434cbc
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e1cd90 VA: 0x7594434d90
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e1ce64 VA: 0x7594434e64
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e1d138 VA: 0x7594435138
	protected override Void Reset() { }
	// RVA: 0x1e1d1ec VA: 0x75944351ec
	protected override FP GetDuration() { }
	// RVA: 0x1e1d260 VA: 0x7594435260
	protected override Boolean OnSpellStart() { }
	// RVA: 0x1e1cf14 VA: 0x7594434f14
	protected Void SetLifeTime(BuffData[] buffs) { }
	// RVA: 0x1e1d2e0 VA: 0x75944352e0
	protected Boolean DoOnSpellStart(BuffData[] buffs) { }
	// RVA: 0x1e1d568 VA: 0x7594435568
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e1d650 VA: 0x7594435650
	private Boolean _CheckNotAllFinished() { }
	// RVA: 0x1e1d754 VA: 0x7594435754
	public Void .ctor() { }
	// RVA: 0x1e1d8a4 VA: 0x75944358a4
	private IEnumerator <>n__0() { }
	// RVA: 0x1e1d8ac VA: 0x75944358ac
	private IEnumerator <>n__1() { }
	// RVA: 0x1e1d8b4 VA: 0x75944358b4
	private FP <>xLuaBaseProxy_get_escapeTime() { }
	// RVA: 0x1e1d8bc VA: 0x75944358bc
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x1e1d8c4 VA: 0x75944358c4
	private Boolean <>xLuaBaseProxy_get_allowNoTarget() { }
	// RVA: 0x1e1d8cc VA: 0x75944358cc
	private Void <>xLuaBaseProxy_StopAffect() { }
	// RVA: 0x1e1d8d4 VA: 0x75944358d4
	private IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay() { }
	// RVA: 0x1e1d8dc VA: 0x75944358dc
	private IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay() { }
	// RVA: 0x1e1d8e4 VA: 0x75944358e4
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e1d90c VA: 0x759443590c
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e1d914 VA: 0x7594435914
	private Boolean <>xLuaBaseProxy_OnSpellStart() { }
	// RVA: 0x1e1d91c VA: 0x759443591c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```