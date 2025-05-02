# BackInTransition

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
private class BackInTransition : ITransAction
{
	private StageZoneSelectState m_closure; // 0x10

	public TransActionType ActionType { get; }

	// RVA: 0x2f70878 VA: 0x7595588878
	public Void .ctor(StageZoneSelectState closure) { }
	// RVA: 0x2f724e4 VA: 0x759558a4e4
	public TransActionType get_ActionType() { }
	// RVA: 0x2f724ec VA: 0x759558a4ec
	public Void Execute(State fromState, State toState, TransActionListener mustInvokeEnd) { }
	// RVA: 0x2f72530 VA: 0x759558a530
	public Void ExecuteFastMode(State fromState, State toState, TransActionListener mustInvokeEnd) { }
	// RVA: 0x2f724f8 VA: 0x759558a4f8
	private Void _Execute(TransActionListener mustInvokeEnd) { }
}
```