# AutoChessStateMachine

**Namespace:** ` `


## Fields

- `AutoChessPerformSoftLock m_softLock`

- `AutoChessGameStateBase m_currentState`


## Properties

- `AutoChessPerformSoftLock softLock`


## Methods

- `AutoChessPerformSoftLock get_softLock()`

- `AutoChessGameStateBase GetCurrentState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AutoChessStateMachine : EnumStateMachine`1
{
	private AutoChessPerformSoftLock m_softLock; // 0x58
	private AutoChessGameStateBase m_currentState; // 0x60

	public AutoChessPerformSoftLock softLock { get; }

	// RVA: 0x1cab4f4 VA: 0x75942c34f4
	public AutoChessPerformSoftLock get_softLock() { }
	// RVA: 0x1cab4fc VA: 0x75942c34fc
	public AutoChessGameStateBase GetCurrentState() { }
	// RVA: 0x1cab504 VA: 0x75942c3504
	protected override Void OnStateChanged(Int32 newStateId, Int32 oldStateId) { }
	// RVA: 0x1cab5d4 VA: 0x75942c35d4
	public Void .ctor() { }
}
```