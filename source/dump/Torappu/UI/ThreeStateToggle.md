# ThreeStateToggle

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _unselect`

- `GameObject _firstSelect`

- `GameObject _secondSelect`

- `Boolean _setWithAwake`

- `State m_state`


## Properties

- `State state`


## Methods

- `Void set_onToggle(Action`1)`

- `Void Awake()`

- `Void Toggle()`

- `State get_state()`

- `Void set_state(State)`

- `Void _ChangeState(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ThreeStateToggle : MonoBehaviour, IHotfixable
{
	private GameObject _unselect; // 0x18
	private GameObject _firstSelect; // 0x20
	private GameObject _secondSelect; // 0x28
	private Boolean _setWithAwake; // 0x30
	private State m_state; // 0x34
	private Action`1 m_stateToggleListener; // 0x38
	private static DelegateBridge __Hotfix0_get_onToggle; // 0x0
	private static DelegateBridge __Hotfix0_set_onToggle; // 0x8
	private static DelegateBridge __Hotfix0_Awake; // 0x10
	private static DelegateBridge __Hotfix0_Toggle; // 0x18
	private static DelegateBridge __Hotfix0_get_state; // 0x20
	private static DelegateBridge __Hotfix0_set_state; // 0x28
	private static DelegateBridge __Hotfix0__ChangeState; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Action`1 onToggle { get; set; }
	public State state { get; set; }

	// RVA: 0x2240054 VA: 0x7594858054
	public Action`1 get_onToggle() { }
	// RVA: 0x22400bc VA: 0x75948580bc
	public Void set_onToggle(Action`1 value) { }
	// RVA: 0x2240140 VA: 0x7594858140
	private Void Awake() { }
	// RVA: 0x2240310 VA: 0x7594858310
	public Void Toggle() { }
	// RVA: 0x22403c0 VA: 0x75948583c0
	public State get_state() { }
	// RVA: 0x2240428 VA: 0x7594858428
	public Void set_state(State value) { }
	// RVA: 0x22401c0 VA: 0x75948581c0
	private Void _ChangeState(State newState) { }
	// RVA: 0x22404a8 VA: 0x75948584a8
	public Void .ctor() { }
}
```