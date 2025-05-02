# UIStateMachine

**Namespace:** `YostarSDK.UI`


## Fields

- `Boolean m_isTransitting`

- `Coroutine m_transitCoroutine`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`

- `IUIState currentState`

- `Boolean isTransiting`

- `StateType state`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `IUIState get_currentState()`

- `Boolean get_isTransiting()`

- `Void set_isTransiting(Boolean)`

- `Void add_onStateTransitionStart(Action`2)`

- `Void remove_onStateTransitionStart(Action`2)`

- `StateType get_state()`

- `Void RegisterState(IUIState, Boolean)`

- `Void SwitchState(StateType)`

- `Void SwitchState(StateType, Single)`

- `IUIState _GetState(StateType)`

- `IEnumerator _DoTransition(TransitionParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class UIStateMachine`1 : EnumStateMachine`1
{
	private Boolean m_isTransitting; // 0x0
	private Coroutine m_transitCoroutine; // 0x0
	private UIPage <page>k__BackingField; // 0x0
	private Action`2 onStateTransitionStart; // 0x0

	protected UIPage page { get; set; }
	protected IUIState currentState { get; }
	protected Boolean isTransiting { get; set; }
	public StateType state { get; }

	// RVA: 0x VA: 0x0
	protected UIPage get_page() { }
	// RVA: 0x VA: 0x0
	private Void set_page(UIPage value) { }
	// RVA: 0x VA: 0x0
	protected IUIState get_currentState() { }
	// RVA: 0x VA: 0x0
	protected Boolean get_isTransiting() { }
	// RVA: 0x VA: 0x0
	private Void set_isTransiting(Boolean value) { }
	// RVA: 0x VA: 0x0
	public Void add_onStateTransitionStart(Action`2 value) { }
	// RVA: 0x VA: 0x0
	public Void remove_onStateTransitionStart(Action`2 value) { }
	// RVA: 0x VA: 0x0
	public StateType get_state() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(UIPage page) { }
	// RVA: 0x VA: 0x0
	public Void RegisterState(IUIState stateNode, Boolean asDefault) { }
	// RVA: 0x VA: 0x0
	public Void SwitchState(StateType toState) { }
	// RVA: 0x VA: 0x0
	public Void SwitchState(StateType toState, Single duration) { }
	// RVA: 0x VA: 0x0
	private IUIState _GetState(StateType stateType) { }
	// RVA: 0x VA: 0x0
	private IEnumerator _DoTransition(TransitionParam param) { }
}
```