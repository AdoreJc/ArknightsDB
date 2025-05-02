# ToggleablePassiveWrapperAbility

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnToggleChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ToggleablePassiveWrapperAbility : ToggleablePassiveBuffAbility
{
	private Ability[] _passiveAbilities; // 0x130
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnToggleChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e61cfc VA: 0x7594479cfc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e61e20 VA: 0x7594479e20
	protected override Void OnToggleChanged(Boolean isToggled) { }
	// RVA: 0x1e61f8c VA: 0x7594479f8c
	public Void .ctor() { }
	// RVA: 0x1e61ff8 VA: 0x7594479ff8
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e6201c VA: 0x759447a01c
	private Void <>xLuaBaseProxy_OnToggleChanged(Boolean P0) { }
}
```