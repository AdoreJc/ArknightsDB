# BurstAttackGroup

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `FinishCallbackDelegate m_onBurstAttackCasted`

- `AbilityConfigs _burstAttack`


## Properties

- `Boolean isDuringBurstAttack`


## Methods

- `Boolean get_isDuringBurstAttack()`

- `Void _OnBurstAbilityFinished(Ability, FinishReason, Boolean)`

- `Void OnBeforeBurstAttack(FinishCallbackDelegate)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_ResetCooldown(Boolean)`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BurstAttackGroup : AbilitySelectableGroup
{
	private FinishCallbackDelegate m_onBurstAttackCasted; // 0x140
	private AbilityConfigs _burstAttack; // 0x148
	private static DelegateBridge __Hotfix0_get_isDuringBurstAttack; // 0x0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x8
	private static DelegateBridge __Hotfix0_ResetCooldown; // 0x10
	private static DelegateBridge __Hotfix0_CastDirectly; // 0x18
	private static DelegateBridge __Hotfix0__OnBurstAbilityFinished; // 0x20
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x28
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x30
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x38
	private static DelegateBridge __Hotfix0_DoAttach; // 0x40
	private static DelegateBridge __Hotfix0_DoDetach; // 0x48
	private static DelegateBridge __Hotfix0_OnBeforeBurstAttack; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean isDuringBurstAttack { get; }

	// RVA: 0x1e6ea70 VA: 0x7594486a70
	public Boolean get_isDuringBurstAttack() { }
	// RVA: 0x1e6eae0 VA: 0x7594486ae0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e6ebf4 VA: 0x7594486bf4
	public override Void ResetCooldown(Boolean waitFirstPeriod) { }
	// RVA: 0x1e6ecb8 VA: 0x7594486cb8
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e6ee58 VA: 0x7594486e58
	protected Void _OnBurstAbilityFinished(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1e6ef04 VA: 0x7594486f04
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e6f0b0 VA: 0x75944870b0
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e6f178 VA: 0x7594487178
	public override Void PreloadSpecialAudioSignals(String abilityId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1e6f2e8 VA: 0x75944872e8
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e6f39c VA: 0x759448739c
	protected override Void DoDetach() { }
	// RVA: 0x1e6f434 VA: 0x7594487434
	public Void OnBeforeBurstAttack(FinishCallbackDelegate finishCb) { }
	// RVA: 0x1e6f4e4 VA: 0x75944874e4
	public Void .ctor() { }
	// RVA: 0x1e6f554 VA: 0x7594487554
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e6f57c VA: 0x759448757c
	private Void <>xLuaBaseProxy_ResetCooldown(Boolean P0) { }
	// RVA: 0x1e6f588 VA: 0x7594487588
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1e6f594 VA: 0x7594487594
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e6f5a0 VA: 0x75944875a0
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e6f5a8 VA: 0x75944875a8
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
	// RVA: 0x1e6f5b0 VA: 0x75944875b0
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e6f5b8 VA: 0x75944875b8
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```