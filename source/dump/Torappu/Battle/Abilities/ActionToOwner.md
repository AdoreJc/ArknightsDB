# ActionToOwner

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Event _runActionOnEvent`

- `ActionArray _actions`

- `Boolean _onlyRunOnce`

- `Boolean m_run`


## Methods

- `Void GatherActionNodes(List`1)`

- `Void _RunActions()`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ActionToOwner : Behaviour, IActionNodeSource
{
	private Event _runActionOnEvent; // 0x20
	private ActionArray _actions; // 0x28
	private Boolean _onlyRunOnce; // 0x30
	private Boolean m_run; // 0x31
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x0
	private static DelegateBridge __Hotfix0_OnEvent; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge __Hotfix0__RunActions; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1eb80a8 VA: 0x75944d00a8
	public override Void OnCastStart() { }
	// RVA: 0x1eb8110 VA: 0x75944d0110
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1eb84a0 VA: 0x75944d04a0
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1eb81b4 VA: 0x75944d01b4
	private Void _RunActions() { }
	// RVA: 0x1eb8534 VA: 0x75944d0534
	public Void .ctor() { }
	// RVA: 0x1eb85ec VA: 0x75944d05ec
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1eb85f4 VA: 0x75944d05f4
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```