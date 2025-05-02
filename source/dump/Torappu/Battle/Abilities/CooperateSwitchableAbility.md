# CooperateSwitchableAbility

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void _OnCooperateBuffLevelChanged(Object)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class CooperateSwitchableAbility : PassiveBuffAbility
{
	protected Ability[] _abilities; // 0x110
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_DoDetach; // 0x8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x10
	private static DelegateBridge __Hotfix0__OnCooperateBuffLevelChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e6fad4 VA: 0x7594487ad4
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e6fec0 VA: 0x7594487ec0
	protected override Void DoDetach() { }
	// RVA: 0x1e70030 VA: 0x7594488030
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e6fc38 VA: 0x7594487c38
	private Void _OnCooperateBuffLevelChanged(Object arg) { }
	// RVA: 0x1e701d0 VA: 0x75944881d0
	public Void .ctor() { }
	// RVA: 0x1e7027c VA: 0x759448827c
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e70284 VA: 0x7594488284
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e7028c VA: 0x759448828c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
}
```