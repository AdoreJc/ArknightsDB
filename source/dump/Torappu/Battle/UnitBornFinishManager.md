# UnitBornFinishManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _bornEvent`

- `String _finishEvent`


## Methods

- `Void _OnUnitBorn(Object)`

- `Void _OnUnitFinish(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UnitBornFinishManager : EnvManager
{
	private String _bornEvent; // 0x28
	private String _finishEvent; // 0x30
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x8
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4068f28 VA: 0x7596680f28
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4069134 VA: 0x7596681134
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x4069264 VA: 0x7596681264
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x4069394 VA: 0x7596681394
	public Void .ctor() { }
	// RVA: 0x4069404 VA: 0x7596681404
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
}
```