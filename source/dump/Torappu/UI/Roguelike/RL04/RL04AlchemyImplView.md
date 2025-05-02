# RL04AlchemyImplView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04AlchemyForecastView _forecastView`

- `RL04AlchemySlotListView _slotListView`

- `RL04AlchemyFragmentStorageView _fragmentStorageView`

- `CanvasGroup _canvasAlchemyBtnNotReady`

- `CanvasGroup _canvasAlchemyBtnReady`

- `CanvasGroup _canvasAlchemyBtnCant`

- `GameObject _objLeaveBtnOpeningBlock`

- `UIAnimationLocation _leaveBtnAnim`

- `CanvasGroup _canvasAlchemyTips`

- `Text _txtTipsAlchemy`

- `Text _txtTipsAlchemy1`

- `RL04AlchemyResultView _resultView`

- `RoguelikeRewardStyle <rewardUiStyle>k__BackingField`

- `Boolean m_isInited`

- `String m_topicId`

- `FadeSwitchTween m_tweenAlchemyTips`

- `FadeSwitchTween m_tweenAlchemyBtnNotReady`

- `FadeSwitchTween m_tweenAlchemyBtnReady`

- `FadeSwitchTween m_tweenAlchemyBtnCant`

- `AnimationSwitchTween m_leaveBtnAnimTween`

- `Boolean m_cachedIsInDisaster`

- `ForecastStatus m_cachedForecastStatus`

- `UIStateFinder m_stateFinder`

- `String m_tipsStartAlchemyBtnNotReady`


## Properties

- `RoguelikeRewardStyle rewardUiStyle`


## Methods

- `RoguelikeRewardStyle get_rewardUiStyle()`

- `Void set_rewardUiStyle(RoguelikeRewardStyle)`

- `Void ResetViewSeqCache()`

- `Void _InitIfNot()`

- `Void EventOnLeaveBtnClick()`

- `Void EventOnCancelLeaveClick()`

- `Void EventOnStartAlchemyBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyImplView : DataBinder`1
{
	private RL04AlchemyForecastView _forecastView; // 0x20
	private RL04AlchemySlotListView _slotListView; // 0x28
	private RL04AlchemyFragmentStorageView _fragmentStorageView; // 0x30
	private CanvasGroup _canvasAlchemyBtnNotReady; // 0x38
	private CanvasGroup _canvasAlchemyBtnReady; // 0x40
	private CanvasGroup _canvasAlchemyBtnCant; // 0x48
	private GameObject _objLeaveBtnOpeningBlock; // 0x50
	private UIAnimationLocation _leaveBtnAnim; // 0x58
	private CanvasGroup _canvasAlchemyTips; // 0x68
	private Text _txtTipsAlchemy; // 0x70
	private Text _txtTipsAlchemy1; // 0x78
	private RL04AlchemyResultView _resultView; // 0x80
	private RoguelikeRewardStyle <rewardUiStyle>k__BackingField; // 0x88
	private Boolean m_isInited; // 0x90
	private String m_topicId; // 0x98
	private FadeSwitchTween m_tweenAlchemyTips; // 0xa0
	private FadeSwitchTween m_tweenAlchemyBtnNotReady; // 0xa8
	private FadeSwitchTween m_tweenAlchemyBtnReady; // 0xb0
	private FadeSwitchTween m_tweenAlchemyBtnCant; // 0xb8
	private AnimationSwitchTween m_leaveBtnAnimTween; // 0xc0
	private Boolean m_cachedIsInDisaster; // 0xc8
	private ForecastStatus m_cachedForecastStatus; // 0xcc
	private UIStateFinder m_stateFinder; // 0xd0
	private String m_tipsStartAlchemyBtnNotReady; // 0xe0
	private static DelegateBridge __Hotfix0_get_rewardUiStyle; // 0x0
	private static DelegateBridge __Hotfix0_set_rewardUiStyle; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_ResetViewSeqCache; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_EventOnLeaveBtnClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnCancelLeaveClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnStartAlchemyBtnClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public RoguelikeRewardStyle rewardUiStyle { get; set; }

	// RVA: 0x2b09fb4 VA: 0x7595121fb4
	public RoguelikeRewardStyle get_rewardUiStyle() { }
	// RVA: 0x2afb9c4 VA: 0x75951139c4
	public Void set_rewardUiStyle(RoguelikeRewardStyle value) { }
	// RVA: 0x2b0a01c VA: 0x759512201c
	public override Void OnValueChanged(RoguelikeAlchemyImplViewModelProperty property) { }
	// RVA: 0x2afb69c VA: 0x759511369c
	public Void ResetViewSeqCache() { }
	// RVA: 0x2b0a390 VA: 0x7595122390
	private Void _InitIfNot() { }
	// RVA: 0x2b0a878 VA: 0x7595122878
	public Void EventOnLeaveBtnClick() { }
	// RVA: 0x2b0a91c VA: 0x759512291c
	public Void EventOnCancelLeaveClick() { }
	// RVA: 0x2b0a9c0 VA: 0x75951229c0
	public Void EventOnStartAlchemyBtnClick() { }
	// RVA: 0x2b0ab4c VA: 0x7595122b4c
	public Void .ctor() { }
}
```