# EnumStateMachine

**Namespace:** `Torappu`


## Methods

- `Void Start(StateType)`

- `Void SwitchState(StateType)`

- `Void SetDefaultState(StateType)`

- `IStateNode GetStateNode(StateType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class EnumStateMachine`1 : StateMachine
{


	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IBlackboard blackboard) { }
	// RVA: 0x VA: 0x0
	public Void Start(StateType stateType) { }
	// RVA: 0x VA: 0x0
	public Void SwitchState(StateType toState) { }
	// RVA: 0x VA: 0x0
	public virtual Void RegisterState(StateType state, IStateNode stateNode, Boolean asDefault) { }
	// RVA: 0x VA: 0x0
	public Void SetDefaultState(StateType state) { }
	// RVA: 0x VA: 0x0
	protected IStateNode GetStateNode(StateType state) { }
}
```