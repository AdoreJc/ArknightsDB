# ActivityTopBarView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _activityIcon`

- `Image _backImage`

- `Text _infoText`

- `Text _infoText2`

- `Button _button`

- `UICommonTrackPoint _trackPoint`

- `GameObject _panelLocked`

- `GameObject _panelFinished`

- `Boolean _needSwitchAnim`

- `UIAnimationLocation _verticalShowAnim`

- `UIAnimationLocation _verticalHideAnim`

- `CanvasGroup _rootCanvasGroup`

- `LayoutElement _preferredLayout`

- `Action <onSwitchAnimEnd>k__BackingField`

- `Action <onSwitchAnimStart>k__BackingField`

- `TrackPointViewProperty m_activityRedPoint`

- `HomeActivityConfig m_homeActConfig`

- `Boolean m_isUnlocked`

- `UISwitchTween m_switchTween`


## Properties

- `Single preferredHeight`

- `Action onSwitchAnimEnd`

- `Action onSwitchAnimStart`


## Methods

- `Single get_preferredHeight()`

- `Action get_onSwitchAnimEnd()`

- `Void set_onSwitchAnimEnd(Action)`

- `Action get_onSwitchAnimStart()`

- `Void set_onSwitchAnimStart(Action)`

- `Void set_onClick(Action`1)`

- `Void Render(String, ActShowType, HomeActivityConfig, Boolean)`

- `Void _SetShow(Boolean, Boolean)`

- `Void _RenderBasicInfo()`

- `Void _UpdateStatus(ActShowType)`

- `Boolean _ShowSwitchAnim()`

- `Void _EnsureSwitchTweenIfHave()`

- `Void EventOnClick()`

- `Void EventOnLockedClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class ActivityTopBarView : MonoBehaviour, IHotfixable
{
	private Image _activityIcon; // 0x18
	private Image _backImage; // 0x20
	private Text _infoText; // 0x28
	private Text _infoText2; // 0x30
	private Button _button; // 0x38
	private UICommonTrackPoint _trackPoint; // 0x40
	private GameObject _panelLocked; // 0x48
	private GameObject _panelFinished; // 0x50
	private Boolean _needSwitchAnim; // 0x58
	private UIAnimationLocation _verticalShowAnim; // 0x60
	private UIAnimationLocation _verticalHideAnim; // 0x70
	private CanvasGroup _rootCanvasGroup; // 0x80
	private LayoutElement _preferredLayout; // 0x88
	private Action <onSwitchAnimEnd>k__BackingField; // 0x90
	private Action <onSwitchAnimStart>k__BackingField; // 0x98
	private TrackPointViewProperty m_activityRedPoint; // 0xa0
	private HomeActivityConfig m_homeActConfig; // 0xa8
	private Boolean m_isUnlocked; // 0xb0
	private UISwitchTween m_switchTween; // 0xb8
	private Action`1 <onClick>k__BackingField; // 0xc0
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x0
	private static DelegateBridge __Hotfix0_get_onSwitchAnimEnd; // 0x8
	private static DelegateBridge __Hotfix0_set_onSwitchAnimEnd; // 0x10
	private static DelegateBridge __Hotfix0_get_onSwitchAnimStart; // 0x18
	private static DelegateBridge __Hotfix0_set_onSwitchAnimStart; // 0x20
	private static DelegateBridge __Hotfix0_get_onClick; // 0x28
	private static DelegateBridge __Hotfix0_set_onClick; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0__SetShow; // 0x40
	private static DelegateBridge __Hotfix0__RenderBasicInfo; // 0x48
	private static DelegateBridge __Hotfix0__UpdateStatus; // 0x50
	private static DelegateBridge __Hotfix0__ShowSwitchAnim; // 0x58
	private static DelegateBridge __Hotfix0__EnsureSwitchTweenIfHave; // 0x60
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x68
	private static DelegateBridge __Hotfix0_EventOnLockedClicked; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Single preferredHeight { get; }
	private Action onSwitchAnimEnd { get; set; }
	private Action onSwitchAnimStart { get; set; }
	private Action`1 onClick { get; set; }

	// RVA: 0x2823fbc VA: 0x7594e3bfbc
	public Single get_preferredHeight() { }
	// RVA: 0x2824ad4 VA: 0x7594e3cad4
	private Action get_onSwitchAnimEnd() { }
	// RVA: 0x282303c VA: 0x7594e3b03c
	public Void set_onSwitchAnimEnd(Action value) { }
	// RVA: 0x2824b3c VA: 0x7594e3cb3c
	private Action get_onSwitchAnimStart() { }
	// RVA: 0x28230c0 VA: 0x7594e3b0c0
	public Void set_onSwitchAnimStart(Action value) { }
	// RVA: 0x2824ba4 VA: 0x7594e3cba4
	private Action`1 get_onClick() { }
	// RVA: 0x2822fb8 VA: 0x7594e3afb8
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2823ce4 VA: 0x7594e3bce4
	public Void Render(String actId, ActShowType showType, HomeActivityConfig config, Boolean fastMode) { }
	// RVA: 0x2825000 VA: 0x7594e3d000
	private Void _SetShow(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2824c0c VA: 0x7594e3cc0c
	private Void _RenderBasicInfo() { }
	// RVA: 0x282511c VA: 0x7594e3d11c
	private Void _UpdateStatus(ActShowType showType) { }
	// RVA: 0x282544c VA: 0x7594e3d44c
	private Boolean _ShowSwitchAnim() { }
	// RVA: 0x28252c4 VA: 0x7594e3d2c4
	private Void _EnsureSwitchTweenIfHave() { }
	// RVA: 0x28254b4 VA: 0x7594e3d4b4
	public Void EventOnClick() { }
	// RVA: 0x2825580 VA: 0x7594e3d580
	public Void EventOnLockedClicked() { }
	// RVA: 0x2825628 VA: 0x7594e3d628
	public Void .ctor() { }
}
```