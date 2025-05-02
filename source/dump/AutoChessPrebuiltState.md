# AutoChessPrebuiltState

**Namespace:** ` `


## Fields

- `Coroutine m_prebuiltCoroutine`


## Methods

- `IEnumerator _Prebuilt()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AutoChessPrebuiltState : AutoChessGameStateBase
{
	private const Single PREBUILT_DURATION; // 0x0
	private Coroutine m_prebuiltCoroutine; // 0x10

	public override GameState currentState { get; }

	// RVA: 0x1cb38e4 VA: 0x75942cb8e4
	public override GameState get_currentState() { }
	// RVA: 0x1cb38ec VA: 0x75942cb8ec
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1cb3aa4 VA: 0x75942cbaa4
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1cb3b5c VA: 0x75942cbb5c
	public override Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x1cb3a44 VA: 0x75942cba44
	private IEnumerator _Prebuilt() { }
	// RVA: 0x1cb3c20 VA: 0x75942cbc20
	public Void .ctor() { }
}
```