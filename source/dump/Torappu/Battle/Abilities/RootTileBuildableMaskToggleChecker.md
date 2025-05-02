# RootTileBuildableMaskToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TileCondition _condition`


## Methods

- `Boolean _CheckCondition()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RootTileBuildableMaskToggleChecker : Checker
{
	private TileCondition _condition; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OnDetached; // 0x8
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x10
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1e5f580 VA: 0x7594477580
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5f5f8 VA: 0x75944775f8
	public override Void OnDetached() { }
	// RVA: 0x1e5f664 VA: 0x7594477664
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5f6cc VA: 0x75944776cc
	private Boolean _CheckCondition() { }
	// RVA: 0x1e5f800 VA: 0x7594477800
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5f894 VA: 0x7594477894
	public Void .ctor() { }
	// RVA: 0x1e5f900 VA: 0x7594477900
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e5f904 VA: 0x7594477904
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```