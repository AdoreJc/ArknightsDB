# ToggleablePassiveAbilityGroup

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnToggleChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ToggleablePassiveAbilityGroup : ToggleablePassiveBuffAbility
{
	protected Ability[] _abilities; // 0x130
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnToggleChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e60d54 VA: 0x7594478d54
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e60ef0 VA: 0x7594478ef0
	protected override Void OnToggleChanged(Boolean isToggled) { }
	// RVA: 0x1e61008 VA: 0x7594479008
	public Void .ctor() { }
	// RVA: 0x1e610b0 VA: 0x75944790b0
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e610d4 VA: 0x75944790d4
	private Void <>xLuaBaseProxy_OnToggleChanged(Boolean P0) { }
}
```