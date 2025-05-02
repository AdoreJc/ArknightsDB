# TwoStateFadeSwitcher

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup _unselect`

- `CanvasGroup _select`

- `Boolean _setWithAwake`

- `Boolean _ignoreTimeScale`

- `Single _fadeTime`

- `State m_state`

- `FadeSwitchTween m_selectTween`

- `FadeSwitchTween m_unselectTween`

- `Boolean m_isInited`


## Properties

- `State state`

- `Boolean selected`


## Methods

- `Void set_onToggle(Action`1)`

- `Void _InitIfNot()`

- `Void Awake()`

- `Void Toggle()`

- `State get_state()`

- `Void set_state(State)`

- `Boolean get_selected()`

- `Void set_selected(Boolean)`

- `Void ResetState(State)`

- `Void _ChangeState(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TwoStateFadeSwitcher : MonoBehaviour, IHotfixable
{
	private CanvasGroup _unselect; // 0x18
	private CanvasGroup _select; // 0x20
	private Boolean _setWithAwake; // 0x28
	private Boolean _ignoreTimeScale; // 0x29
	private Single _fadeTime; // 0x2c
	private State m_state; // 0x30
	private Action`1 m_stateToggleListener; // 0x38
	private FadeSwitchTween m_selectTween; // 0x40
	private FadeSwitchTween m_unselectTween; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0_get_onToggle; // 0x0
	private static DelegateBridge __Hotfix0_set_onToggle; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Awake; // 0x18
	private static DelegateBridge __Hotfix0_Toggle; // 0x20
	private static DelegateBridge __Hotfix0_get_state; // 0x28
	private static DelegateBridge __Hotfix0_set_state; // 0x30
	private static DelegateBridge __Hotfix0_get_selected; // 0x38
	private static DelegateBridge __Hotfix0_set_selected; // 0x40
	private static DelegateBridge __Hotfix0_ResetState; // 0x48
	private static DelegateBridge __Hotfix0__ChangeState; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Action`1 onToggle { get; set; }
	public State state { get; set; }
	public Boolean selected { get; set; }

	// RVA: 0x2240520 VA: 0x7594858520
	public Action`1 get_onToggle() { }
	// RVA: 0x2240588 VA: 0x7594858588
	public Void set_onToggle(Action`1 value) { }
	// RVA: 0x224060c VA: 0x759485860c
	private Void _InitIfNot() { }
	// RVA: 0x224074c VA: 0x759485874c
	private Void Awake() { }
	// RVA: 0x2240894 VA: 0x7594858894
	public Void Toggle() { }
	// RVA: 0x22409e8 VA: 0x75948589e8
	public State get_state() { }
	// RVA: 0x2240a50 VA: 0x7594858a50
	public Void set_state(State value) { }
	// RVA: 0x2240ad0 VA: 0x7594858ad0
	public Boolean get_selected() { }
	// RVA: 0x2240b44 VA: 0x7594858b44
	public Void set_selected(Boolean value) { }
	// RVA: 0x22407d4 VA: 0x75948587d4
	public Void ResetState(State newState) { }
	// RVA: 0x2240930 VA: 0x7594858930
	private Void _ChangeState(State newState) { }
	// RVA: 0x2240bcc VA: 0x7594858bcc
	public Void .ctor() { }
}
```