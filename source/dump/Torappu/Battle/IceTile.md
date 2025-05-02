# IceTile

**Namespace:** `Torappu.Battle`


## Methods

- `Void _CheckFrozen(Object)`

- `Void _StopCheck(Enemy)`

- `Void <>xLuaBaseProxy_OnEnemyEnter(Enemy)`

- `Void <>xLuaBaseProxy_OnEnemyLeave(Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class IceTile : BuffTile
{
	private const Single FRICTION_FACTOR; // 0x0
	private static DelegateBridge __Hotfix0__CheckFrozen; // 0x0
	private static DelegateBridge __Hotfix0__StopCheck; // 0x8
	private static DelegateBridge __Hotfix0_OnEnemyEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnEnemyLeave; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x4092598 VA: 0x75966aa598
	private Void _CheckFrozen(Object rawTarget) { }
	// RVA: 0x4092700 VA: 0x75966aa700
	private Void _StopCheck(Enemy enemy) { }
	// RVA: 0x4092810 VA: 0x75966aa810
	protected override Void OnEnemyEnter(Enemy enemy) { }
	// RVA: 0x409298c VA: 0x75966aa98c
	protected override Void OnEnemyLeave(Enemy enemy) { }
	// RVA: 0x4092a18 VA: 0x75966aaa18
	public Void .ctor() { }
	// RVA: 0x4092aa8 VA: 0x75966aaaa8
	private Void <>xLuaBaseProxy_OnEnemyEnter(Enemy P0) { }
	// RVA: 0x4092aac VA: 0x75966aaaac
	private Void <>xLuaBaseProxy_OnEnemyLeave(Enemy P0) { }
}
```