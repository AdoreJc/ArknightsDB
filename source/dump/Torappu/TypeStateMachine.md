# TypeStateMachine

**Namespace:** `Torappu`


## Methods

- `Void SwitchState(IStateNode)`

- `Int32 Type2Int(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TypeStateMachine : StateMachine
{
	private Dictionary`2 m_type2int; // 0x58


	// RVA: 0x35013a4 VA: 0x7595b193a4
	public Void .ctor() { }
	// RVA: 0x350142c VA: 0x7595b1942c
	public Void .ctor(IBlackboard blackboard) { }
	// RVA: 0x35014c0 VA: 0x7595b194c0
	public Void SwitchState(IStateNode toState) { }
	// RVA: 0x35015c4 VA: 0x7595b195c4
	public virtual Void RegisterState(IStateNode stateNode, Boolean asDefault) { }
	// RVA: 0x35014fc VA: 0x7595b194fc
	protected Int32 Type2Int(Type type) { }
}
```