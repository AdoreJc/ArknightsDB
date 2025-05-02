# TickGroup

**Namespace:** `Torappu.TimeModule`


## Methods

- `TickFunction _AddTickFunction(ITickOwner, Action`1, String)`

- `Void _Release()`

- `Void _Tick(Single, Double)`

- `Void _ChangeGlobalTimeScale(Single)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.TimeModule
public class TickGroup
{
	protected List`1 m_tickFuncs; // 0x10
	protected List`1 m_tickBuffer; // 0x18
	protected readonly List`1 m_pendingAddFuncs; // 0x20


	// RVA: 0x678dc0c VA: 0x7598da5c0c
	private TickFunction _AddTickFunction(ITickOwner owner, Action`1 func, String name) { }
	// RVA: 0x678dd10 VA: 0x7598da5d10
	private Void _Release() { }
	// RVA: 0x678dfb0 VA: 0x7598da5fb0
	private Void _Tick(Single unscaledDeltaTime, Double unscaledTime) { }
	// RVA: 0x678e298 VA: 0x7598da6298
	private Void _ChangeGlobalTimeScale(Single timeScale) { }
	// RVA: 0x678e4c0 VA: 0x7598da64c0
	public Void .ctor() { }
}
```