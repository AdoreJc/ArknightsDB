# HierachyStateMachine

**Namespace:** `Torappu`


## Fields

- `DataType <data>k__BackingField`


## Properties

- `DataType data`

- `BlackboardType blackboard`


## Methods

- `DataType get_data()`

- `Void set_data(DataType)`

- `BlackboardType get_blackboard()`

- `Void SwitchState(StateType)`

- `Void RegisterState(StateType, StateNode, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HierachyStateMachine`3 : StateMachine
{
	private DataType <data>k__BackingField; // 0x0

	public DataType data { get; set; }
	public BlackboardType blackboard { get; }
	public override String stateDebugString { get; }
	protected override Boolean manageBlackboard { get; }

	// RVA: 0x VA: 0x0
	public DataType get_data() { }
	// RVA: 0x VA: 0x0
	private Void set_data(DataType value) { }
	// RVA: 0x VA: 0x0
	public BlackboardType get_blackboard() { }
	// RVA: 0x VA: 0x0
	public override String get_stateDebugString() { }
	// RVA: 0x VA: 0x0
	protected override Boolean get_manageBlackboard() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(DataType data, BlackboardType blackboard) { }
	// RVA: 0x VA: 0x0
	public Void SwitchState(StateType toState) { }
	// RVA: 0x VA: 0x0
	public Void RegisterState(StateType state, StateNode stateNode, Boolean asDefault) { }
}
```