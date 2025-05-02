# UIStateTransitionTween

**Namespace:** `Torappu.UI`


## Fields

- `Tween m_cachedTween`

- `TState m_currentState`

- `Int32 m_currentStateIntKey`


## Properties

- `Boolean isPlaying`

- `TState state`


## Methods

- `Boolean get_isPlaying()`

- `TState get_state()`

- `Void SetTweenProvider(TState, TState, TweenProvider)`

- `Void GoToState(TState, Boolean)`

- `Void _SetCurrentStateAndUpdateKey(TState)`

- `Boolean _TryGetTransition(TState, TState, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIStateTransitionTween`1
{
	private EnumIntDictionary`2 m_tweenDict; // 0x0
	private Tween m_cachedTween; // 0x0
	private TState m_currentState; // 0x0
	private Int32 m_currentStateIntKey; // 0x0

	public Boolean isPlaying { get; }
	public TState state { get; }

	// RVA: 0x VA: 0x0
	public Boolean get_isPlaying() { }
	// RVA: 0x VA: 0x0
	public TState get_state() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(TState defaultState) { }
	// RVA: 0x VA: 0x0
	public Void SetTweenProvider(TState fromState, TState toState, TweenProvider tweenProvider) { }
	// RVA: 0x VA: 0x0
	public Void GoToState(TState toState, Boolean isFastMode) { }
	// RVA: 0x VA: 0x0
	private Void _SetCurrentStateAndUpdateKey(TState state) { }
	// RVA: 0x VA: 0x0
	private EnumIntDictionary`2 _GetStateTweenDict(TState state) { }
	// RVA: 0x VA: 0x0
	private Boolean _TryGetTransition(TState fromState, TState toState, out TweenProvider tweenProvider) { }
}
```