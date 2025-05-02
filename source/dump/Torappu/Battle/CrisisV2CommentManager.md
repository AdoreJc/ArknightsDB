# CrisisV2CommentManager

**Namespace:** `Torappu.Battle`


## Methods

- `Void _OnUnitBorn(Object)`

- `Void _OnEnemyReachedExit(Object)`

- `Void _OnGameOver(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CrisisV2CommentManager : EnvManager
{
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x8
	private static DelegateBridge __Hotfix0__OnEnemyReachedExit; // 0x10
	private static DelegateBridge __Hotfix0__OnGameOver; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4047a98 VA: 0x759665fa98
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4047d38 VA: 0x759665fd38
	private Void _OnUnitBorn(Object args) { }
	// RVA: 0x4048060 VA: 0x7596660060
	private Void _OnEnemyReachedExit(Object args) { }
	// RVA: 0x4048388 VA: 0x7596660388
	private Void _OnGameOver(Object args) { }
	// RVA: 0x404851c VA: 0x759666051c
	public Void .ctor() { }
	// RVA: 0x404858c VA: 0x759666058c
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
}
```