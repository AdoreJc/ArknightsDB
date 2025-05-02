# StateTransition

**Namespace:** ` `


## Fields

- `UIPopupState m_closure`

- `TransitionSide m_side`

- `TransactionContext m_context`

- `TransitionType transType`


## Properties

- `TransActionType ActionType`

- `TransactionContext context`


## Methods

- `TransActionType get_ActionType()`

- `Void Execute(State, State, TransActionListener)`

- `Void ExecuteFastMode(State, State, TransActionListener)`

- `TransactionContext get_context()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class StateTransition : ITransAction
{
	private UIPopupState m_closure; // 0x10
	private Action`2 m_process; // 0x18
	private TransitionSide m_side; // 0x20
	private TransactionContext m_context; // 0x28
	public TransitionType transType; // 0x48

	public TransActionType ActionType { get; }
	public TransactionContext context { get; }

	// RVA: 0x221c84c VA: 0x759483484c
	public Void .ctor(UIPopupState closure, TransitionSide side, Action`2 process) { }
	// RVA: 0x221d140 VA: 0x7594835140
	public TransActionType get_ActionType() { }
	// RVA: 0x221d148 VA: 0x7594835148
	public Void Execute(State fromState, State toState, TransActionListener mustInvokeEnd) { }
	// RVA: 0x221d2a8 VA: 0x75948352a8
	public Void ExecuteFastMode(State fromState, State toState, TransActionListener mustInvokeEnd) { }
	// RVA: 0x221d408 VA: 0x7594835408
	public TransactionContext get_context() { }
}
```