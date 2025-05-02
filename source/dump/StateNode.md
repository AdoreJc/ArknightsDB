# StateNode

**Namespace:** ` `


## Properties

- `Boolean isActiveNode`

- `DataType data`

- `BlackboardType blackboard`


## Methods

- `Boolean get_isActiveNode()`

- `DataType get_data()`

- `BlackboardType get_blackboard()`

- `Void SwitchState(StateType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StateNode : IStateNode
{
	private HierachyStateMachine`3 m_stateMachine; // 0x0

	public Boolean isActiveNode { get; }
	protected DataType data { get; }
	protected BlackboardType blackboard { get; }
	protected HierachyStateMachine`3 stateMachine { get; }

	// RVA: 0x VA: 0x0
	public Boolean get_isActiveNode() { }
	// RVA: 0x VA: 0x0
	protected DataType get_data() { }
	// RVA: 0x VA: 0x0
	protected BlackboardType get_blackboard() { }
	// RVA: 0x VA: 0x0
	protected HierachyStateMachine`3 get_stateMachine() { }
	// RVA: 0x VA: 0x0
	public virtual Void OnInit(HierachyStateMachine`3 stateMachine) { }
	// RVA: 0x VA: 0x0
	public virtual Void OnEnter(Int32 lastState) { }
	// RVA: 0x VA: 0x0
	public virtual Void OnExit(Int32 newState) { }
	// RVA: 0x VA: 0x0
	public virtual Void OnTick(FP deltaTime) { }
	// RVA: 0x VA: 0x0
	public virtual Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x VA: 0x0
	protected Void SwitchState(StateType type) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```