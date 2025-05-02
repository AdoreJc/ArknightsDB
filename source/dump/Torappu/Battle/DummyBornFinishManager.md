# DummyBornFinishManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _bornEvent`

- `String _finishEvent`


## Methods

- `Void _OnDummyLocateTile(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DummyBornFinishManager : EnvManager
{
	private String _bornEvent; // 0x28
	private String _finishEvent; // 0x30
	private Dictionary`2 m_dummyTileMap; // 0x38
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0__OnDummyLocateTile; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4048594 VA: 0x7596660594
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4048700 VA: 0x7596660700
	private Void _OnDummyLocateTile(Object arg) { }
	// RVA: 0x4048a38 VA: 0x7596660a38
	public Void .ctor() { }
	// RVA: 0x4048afc VA: 0x7596660afc
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
}
```