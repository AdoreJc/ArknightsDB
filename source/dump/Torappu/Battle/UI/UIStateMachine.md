# UIStateMachine

**Namespace:** `Torappu.Battle.UI`


## Properties

- `IUIStateNode currentState`


## Methods

- `IUIStateNode get_currentState()`

- `Void RegisterState(UIStateEnum, IUIStateNode, Boolean)`

- `Void Start(UIStateEnum)`

- `Void SetDefaultState(UIStateEnum)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIStateMachine : EnumStateMachine`1
{

	public IUIStateNode currentState { get; }

	// RVA: 0x2077f5c VA: 0x759468ff5c
	public IUIStateNode get_currentState() { }
	// RVA: 0x2075770 VA: 0x759468d770
	public Void RegisterState(UIStateEnum state, IUIStateNode stateNode, Boolean asDefault) { }
	// RVA: 0x20784e8 VA: 0x75946904e8
	public Void Start(UIStateEnum state) { }
	// RVA: 0x20784f0 VA: 0x75946904f0
	public Void SetDefaultState(UIStateEnum state) { }
	// RVA: 0x20784f8 VA: 0x75946904f8
	protected override Void OnStateChanged(Int32 newStateId, Int32 oldStateId) { }
	// RVA: 0x2078624 VA: 0x7594690624
	public Void .ctor() { }
}
```