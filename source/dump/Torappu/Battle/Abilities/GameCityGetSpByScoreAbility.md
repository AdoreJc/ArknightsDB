# GameCityGetSpByScoreAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _ignoreReduce`

- `Boolean _forceFlag`

- `Single _scoreScale`

- `GameCityGameMode m_gameMode`

- `FP m_scoreScale`

- `FP m_tempScore`


## Methods

- `Void _GetSpWithScore(Object)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class GameCityGetSpByScoreAbility : AbilityStandard
{
	private Boolean _ignoreReduce; // 0x107
	private Boolean _forceFlag; // 0x108
	private Single _scoreScale; // 0x10c
	private GameCityGameMode m_gameMode; // 0x110
	private FP m_scoreScale; // 0x118
	protected FP m_tempScore; // 0x120
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x18
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x20
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x28
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x30
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x40
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x48
	private static DelegateBridge __Hotfix0_DoSetData; // 0x50
	private static DelegateBridge __Hotfix0_DoAttach; // 0x58
	private static DelegateBridge __Hotfix0_DoDetach; // 0x60
	private static DelegateBridge __Hotfix0__GetSpWithScore; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e75d38 VA: 0x759448dd38
	public override FP get_cooldown() { }
	// RVA: 0x1e75dc8 VA: 0x759448ddc8
	public override Category get_category() { }
	// RVA: 0x1e75e30 VA: 0x759448de30
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e75e94 VA: 0x759448de94
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e75ef8 VA: 0x759448def8
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e75f70 VA: 0x759448df70
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e75ff0 VA: 0x759448dff0
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e76054 VA: 0x759448e054
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e760b8 VA: 0x759448e0b8
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e7617c VA: 0x759448e17c
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e76240 VA: 0x759448e240
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e7642c VA: 0x759448e42c
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e76558 VA: 0x759448e558
	protected override Void DoDetach() { }
	// RVA: 0x1e7666c VA: 0x759448e66c
	private Void _GetSpWithScore(Object obj) { }
	// RVA: 0x1e76894 VA: 0x759448e894
	public Void .ctor() { }
	// RVA: 0x1e7695c VA: 0x759448e95c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e76984 VA: 0x759448e984
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e7698c VA: 0x759448e98c
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```