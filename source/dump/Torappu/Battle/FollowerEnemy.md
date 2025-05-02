# FollowerEnemy

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean <>xLuaBaseProxy_get_disableUIUnitHud()`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Vector2 <>xLuaBaseProxy__MoveByRoute(Single, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FollowerEnemy : Enemy
{
	private ObjectPtr`1 m_hostEnemy; // 0x4b8
	private static DelegateBridge __Hotfix0_get_disableUIUnitHud; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_OnBorn; // 0x10
	private static DelegateBridge __Hotfix0__MoveByRoute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Boolean disableUIUnitHud { get; }

	// RVA: 0x1c1b748 VA: 0x7594233748
	public override Boolean get_disableUIUnitHud() { }
	// RVA: 0x1c1b7b0 VA: 0x75942337b0
	protected override Void OnReset() { }
	// RVA: 0x1c1b854 VA: 0x7594233854
	protected override Void OnBorn() { }
	// RVA: 0x1c1b8c0 VA: 0x75942338c0
	protected override Vector2 _MoveByRoute(Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1c1bc74 VA: 0x7594233c74
	public Void .ctor() { }
	// RVA: 0x1c1bd08 VA: 0x7594233d08
	private Boolean <>xLuaBaseProxy_get_disableUIUnitHud() { }
	// RVA: 0x1c1bd10 VA: 0x7594233d10
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x1c1bd18 VA: 0x7594233d18
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x1c1bd20 VA: 0x7594233d20
	private Vector2 <>xLuaBaseProxy__MoveByRoute(Single P0, out Boolean P1) { }
}
```