# MultiFunnelTrait

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _initAtkScale`

- `Single _deltaAtkScale`

- `Single _maxAtkScale`

- `Int32 _maxStackCnt`

- `Boolean _normalAttackMultiFunnelsButSingleAbility`

- `Single m_initAtkScale`

- `Single m_deltaAtkScale`

- `Single m_maxAtkScale`

- `Int32 m_maxStackCnt`

- `Single m_maxAtkScaleMultiplier`

- `Ability m_mainFunnel`

- `AttackData m_mainFunnelData`

- `Ability m_normalFirstFunnel`

- `Ability m_modeFirstFunnel`


## Properties

- `Single maxAtkScale`


## Methods

- `Single get_maxAtkScale()`

- `Void SetFunnelActive(Ability)`

- `Boolean IsFunnelActive(Ability, Boolean)`

- `Single SetNormalAtkScale(Entity, Ability)`

- `Single SetFunnelAtkScale(Entity, Projectile)`

- `Void OnProjectileStop(Projectile)`

- `Void OnProjectileStop(Projectile, Single)`

- `Void UpdateMaxAtkScaleMultiplier(Single)`

- `IEnumerator DelayToRestore(Ability, Single)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiFunnelTrait : PassiveBuffAbility
{
	private Single _initAtkScale; // 0x110
	private Single _deltaAtkScale; // 0x114
	private Single _maxAtkScale; // 0x118
	private Int32 _maxStackCnt; // 0x11c
	private Boolean _normalAttackMultiFunnelsButSingleAbility; // 0x120
	private Single m_initAtkScale; // 0x124
	private Single m_deltaAtkScale; // 0x128
	private Single m_maxAtkScale; // 0x12c
	private Int32 m_maxStackCnt; // 0x130
	private Single m_maxAtkScaleMultiplier; // 0x134
	private Ability m_mainFunnel; // 0x138
	private AttackData m_mainFunnelData; // 0x140
	private Ability m_normalFirstFunnel; // 0x160
	private Ability m_modeFirstFunnel; // 0x168
	private readonly HashSet`1 m_activeFunnels; // 0x170
	private readonly HashSet`1 m_toRemoveFromActiveFunnels; // 0x178
	private readonly Dictionary`2 m_funnels; // 0x180
	private static readonly HashSet`1 s_activeFunnelsToRemove; // 0x0
	private static DelegateBridge __Hotfix0_get_maxAtkScale; // 0x8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x10
	private static DelegateBridge __Hotfix0_SetFunnelActive; // 0x18
	private static DelegateBridge __Hotfix0_IsFunnelActive; // 0x20
	private static DelegateBridge __Hotfix0_SetNormalAtkScale; // 0x28
	private static DelegateBridge __Hotfix0_SetFunnelAtkScale; // 0x30
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x38
	private static DelegateBridge __Hotfix1_OnProjectileStop; // 0x40
	private static DelegateBridge __Hotfix0_UpdateMaxAtkScaleMultiplier; // 0x48
	private static DelegateBridge __Hotfix0_DelayToRestore; // 0x50
	private static DelegateBridge __Hotfix0_Reset; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Single maxAtkScale { get; }

	// RVA: 0x1e7c4d8 VA: 0x75944944d8
	private Single get_maxAtkScale() { }
	// RVA: 0x1e7c558 VA: 0x7594494558
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e7c750 VA: 0x7594494750
	public Void SetFunnelActive(Ability atkAbility) { }
	// RVA: 0x1e7c800 VA: 0x7594494800
	public Boolean IsFunnelActive(Ability ability, Boolean ignoreRestoring) { }
	// RVA: 0x1e7cc84 VA: 0x7594494c84
	public Single SetNormalAtkScale(Entity target, Ability ability) { }
	// RVA: 0x1e7cedc VA: 0x7594494edc
	public Single SetFunnelAtkScale(Entity target, Projectile projectile) { }
	// RVA: 0x1e7d474 VA: 0x7594495474
	public Void OnProjectileStop(Projectile projectile) { }
	// RVA: 0x1e7d614 VA: 0x7594495614
	public Void OnProjectileStop(Projectile projectile, Single delayToRestore) { }
	// RVA: 0x1e7d8a4 VA: 0x75944958a4
	public Void UpdateMaxAtkScaleMultiplier(Single finalScale) { }
	// RVA: 0x1e7d7ac VA: 0x75944957ac
	private IEnumerator DelayToRestore(Ability ability, Single delayToRestore) { }
	// RVA: 0x1e7d9c0 VA: 0x75944959c0
	protected override Void Reset() { }
	// RVA: 0x1e7daec VA: 0x7594495aec
	public Void .ctor() { }
	// RVA: 0x1e7dc44 VA: 0x7594495c44
	private static Void .cctor() { }
	// RVA: 0x1e7dcdc VA: 0x7594495cdc
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e7dd04 VA: 0x7594495d04
	private Void <>xLuaBaseProxy_Reset() { }
}
```