# TwoStateToggle

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _unselect`

- `GameObject _select`

- `Boolean _setWithAwake`

- `State m_state`

- `Boolean m_isInited`


## Properties

- `State state`

- `Boolean selected`


## Methods

- `Void set_onToggle(Action`1)`

- `Void Awake()`

- `Void Toggle()`

- `State get_state()`

- `Void set_state(State)`

- `Boolean get_selected()`

- `Void set_selected(Boolean)`

- `Void _ChangeState(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TwoStateToggle : MonoBehaviour, IHotfixable
{
	private GameObject _unselect; // 0x18
	private GameObject _select; // 0x20
	private Boolean _setWithAwake; // 0x28
	private State m_state; // 0x2c
	private Action`1 m_stateToggleListener; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0_get_onToggle; // 0x0
	private static DelegateBridge __Hotfix0_set_onToggle; // 0x8
	private static DelegateBridge __Hotfix0_Awake; // 0x10
	private static DelegateBridge __Hotfix0_Toggle; // 0x18
	private static DelegateBridge __Hotfix0_get_state; // 0x20
	private static DelegateBridge __Hotfix0_set_state; // 0x28
	private static DelegateBridge __Hotfix0_get_selected; // 0x30
	private static DelegateBridge __Hotfix0_set_selected; // 0x38
	private static DelegateBridge __Hotfix0__ChangeState; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Action`1 onToggle { get; set; }
	public State state { get; set; }
	public Boolean selected { get; set; }

	// RVA: 0x2240c50 VA: 0x7594858c50
	public Action`1 get_onToggle() { }
	// RVA: 0x2240cb8 VA: 0x7594858cb8
	public Void set_onToggle(Action`1 value) { }
	// RVA: 0x2240d3c VA: 0x7594858d3c
	private Void Awake() { }
	// RVA: 0x2240dd4 VA: 0x7594858dd4
	public Void Toggle() { }
	// RVA: 0x2240f40 VA: 0x7594858f40
	public State get_state() { }
	// RVA: 0x2240fa8 VA: 0x7594858fa8
	public Void set_state(State value) { }
	// RVA: 0x2241028 VA: 0x7594859028
	public Boolean get_selected() { }
	// RVA: 0x224109c VA: 0x759485909c
	public Void set_selected(Boolean value) { }
	// RVA: 0x2240e70 VA: 0x7594858e70
	private Void _ChangeState(State newState) { }
	// RVA: 0x2241124 VA: 0x7594859124
	public Void .ctor() { }
}
```