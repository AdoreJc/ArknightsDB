# RoguelikeShopNormalView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _rootGroup`

- `Single _fadeDuration`

- `GameObject _switchPanel`

- `UIAnimationLocation _switchAnimationLocation`

- `CanvasGroup _leaveCanvasGroup`

- `GameObject _confirmLeavePanelGo`

- `CanvasGroup _confirmBtnCanvasGroup`

- `RectTransform _confirmBtnRt`

- `Vector2 _confirmBtnHidePos`

- `Vector2 _confirmBtnShowPos`

- `GameObject _btnBattleGo`

- `Boolean m_hasInited`

- `FadeSwitchTween m_rootSwitchTween`

- `AnimationSwitchTween m_switchTween`

- `FadeSwitchTween m_leaveSwitchTween`

- `FadeTranslationSwitchTween m_leaveConfirmSwitchTween`

- `RoguelikeShopNormalControllerBindings m_controllerBindings`


## Properties

- `Boolean isReady`


## Methods

- `Boolean get_isReady()`

- `Void OnSwitchEvent()`

- `Void OnBtnConfirmLeaveShow()`

- `Void OnBtnConfirmLeaveHide()`

- `Void OnLeaveShop()`

- `Void OnDealerClick()`

- `Void Init()`

- `Single SetShow(Boolean, Boolean, RoguelikeGameShopStatusEnum)`

- `RoguelikeGameShopStatusEnum GetShopStatus()`

- `RoguelikeGameShopStatusEnum GetRivalStatus()`

- `Void BindShopController(RoguelikeShopNormalControllerBindings)`

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__30_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopNormalView : DataBinder`1, IRoguelikeGameShopVisibility
{
	private CanvasGroup _rootGroup; // 0x20
	private Single _fadeDuration; // 0x28
	private GameObject _switchPanel; // 0x30
	private UIAnimationLocation _switchAnimationLocation; // 0x38
	private CanvasGroup _leaveCanvasGroup; // 0x48
	private GameObject _confirmLeavePanelGo; // 0x50
	private CanvasGroup _confirmBtnCanvasGroup; // 0x58
	private RectTransform _confirmBtnRt; // 0x60
	private Vector2 _confirmBtnHidePos; // 0x68
	private Vector2 _confirmBtnShowPos; // 0x70
	private GameObject _btnBattleGo; // 0x78
	private Boolean m_hasInited; // 0x80
	private FadeSwitchTween m_rootSwitchTween; // 0x88
	private AnimationSwitchTween m_switchTween; // 0x90
	private FadeSwitchTween m_leaveSwitchTween; // 0x98
	private FadeTranslationSwitchTween m_leaveConfirmSwitchTween; // 0xa0
	private RoguelikeShopNormalControllerBindings m_controllerBindings; // 0xa8
	private static DelegateBridge __Hotfix0_get_isReady; // 0x0
	private static DelegateBridge __Hotfix0_OnSwitchEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnConfirmLeaveShow; // 0x10
	private static DelegateBridge __Hotfix0_OnBtnConfirmLeaveHide; // 0x18
	private static DelegateBridge __Hotfix0_OnLeaveShop; // 0x20
	private static DelegateBridge __Hotfix0_OnDealerClick; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_SetShow; // 0x38
	private static DelegateBridge __Hotfix0_GetShopStatus; // 0x40
	private static DelegateBridge __Hotfix0_GetRivalStatus; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0_BindShopController; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Boolean isReady { get; }

	// RVA: 0x2aeb608 VA: 0x7595103608
	public Boolean get_isReady() { }
	// RVA: 0x2aeb694 VA: 0x7595103694
	public Void OnSwitchEvent() { }
	// RVA: 0x2aeb790 VA: 0x7595103790
	public Void OnBtnConfirmLeaveShow() { }
	// RVA: 0x2aeb82c VA: 0x759510382c
	public Void OnBtnConfirmLeaveHide() { }
	// RVA: 0x2aeb8b8 VA: 0x75951038b8
	public Void OnLeaveShop() { }
	// RVA: 0x2aeb9b4 VA: 0x75951039b4
	public Void OnDealerClick() { }
	// RVA: 0x2aebab0 VA: 0x7595103ab0
	public Void Init() { }
	// RVA: 0x2aebe30 VA: 0x7595103e30
	public Single SetShow(Boolean isShow, Boolean fastMode, RoguelikeGameShopStatusEnum current) { }
	// RVA: 0x2aebf9c VA: 0x7595103f9c
	public RoguelikeGameShopStatusEnum GetShopStatus() { }
	// RVA: 0x2aec004 VA: 0x7595104004
	public RoguelikeGameShopStatusEnum GetRivalStatus() { }
	// RVA: 0x2aec068 VA: 0x7595104068
	public override Void OnValueChanged(RoguelikeGameShopGoodsProperty property) { }
	// RVA: 0x2aec14c VA: 0x759510414c
	public Void BindShopController(RoguelikeShopNormalControllerBindings bindings) { }
	// RVA: 0x2aebb68 VA: 0x7595103b68
	private Void _InitIfNot() { }
	// RVA: 0x2aec1d0 VA: 0x75951041d0
	public Void .ctor() { }
	// RVA: 0x2aec26c VA: 0x759510426c
	private Void <_InitIfNot>b__30_0() { }
}
```