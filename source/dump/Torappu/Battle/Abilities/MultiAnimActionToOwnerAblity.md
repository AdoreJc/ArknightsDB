# MultiAnimActionToOwnerAblity

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _additionalTimes`

- `Single _triggerDelta`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta()`

- `Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiAnimActionToOwnerAblity : AnimatedActionToTargetAbility
{
	private Int32 _additionalTimes; // 0x1d0
	private Single _triggerDelta; // 0x1d4
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnWaitForTriggerDelta; // 0x8
	private static DelegateBridge __Hotfix0_CheckAnotherSpell; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1e02df4 VA: 0x759441adf4
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e02f2c VA: 0x759441af2c
	protected override IEnumerator OnWaitForTriggerDelta() { }
	// RVA: 0x1e03000 VA: 0x759441b000
	protected override Boolean CheckAnotherSpell(Int32 spellCnt) { }
	// RVA: 0x1e03084 VA: 0x759441b084
	public Void .ctor() { }
	// RVA: 0x1e030f0 VA: 0x759441b0f0
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e03118 VA: 0x759441b118
	private IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta() { }
	// RVA: 0x1e03120 VA: 0x759441b120
	private Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32 P0) { }
}
```