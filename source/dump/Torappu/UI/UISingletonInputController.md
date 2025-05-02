# UISingletonInputController

**Namespace:** `Torappu.UI`


## Fields

- `EventSystem _eventSystem`

- `EnableStateWithKey m_disableEventSystem`


## Methods

- `Void DisableEventSystem(Boolean, String)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class UISingletonInputController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	public const String DEFAULT_EVENT_SYSTEM_KEY; // 0x0
	private EventSystem _eventSystem; // 0x18
	private EnableStateWithKey m_disableEventSystem; // 0x20
	private static __XLua_Gen_Delegate116 __Hotfix0_DisableEventSystem; // 0x0
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x8


	// RVA: 0x678c484 VA: 0x7598da4484
	public Void DisableEventSystem(Boolean disable, String key) { }
	// RVA: 0x678c590 VA: 0x7598da4590
	public Void .ctor() { }
}
```