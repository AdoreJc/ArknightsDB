# UnitHudPluginManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _pluginName`

- `Boolean _characterClassOnly`

- `Boolean _enemyClassOnly`


## Methods

- `Void _OnUnitBorn(Object)`

- `Void _OnUnitFinish(Object)`

- `Boolean CheckUnitValid(Unit)`

- `HudPlugin LoadPlugin(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UnitHudPluginManager : EnvManager
{
	private String _pluginName; // 0x28
	private Boolean _characterClassOnly; // 0x30
	private Boolean _enemyClassOnly; // 0x31
	private ListDict`2 m_plugin; // 0x38
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x8
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x10
	private static DelegateBridge __Hotfix0_CheckUnitValid; // 0x18
	private static DelegateBridge __Hotfix0_LoadPlugin; // 0x20
	private static DelegateBridge __Hotfix0_CreatePlugin; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x406940c VA: 0x759668140c
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4069618 VA: 0x7596681618
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x4069ab8 VA: 0x7596681ab8
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x4069814 VA: 0x7596681814
	private Boolean CheckUnitValid(Unit unit) { }
	// RVA: 0x4069d48 VA: 0x7596681d48
	protected HudPlugin LoadPlugin(String pluginName) { }
	// RVA: 0x4069e64 VA: 0x7596681e64
	protected virtual HudPlugin CreatePlugin(Unit unit) { }
	// RVA: 0x406a014 VA: 0x7596682014
	public Void .ctor() { }
	// RVA: 0x406a0d8 VA: 0x75966820d8
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
}
```