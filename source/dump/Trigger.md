# Trigger

**Namespace:** ` `


## Fields

- `String m_consumableSignal`

- `CommandType m_cmdType`


## Methods

- `Void RegisterExtraGameObject(String, GameObject)`

- `Void _TriggerSignalIfPermitted()`

- `Boolean _CheckIfSignalEnabled()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Trigger : IHotfixable
{
	private Dictionary`2 m_consumableRequires; // 0x10
	private String m_consumableSignal; // 0x18
	private CommandType m_cmdType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RegisterExtraGameObject; // 0x8
	private static DelegateBridge __Hotfix0__TriggerSignalIfPermitted; // 0x10
	private static DelegateBridge __Hotfix0__CheckIfSignalEnabled; // 0x18


	// RVA: 0x3e5a660 VA: 0x7596472660
	private Void .ctor(Builder builder) { }
	// RVA: 0x3e5a9a4 VA: 0x75964729a4
	public Void RegisterExtraGameObject(String id, GameObject target) { }
	// RVA: 0x3e5a888 VA: 0x7596472888
	private Void _TriggerSignalIfPermitted() { }
	// RVA: 0x3e5ab9c VA: 0x7596472b9c
	private Boolean _CheckIfSignalEnabled() { }
}
```