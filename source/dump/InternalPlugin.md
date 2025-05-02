# InternalPlugin

**Namespace:** ` `


## Fields

- `StateEngine m_engine`


## Methods

- `Void NotifyStateEnter(TransEvent)`

- `Void NotifyStateExit(TransEvent)`

- `Void NotifyStatePause(TransEvent)`

- `Void NotifyStateResume(TransEvent)`

- `Void NotifyStatePreResume(TransEvent)`

- `Void NotifyBeforeStateTrans(StateTransContext)`

- `Void _TriggerEventListeners(TransEvent, Action`2)`

- `Void _TriggerListeners(ParamT, Action`2)`

- `Void _OnStateEnter(TransEvent, OnStateChangeListener)`

- `Void _OnStatePreResume(TransEvent, OnStateChangeListener)`

- `Void _OnStateResume(TransEvent, OnStateChangeListener)`

- `Void _OnStatePause(TransEvent, OnStateChangeListener)`

- `Void _OnStateExit(TransEvent, OnStateChangeListener)`

- `Void _BeforeStateChange(StateTransContext, OnStateChangeListener)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InternalPlugin : IStateEnginePlugin
{
	private StateEngine m_engine; // 0x10


	// RVA: 0x2164f98 VA: 0x759477cf98
	public Void .ctor(StateEngine engine) { }
	// RVA: 0x2165240 VA: 0x759477d240
	public Void NotifyStateEnter(TransEvent evt) { }
	// RVA: 0x2165394 VA: 0x759477d394
	public Void NotifyStateExit(TransEvent evt) { }
	// RVA: 0x216542c VA: 0x759477d42c
	public Void NotifyStatePause(TransEvent evt) { }
	// RVA: 0x21654c4 VA: 0x759477d4c4
	public Void NotifyStateResume(TransEvent evt) { }
	// RVA: 0x216555c VA: 0x759477d55c
	public Void NotifyStatePreResume(TransEvent evt) { }
	// RVA: 0x21655f4 VA: 0x759477d5f4
	public Void NotifyBeforeStateTrans(StateTransContext transContext) { }
	// RVA: 0x21652d8 VA: 0x759477d2d8
	private Void _TriggerEventListeners(TransEvent evt, Action`2 callback) { }
	// RVA: 0x VA: 0x0
	private Void _TriggerListeners(ParamT param, Action`2 callback) { }
	// RVA: 0x216571c VA: 0x759477d71c
	private Void _OnStateEnter(TransEvent evt, OnStateChangeListener listener) { }
	// RVA: 0x216577c VA: 0x759477d77c
	private Void _OnStatePreResume(TransEvent evt, OnStateChangeListener listener) { }
	// RVA: 0x21657e0 VA: 0x759477d7e0
	private Void _OnStateResume(TransEvent evt, OnStateChangeListener listener) { }
	// RVA: 0x2165844 VA: 0x759477d844
	private Void _OnStatePause(TransEvent evt, OnStateChangeListener listener) { }
	// RVA: 0x21658a4 VA: 0x759477d8a4
	private Void _OnStateExit(TransEvent evt, OnStateChangeListener listener) { }
	// RVA: 0x2165904 VA: 0x759477d904
	private Void _BeforeStateChange(StateTransContext context, OnStateChangeListener listener) { }
}
```