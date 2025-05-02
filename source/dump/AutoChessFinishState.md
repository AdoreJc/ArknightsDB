# AutoChessFinishState

**Namespace:** ` `


## Fields

- `IEnumerator m_finishGameCoroutine`


## Methods

- `IEnumerator _DoFinishGame()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AutoChessFinishState : AutoChessGameStateBase
{
	private IEnumerator m_finishGameCoroutine; // 0x10

	public override GameState currentState { get; }

	// RVA: 0x1cad548 VA: 0x75942c5548
	public override GameState get_currentState() { }
	// RVA: 0x1cad550 VA: 0x75942c5550
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1cad61c VA: 0x75942c561c
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1cad5bc VA: 0x75942c55bc
	private IEnumerator _DoFinishGame() { }
	// RVA: 0x1cad6d8 VA: 0x75942c56d8
	public Void .ctor() { }
}
```