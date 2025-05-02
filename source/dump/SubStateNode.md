# SubStateNode

**Namespace:** ` `


## Methods

- `Void set_parentState(SubStateMachineNode`1)`

- `Void SwitchParentState(StateType)`

- `Void ExitParentByDefault()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class SubStateNode : StateNode
{
	private SubStateMachineNode`1 <parentState>k__BackingField; // 0x0

	protected SubStateMachineNode`1 parentState { get; set; }

	// RVA: 0x VA: 0x0
	protected SubStateMachineNode`1 get_parentState() { }
	// RVA: 0x VA: 0x0
	private Void set_parentState(SubStateMachineNode`1 value) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(SubStateMachineNode`1 parentState) { }
	// RVA: 0x VA: 0x0
	protected Void SwitchParentState(StateType toState) { }
	// RVA: 0x VA: 0x0
	protected Void ExitParentByDefault() { }
}
```