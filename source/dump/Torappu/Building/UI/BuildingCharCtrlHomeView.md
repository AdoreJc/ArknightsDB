# BuildingCharCtrlHomeView

**Namespace:** `Torappu.Building.UI`


## Fields

- `ETCJoystick _etcJoystick`

- `GameObject _panelTouch`

- `BuildingCharCtrlTouchBtn _btnTouch`

- `GameObject _panelUpAndDown`

- `CanvasGroup _canvasGroupUpDownBtn`

- `CanvasGroup _canvasGroupWaiting`

- `Button _btnUpstairs`

- `Button _btnDownstairs`

- `GameObject _panelUpWaiting`

- `GameObject _panelDownWaiting`

- `UIAnimationLocation _animationLocationShow`

- `UIAnimationLocation _animationLocationHide`

- `GameObject _panelSwitchUIBtn`

- `UIAnimationLocation _animationLocationShowEmoji`

- `UIAnimationLocation _animationLocationHideEmoji`

- `SimpleLayoutContent _emojiLayoutContent`

- `BuildingCharCtrlHomeViewModel m_cachedViewModel`

- `Boolean m_cachedIsShowUI`

- `Boolean m_cachedShowEmoji`

- `EmojiAdapter m_emojiAdapter`

- `Tween m_showHideTween`

- `Tween m_emojiShowHideTween`

- `Boolean m_isInited`

- `Boolean m_cachedIsUpDownstairs`

- `FadeSwitchTween m_upDownBtnFadeTween`

- `FadeSwitchTween m_waitingFadeTween`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateUpDownstairsRelated(BuildingCharCtrlHomeViewModel)`

- `Vector2 GetJoystickAxis()`

- `Void <OnValueChanged>b__27_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingCharCtrlHomeView : DataBinder`1
{
	private ETCJoystick _etcJoystick; // 0x20
	private GameObject _panelTouch; // 0x28
	private BuildingCharCtrlTouchBtn _btnTouch; // 0x30
	private GameObject _panelUpAndDown; // 0x38
	private CanvasGroup _canvasGroupUpDownBtn; // 0x40
	private CanvasGroup _canvasGroupWaiting; // 0x48
	private Button _btnUpstairs; // 0x50
	private Button _btnDownstairs; // 0x58
	private GameObject _panelUpWaiting; // 0x60
	private GameObject _panelDownWaiting; // 0x68
	private UIAnimationLocation _animationLocationShow; // 0x70
	private UIAnimationLocation _animationLocationHide; // 0x80
	private GameObject _panelSwitchUIBtn; // 0x90
	private UIAnimationLocation _animationLocationShowEmoji; // 0x98
	private UIAnimationLocation _animationLocationHideEmoji; // 0xa8
	private SimpleLayoutContent _emojiLayoutContent; // 0xb8
	private BuildingCharCtrlHomeViewModel m_cachedViewModel; // 0xc0
	private Boolean m_cachedIsShowUI; // 0xc8
	private Boolean m_cachedShowEmoji; // 0xc9
	private EmojiAdapter m_emojiAdapter; // 0xd0
	private Tween m_showHideTween; // 0xd8
	private Tween m_emojiShowHideTween; // 0xe0
	private Boolean m_isInited; // 0xe8
	private Boolean m_cachedIsUpDownstairs; // 0xe9
	private FadeSwitchTween m_upDownBtnFadeTween; // 0xf0
	private FadeSwitchTween m_waitingFadeTween; // 0xf8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__UpdateUpDownstairsRelated; // 0x10
	private static DelegateBridge __Hotfix0_GetJoystickAxis; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3d32a14 VA: 0x759634aa14
	public override Void OnValueChanged(BuildingCharCtrlHomeViewModelProperty property) { }
	// RVA: 0x3d32ce4 VA: 0x759634ace4
	private Void _InitIfNot() { }
	// RVA: 0x3d32f58 VA: 0x759634af58
	private Void _UpdateUpDownstairsRelated(BuildingCharCtrlHomeViewModel viewModel) { }
	// RVA: 0x3d33200 VA: 0x759634b200
	public Vector2 GetJoystickAxis() { }
	// RVA: 0x3d332f8 VA: 0x759634b2f8
	public Void .ctor() { }
	// RVA: 0x3d33390 VA: 0x759634b390
	private Void <OnValueChanged>b__27_0() { }
}
```