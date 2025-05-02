# EmitGameEventManager

**Namespace:** `Torappu.Battle`


## Methods

- `Void _OnGameStart(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EmitGameEventManager : EnvManager
{
	private List`1 _eventBindings; // 0x28
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0__OnGameStart; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4048b04 VA: 0x7596660b04
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4048c70 VA: 0x7596660c70
	private Void _OnGameStart(Object arg) { }
	// RVA: 0x4048d98 VA: 0x7596660d98
	public Void .ctor() { }
	// RVA: 0x4048e08 VA: 0x7596660e08
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
}
```