# ForwardOutTransition

**Namespace:** ` `


## Fields

- `StageZoneSelectState m_closure`


## Properties

- `TransActionType ActionType`


## Methods

- `TransActionType get_ActionType()`

- `Void Execute(State, State, TransActionListener)`

- `Void ExecuteFastMode(State, State, TransActionListener)`

- `Void _Execute(TransActionListener)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ForwardOutTransition : ITransAction
{
	private StageZoneSelectState m_closure; // 0x10

	public TransActionType ActionType { get; }

	// RVA: 0x2f70848 VA: 0x7595588848
	public Void .ctor(StageZoneSelectState closure) { }
	// RVA: 0x2f7248c VA: 0x759558a48c
	public TransActionType get_ActionType() { }
	// RVA: 0x2f72494 VA: 0x759558a494
	public Void Execute(State fromState, State toState, TransActionListener mustInvokeEnd) { }
	// RVA: 0x2f724d8 VA: 0x759558a4d8
	public Void ExecuteFastMode(State fromState, State toState, TransActionListener mustInvokeEnd) { }
	// RVA: 0x2f724a0 VA: 0x759558a4a0
	private Void _Execute(TransActionListener mustInvokeEnd) { }
}
```