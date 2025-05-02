# LegionModeBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void _OnRallyPointReborn(Object)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_UpdateBlackboard()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class LegionModeBuffAbility : LegionModeAbility
{
	private List`1 _passiveBuffPairs; // 0x130
	private List`1 m_usedPassiveBuffPairs; // 0x138
	private static DelegateBridge __Hotfix0_get_passiveBuffPairs; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge __Hotfix0_DoDetach; // 0x10
	private static DelegateBridge __Hotfix0__OnRallyPointReborn; // 0x18
	private static DelegateBridge __Hotfix0_UpdateBlackboard; // 0x20
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x28
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private List`1 passiveBuffPairs { get; }

	// RVA: 0x1e77dd4 VA: 0x759448fdd4
	private List`1 get_passiveBuffPairs() { }
	// RVA: 0x1e780a8 VA: 0x75944900a8
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e781e8 VA: 0x75944901e8
	protected override Void DoDetach() { }
	// RVA: 0x1e782fc VA: 0x75944902fc
	private Void _OnRallyPointReborn(Object arg) { }
	// RVA: 0x1e78430 VA: 0x7594490430
	protected override Void UpdateBlackboard() { }
	// RVA: 0x1e788fc VA: 0x75944908fc
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e78c9c VA: 0x7594490c9c
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e78f48 VA: 0x7594490f48
	public Void .ctor() { }
	// RVA: 0x1e79038 VA: 0x7594491038
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e79040 VA: 0x7594491040
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e79048 VA: 0x7594491048
	private Void <>xLuaBaseProxy_UpdateBlackboard() { }
	// RVA: 0x1e7904c VA: 0x759449104c
	private IList`1 <>xLuaBaseProxy_GetPassiveBuffs() { }
	// RVA: 0x1e79054 VA: 0x7594491054
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```