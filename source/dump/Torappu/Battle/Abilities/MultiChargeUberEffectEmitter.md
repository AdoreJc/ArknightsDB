# MultiChargeUberEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `IMultiChargeUberEffectEmitterAbility m_chargeAbility`

- `Int32 m_chargeIndex`


## Properties

- `Int32 chargeIndex`


## Methods

- `Int32 get_chargeIndex()`

- `Boolean _CheckChargeActionValid()`

- `Boolean _CheckChargeIndexValid()`

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiChargeUberEffectEmitter : UberEffectEmitter
{
	private ChargeEffectGroup[] _chargeEffectGroups; // 0x58
	private ChargeCastGroup[] _chargeCastGroups; // 0x60
	private IMultiChargeUberEffectEmitterAbility m_chargeAbility; // 0x68
	private Int32 m_chargeIndex; // 0x70
	private static DelegateBridge __Hotfix0_get_chargeEffectGroups; // 0x0
	private static DelegateBridge __Hotfix0_get_chargeIndex; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_GetChargeIndex; // 0x18
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x20
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x28
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x30
	private static DelegateBridge __Hotfix0_OnEvent; // 0x38
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x40
	private static DelegateBridge __Hotfix0_IsInChargeAction; // 0x48
	private static DelegateBridge __Hotfix0__CheckChargeActionValid; // 0x50
	private static DelegateBridge __Hotfix0__CheckChargeIndexValid; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	protected ChargeEffectGroup[] chargeEffectGroups { get; }
	protected Int32 chargeIndex { get; }

	// RVA: 0x1ec5ec8 VA: 0x75944ddec8
	protected ChargeEffectGroup[] get_chargeEffectGroups() { }
	// RVA: 0x1ec5f30 VA: 0x75944ddf30
	protected Int32 get_chargeIndex() { }
	// RVA: 0x1ec5f98 VA: 0x75944ddf98
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ec6404 VA: 0x75944de404
	protected virtual Int32 GetChargeIndex() { }
	// RVA: 0x1ec64dc VA: 0x75944de4dc
	public override Void OnCastStart() { }
	// RVA: 0x1ec6754 VA: 0x75944de754
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ec69cc VA: 0x75944de9cc
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ec6d4c VA: 0x75944ded4c
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec7398 VA: 0x75944df398
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec7664 VA: 0x75944df664
	protected virtual Boolean IsInChargeAction() { }
	// RVA: 0x1ec7214 VA: 0x75944df214
	private Boolean _CheckChargeActionValid() { }
	// RVA: 0x1ec7064 VA: 0x75944df064
	private Boolean _CheckChargeIndexValid() { }
	// RVA: 0x1ec7748 VA: 0x75944df748
	public Void .ctor() { }
	// RVA: 0x1ec7940 VA: 0x75944df940
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ec7944 VA: 0x75944df944
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ec7948 VA: 0x75944df948
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ec794c VA: 0x75944df94c
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
	// RVA: 0x1ec7950 VA: 0x75944df950
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ec7954 VA: 0x75944df954
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```