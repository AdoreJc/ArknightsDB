# DataTransAction

**Namespace:** `Torappu.UI`


## Fields

- `TransitionSide m_transSide`


## Properties

- `TransActionType ActionType`


## Methods

- `Void Execute(State, State, TransActionListener)`

- `Void ExecuteFastMode(State, State, TransActionListener)`

- `TransActionType get_ActionType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DataTransAction : ITransAction
{
	private Action`1 m_dataListener; // 0x10
	private TransitionSide m_transSide; // 0x18

	public TransActionType ActionType { get; }

	// RVA: 0x21623e8 VA: 0x759477a3e8
	public Void .ctor(TransitionSide side, Action`1 callback) { }
	// RVA: 0x2167ee4 VA: 0x759477fee4
	public Void Execute(State fromState, State toState, TransActionListener mustInvokeEnd) { }
	// RVA: 0x2167f60 VA: 0x759477ff60
	public Void ExecuteFastMode(State fromState, State toState, TransActionListener mustInvokeEnd) { }
	// RVA: 0x2167f64 VA: 0x759477ff64
	public TransActionType get_ActionType() { }
}
```