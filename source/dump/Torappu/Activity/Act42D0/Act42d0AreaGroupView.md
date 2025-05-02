# Act42d0AreaGroupView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Act42D0AreaDifficulty _difficulty`

- `UIAnimationLocation _hideSwitchAnim`

- `RectTransform _focusTweenRoot`

- `AnimationSwitchTween m_switchTw`

- `Boolean m_inited`

- `String m_cachedSelectAreaId`

- `Single m_focusThreshold`

- `Single m_focusDuration`

- `Tween m_focusTween`

- `Boolean m_cachedShowStatus`


## Properties

- `Act42D0AreaDifficulty difficulty`


## Methods

- `Act42D0AreaDifficulty get_difficulty()`

- `Void _InitIfNot()`

- `Void RenderAreas(Act42d0AreaMapViewModel)`

- `Void _TryFocusArea(Act42d0AreaMapViewModel)`

- `Void _FocusAreaImpl(Single)`

- `Void _RenderAreaButtons(Act42d0AreaMapViewModel, Boolean)`

- `Boolean TryRegisterAreaGo()`

- `Void SetFocusThreshold(Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42d0AreaGroupView : MonoBehaviour, IHotfixable
{
	private Act42d0AreaButtonHolder[] _btnHolders; // 0x18
	private Act42D0AreaDifficulty _difficulty; // 0x20
	private UIAnimationLocation _hideSwitchAnim; // 0x28
	private RectTransform _focusTweenRoot; // 0x38
	private AnimationSwitchTween m_switchTw; // 0x40
	private Boolean m_inited; // 0x48
	private String m_cachedSelectAreaId; // 0x50
	private Single m_focusThreshold; // 0x58
	private Single m_focusDuration; // 0x5c
	private Tween m_focusTween; // 0x60
	private Boolean m_cachedShowStatus; // 0x68
	private static DelegateBridge __Hotfix0_get_difficulty; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_RenderAreas; // 0x10
	private static DelegateBridge __Hotfix0__TryFocusArea; // 0x18
	private static DelegateBridge __Hotfix0__FocusAreaImpl; // 0x20
	private static DelegateBridge __Hotfix0__RenderAreaButtons; // 0x28
	private static DelegateBridge __Hotfix0_TryRegisterAreaGo; // 0x30
	private static DelegateBridge __Hotfix0_SetFocusThreshold; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Act42D0AreaDifficulty difficulty { get; }

	// RVA: 0x3217d04 VA: 0x759582fd04
	public Act42D0AreaDifficulty get_difficulty() { }
	// RVA: 0x3217d6c VA: 0x759582fd6c
	private Void _InitIfNot() { }
	// RVA: 0x3217e5c VA: 0x759582fe5c
	public Void RenderAreas(Act42d0AreaMapViewModel viewModel) { }
	// RVA: 0x3218160 VA: 0x7595830160
	private Void _TryFocusArea(Act42d0AreaMapViewModel viewModel) { }
	// RVA: 0x32183c8 VA: 0x75958303c8
	private Void _FocusAreaImpl(Single targetVal) { }
	// RVA: 0x3217f68 VA: 0x759582ff68
	private Void _RenderAreaButtons(Act42d0AreaMapViewModel viewModel, Boolean showStatusChanged) { }
	// RVA: 0x321860c VA: 0x759583060c
	public Boolean TryRegisterAreaGo() { }
	// RVA: 0x321875c VA: 0x759583075c
	public Void SetFocusThreshold(Single focusThreshold, Single focusDuration) { }
	// RVA: 0x32187e0 VA: 0x75958307e0
	public Void .ctor() { }
}
```