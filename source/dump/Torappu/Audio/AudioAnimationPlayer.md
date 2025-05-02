# AudioAnimationPlayer

**Namespace:** `Torappu.Audio`


## Methods

- `Boolean _TryGetCondition(String)`

- `Void EventPlayUI(String)`

- `Void EventPlayBattle(String)`

- `Void EventPlaySystem(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioAnimationPlayer : MonoBehaviour, IHotfixable
{
	private List`1 _providerConfigs; // 0x18
	private static DelegateBridge __Hotfix0__TryGetCondition; // 0x0
	private static DelegateBridge __Hotfix0_EventPlayUI; // 0x8
	private static DelegateBridge __Hotfix0_EventPlayBattle; // 0x10
	private static DelegateBridge __Hotfix0_EventPlaySystem; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3eb2cfc VA: 0x75964cacfc
	private Boolean _TryGetCondition(String signal) { }
	// RVA: 0x3eb2f0c VA: 0x75964caf0c
	public Void EventPlayUI(String signal) { }
	// RVA: 0x3eb2fd4 VA: 0x75964cafd4
	public Void EventPlayBattle(String signal) { }
	// RVA: 0x3eb309c VA: 0x75964cb09c
	public Void EventPlaySystem(String signal) { }
	// RVA: 0x3eb3164 VA: 0x75964cb164
	public Void .ctor() { }
}
```