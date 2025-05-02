# CooledChargeRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _chargeCoolDown`

- `Single m_chargeCoolDown`

- `Single m_remainingTime`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_AddChargeTimes()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Boolean <>xLuaBaseProxy_CanCharge()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class CooledChargeRangedAttack : ChargeRangedAttack
{
	private Single _chargeCoolDown; // 0x280
	private Single m_chargeCoolDown; // 0x284
	private Single m_remainingTime; // 0x288
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_AddChargeTimes; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_CanCharge; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e0b348 VA: 0x7594423348
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e0b450 VA: 0x7594423450
	public override Void AddChargeTimes() { }
	// RVA: 0x1e0b4c8 VA: 0x75944234c8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e0b598 VA: 0x7594423598
	public override Boolean CanCharge() { }
	// RVA: 0x1e0b63c VA: 0x759442363c
	public Void .ctor() { }
	// RVA: 0x1e0b6ac VA: 0x75944236ac
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e0b6d4 VA: 0x75944236d4
	private Void <>xLuaBaseProxy_AddChargeTimes() { }
	// RVA: 0x1e0b6dc VA: 0x75944236dc
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1e0b6e4 VA: 0x75944236e4
	private Boolean <>xLuaBaseProxy_CanCharge() { }
}
```