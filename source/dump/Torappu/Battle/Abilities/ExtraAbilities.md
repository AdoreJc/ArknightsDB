# ExtraAbilities

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _useExtraAbilitySignal`


## Methods

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ExtraAbilities : Behaviour
{
	private Ability[] _abilities; // 0x20
	private Boolean _useExtraAbilitySignal; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnEvent; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1ecfa3c VA: 0x75944e7a3c
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ecfc08 VA: 0x75944e7c08
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ecfd54 VA: 0x75944e7d54
	public Void .ctor() { }
	// RVA: 0x1ecfdc4 VA: 0x75944e7dc4
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ecfdcc VA: 0x75944e7dcc
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```