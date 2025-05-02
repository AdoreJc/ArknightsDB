# SandboxV2DungeonCrossDayView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `AnimationWrapper _animWrapper`

- `GameObject _objCalView`

- `Text _txtSurviveDayTitle`

- `Text _txtSurviveDay`

- `Text _txtTotalScoreTitle`

- `Text _txtSurviveTotalScore`

- `GameObject _objTechMax`

- `GameObject _objTechCount`

- `Text _txtTechCount`

- `Image _imgTechProgress`

- `GameObject _objShopMax`

- `GameObject _objShopCount`

- `Text _txtShopCount`

- `GameObject _objCalcContinueClickArea`

- `CanvasGroup _canvasContinueTxt`

- `GameObject _objCrossDayDetailView`

- `ScrollRect _dayDetailScrollRect`

- `GameObject _objHasReadRightTop`

- `GameObject _objHasSaveRightTop`

- `GameObject _objSeasonInfo`

- `Text _txtSeasonTitle`

- `UIAtlasImage _imgSeasonLineLeft`

- `UIAtlasImage _imgSeasonLineRight`

- `Text _txtSeasonDetail`

- `Text _txtDayBefore`

- `Text _txtDayAfter`

- `GameObject _objDayTotalRift`

- `Text _txtDayTotalRift`

- `GameObject _objDayTextNormal`

- `Text _txtDayTextNormal`

- `GameObject _objDayIconNormal`

- `GameObject _objDayIconRift`

- `GameObject _objDayIconChallenge`

- `SimpleLayoutContent _dayApListContent`

- `GameObject _objDaySeasonInfo`

- `GameObject _objDayRiftInfo`

- `GameObject _objDayChallengeInfo`

- `RectTransform _daySeasonAngle`

- `GameObject _objExpedition`

- `SandboxV2DungeonCrossDayExpeditionSquadsView _expeditionSquadsView`

- `SimpleLayoutContent _expeditionRewardContent`

- `SimpleLayoutContent _baseProductRewardContent`

- `GameObject _objBaseProduct`

- `GameObject _objSupply`

- `Text _txtSupplySquadCount`

- `Text _txtSupplyPeriod`

- `GameObject _objSupplyBuffEnough`

- `Text _txtSupplyBuffEnoughTips`

- `GameObject _objSupplyBuffNotEnough`

- `Text _txtSupplyBuffNotEnoughTips`

- `Text _txtDrinkHasCount`

- `Color _colDrinkHasCountEnough`

- `Color _colDrinkHasCountLess`

- `GameObject _objDrinkNotEnoughTips`

- `Text _txtDrinkNotEnoughTips`

- `Single _rewardItemCardScale`

- `GameObject _objNormalDayContinueBtn`

- `GameObject _objSettleDayContinueBtn`

- `CanvasGroup _scrollBlocker`

- `CanvasGroup _canvasBtnExit`

- `RectTransform _backTransform`

- `Button _btnSupplyGo`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `ApItemListAdapter m_adapterDayApItemList`

- `RewardItemListAdapter m_adapterMissionRewardList`

- `RewardItemListAdapter m_adapterBaseRewardList`

- `SandboxV2DungeonCrossDayModel m_model`

- `Tween m_animTween`

- `UIPage m_page`

- `Boolean m_isSettleDay`

- `FadeSwitchTween m_tweenBtnExit`

- `Coroutine m_coAutoCloseDailyPanel`

- `TweenWrapper m_scrollAutoMoveTween`

- `TweenWrapper m_seasonAngleChangeTween`

- `Boolean m_isScreenClicked`

- `TweenWrapper m_techProgressTween`

- `FadeSwitchTween m_tweenCanvasCalcContinueTxt`

- `Boolean m_isDayInfoEnterAnimPlayed`


## Methods

- `Void Init(SandboxV2DungeonCrossDayPage)`

- `Void _InitIfNot()`

- `Void _ShowSettleCalcPanel(SandboxV2DungeonCrossDaySettleCalcModel)`

- `Void _ShowTechProgressPart(Boolean, Single, Single, Int32)`

- `Void _ShowCalcClickAreaPart(Boolean)`

- `Boolean _IsTechTweenPlaying()`

- `Void _RefreshTechCircleCountTxt(Int32)`

- `Void _HideSettleCalcPanel()`

- `Void _ShowDayBriefInfoPart(SandboxV2DungeonCrossDayDailyModel)`

- `Void _ShowDayExpeditionInfoPart(SandboxV2DungeonCrossDayDailyModel)`

- `Void _ShowDayBaseProductInfoPart(SandboxV2DungeonCrossDayDailyModel)`

- `Void _ShowDaySupplyInfoPart(Boolean, SandboxV2DungeonCrossDaySupplyModel)`

- `Void _PlayDayInfoEnterAnim(Boolean, Boolean, Boolean)`

- `Void _ShowDayInfoPanel(SandboxV2DungeonCrossDayDailyModel, Boolean, SandboxV2DungeonCrossDaySupplyModel)`

- `IEnumerator _StartDayPanelAutoScroll(Single)`

- `Void _RefreshDayPanelAfterAutoScrollEnd()`

- `Void _ResetCoAutoCloseDailyPanel()`

- `Void _PlayDayEnterPanelTween(String, TweenCallback)`

- `Void _PlayPanelTween(String, TweenCallback)`

- `IEnumerator _CoNormalDayAutoClose()`

- `Void _OnBackPressed()`

- `Void _OnCalcPanelExitAnimComplete()`

- `Void _OnContinueNormalDay()`

- `Void EventOnDailyPanelBgClickArea()`

- `Void EventOnCalcDetailClick()`

- `Void EventOnContinueFromCalcClick()`

- `Void EventOnSupplyBtnClick()`

- `Void EventOnDrinkTipsBtnClick()`

- `Void EventOnContinueSettleDayBtnClick()`

- `Void EventOnContinueNormalDayBtnClick()`

- `Void EventOnExitDailyPanelBtnClick()`

- `Void _TryTriggerTutorial()`

- `Void _TryRaiseTutorialSignal()`

- `Single <_StartDayPanelAutoScroll>b__111_0()`

- `Void <_StartDayPanelAutoScroll>b__111_1(Single)`

- `Void <_PlayDayEnterPanelTween>b__114_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCrossDayView : DataBinder`1
{
	private const Single SEASON_AUDIO_FX_OFFSET; // 0x0
	private AnimationWrapper _animWrapper; // 0x20
	private GameObject _objCalView; // 0x28
	private Text _txtSurviveDayTitle; // 0x30
	private Text _txtSurviveDay; // 0x38
	private Text _txtTotalScoreTitle; // 0x40
	private Text _txtSurviveTotalScore; // 0x48
	private GameObject _objTechMax; // 0x50
	private GameObject _objTechCount; // 0x58
	private Text _txtTechCount; // 0x60
	private Image _imgTechProgress; // 0x68
	private GameObject _objShopMax; // 0x70
	private GameObject _objShopCount; // 0x78
	private Text _txtShopCount; // 0x80
	private GameObject _objCalcContinueClickArea; // 0x88
	private CanvasGroup _canvasContinueTxt; // 0x90
	private GameObject _objCrossDayDetailView; // 0x98
	private ScrollRect _dayDetailScrollRect; // 0xa0
	private GameObject _objHasReadRightTop; // 0xa8
	private GameObject _objHasSaveRightTop; // 0xb0
	private GameObject _objSeasonInfo; // 0xb8
	private Text _txtSeasonTitle; // 0xc0
	private UIAtlasImage _imgSeasonLineLeft; // 0xc8
	private UIAtlasImage _imgSeasonLineRight; // 0xd0
	private Text _txtSeasonDetail; // 0xd8
	private Text _txtDayBefore; // 0xe0
	private Text _txtDayAfter; // 0xe8
	private GameObject _objDayTotalRift; // 0xf0
	private Text _txtDayTotalRift; // 0xf8
	private GameObject _objDayTextNormal; // 0x100
	private Text _txtDayTextNormal; // 0x108
	private GameObject _objDayIconNormal; // 0x110
	private GameObject _objDayIconRift; // 0x118
	private GameObject _objDayIconChallenge; // 0x120
	private SimpleLayoutContent _dayApListContent; // 0x128
	private GameObject _objDaySeasonInfo; // 0x130
	private GameObject _objDayRiftInfo; // 0x138
	private GameObject _objDayChallengeInfo; // 0x140
	private RectTransform _daySeasonAngle; // 0x148
	private GameObject _objExpedition; // 0x150
	private SandboxV2DungeonCrossDayExpeditionSquadsView _expeditionSquadsView; // 0x158
	private SimpleLayoutContent _expeditionRewardContent; // 0x160
	private SimpleLayoutContent _baseProductRewardContent; // 0x168
	private GameObject _objBaseProduct; // 0x170
	private GameObject _objSupply; // 0x178
	private Text _txtSupplySquadCount; // 0x180
	private Text _txtSupplyPeriod; // 0x188
	private GameObject _objSupplyBuffEnough; // 0x190
	private Text _txtSupplyBuffEnoughTips; // 0x198
	private GameObject _objSupplyBuffNotEnough; // 0x1a0
	private Text _txtSupplyBuffNotEnoughTips; // 0x1a8
	private Text _txtDrinkHasCount; // 0x1b0
	private Color _colDrinkHasCountEnough; // 0x1b8
	private Color _colDrinkHasCountLess; // 0x1c8
	private GameObject _objDrinkNotEnoughTips; // 0x1d8
	private Text _txtDrinkNotEnoughTips; // 0x1e0
	private Single _rewardItemCardScale; // 0x1e8
	private GameObject _objNormalDayContinueBtn; // 0x1f0
	private GameObject _objSettleDayContinueBtn; // 0x1f8
	private CanvasGroup _scrollBlocker; // 0x200
	private CanvasGroup _canvasBtnExit; // 0x208
	private RectTransform _backTransform; // 0x210
	private Button _btnSupplyGo; // 0x218
	private Boolean m_isInited; // 0x220
	private UIStateFinder m_stateFinder; // 0x228
	private ApItemListAdapter m_adapterDayApItemList; // 0x238
	private RewardItemListAdapter m_adapterMissionRewardList; // 0x240
	private RewardItemListAdapter m_adapterBaseRewardList; // 0x248
	private SandboxV2DungeonCrossDayModel m_model; // 0x250
	private Tween m_animTween; // 0x258
	private UIPage m_page; // 0x260
	private Boolean m_isSettleDay; // 0x268
	private FadeSwitchTween m_tweenBtnExit; // 0x270
	private Coroutine m_coAutoCloseDailyPanel; // 0x278
	private TweenWrapper m_scrollAutoMoveTween; // 0x280
	private TweenWrapper m_seasonAngleChangeTween; // 0x288
	private Boolean m_isScreenClicked; // 0x290
	private TweenWrapper m_techProgressTween; // 0x298
	private FadeSwitchTween m_tweenCanvasCalcContinueTxt; // 0x2a0
	private Boolean m_isDayInfoEnterAnimPlayed; // 0x2a8
	private const String CALC_PANEL_ENTER; // 0x0
	private const String CALC_PANEL_EXIT; // 0x0
	private const String DAY_PANEL_ENTER_LONG; // 0x0
	private const String DAY_PANEL_ENTER_SHORT; // 0x0
	private const String DAY_PANEL_ENTER_FIRST_LONG; // 0x0
	private const Single AUTO_SCROLL_DUR_MAX; // 0x0
	private const Single AUTO_SCROLL_DUR_MIN; // 0x0
	private const Single NORMAL_DAY_AUTO_CLOSE_DELAY; // 0x0
	private const Single SEASON_ROTATE_DUR; // 0x0
	private const Single SEASON_ROTATE_DELAY; // 0x0
	private const String RIFT_TOTAL_FORMAT; // 0x0
	private const Single DAY_ENTER_ANIM_DELAY; // 0x0
	private const Single DUR_PER_ROUND_TECH; // 0x0
	private const Single TECH_PROGRESS_TWEEN_DELAY; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__ShowSettleCalcPanel; // 0x18
	private static DelegateBridge __Hotfix0__ShowTechProgressPart; // 0x20
	private static DelegateBridge __Hotfix0__ShowCalcClickAreaPart; // 0x28
	private static DelegateBridge __Hotfix0__IsTechTweenPlaying; // 0x30
	private static DelegateBridge __Hotfix0__RefreshTechCircleCountTxt; // 0x38
	private static DelegateBridge __Hotfix0__HideSettleCalcPanel; // 0x40
	private static DelegateBridge __Hotfix0__ShowDayBriefInfoPart; // 0x48
	private static DelegateBridge __Hotfix0__ShowDayExpeditionInfoPart; // 0x50
	private static DelegateBridge __Hotfix0__ShowDayBaseProductInfoPart; // 0x58
	private static DelegateBridge __Hotfix0__ShowDaySupplyInfoPart; // 0x60
	private static DelegateBridge __Hotfix0__PlayDayInfoEnterAnim; // 0x68
	private static DelegateBridge __Hotfix0__ShowDayInfoPanel; // 0x70
	private static DelegateBridge __Hotfix0__StartDayPanelAutoScroll; // 0x78
	private static DelegateBridge __Hotfix0__RefreshDayPanelAfterAutoScrollEnd; // 0x80
	private static DelegateBridge __Hotfix0__ResetCoAutoCloseDailyPanel; // 0x88
	private static DelegateBridge __Hotfix0__PlayDayEnterPanelTween; // 0x90
	private static DelegateBridge __Hotfix0__PlayPanelTween; // 0x98
	private static DelegateBridge __Hotfix0__CoNormalDayAutoClose; // 0xa0
	private static DelegateBridge __Hotfix0__OnBackPressed; // 0xa8
	private static DelegateBridge __Hotfix0__OnCalcPanelExitAnimComplete; // 0xb0
	private static DelegateBridge __Hotfix0__OnContinueNormalDay; // 0xb8
	private static DelegateBridge __Hotfix0_EventOnDailyPanelBgClickArea; // 0xc0
	private static DelegateBridge __Hotfix0_EventOnCalcDetailClick; // 0xc8
	private static DelegateBridge __Hotfix0_EventOnContinueFromCalcClick; // 0xd0
	private static DelegateBridge __Hotfix0_EventOnSupplyBtnClick; // 0xd8
	private static DelegateBridge __Hotfix0_EventOnDrinkTipsBtnClick; // 0xe0
	private static DelegateBridge __Hotfix0_EventOnContinueSettleDayBtnClick; // 0xe8
	private static DelegateBridge __Hotfix0_EventOnContinueNormalDayBtnClick; // 0xf0
	private static DelegateBridge __Hotfix0_EventOnExitDailyPanelBtnClick; // 0xf8
	private static DelegateBridge __Hotfix0__TryTriggerTutorial; // 0x100
	private static DelegateBridge __Hotfix0__TryRaiseTutorialSignal; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110


	// RVA: 0x2525db0 VA: 0x7594b3ddb0
	public Void Init(SandboxV2DungeonCrossDayPage page) { }
	// RVA: 0x2525e34 VA: 0x7594b3de34
	public override Void OnValueChanged(SandboxV2DungeonCrossDayProp property) { }
	// RVA: 0x2525fc0 VA: 0x7594b3dfc0
	private Void _InitIfNot() { }
	// RVA: 0x252630c VA: 0x7594b3e30c
	private Void _ShowSettleCalcPanel(SandboxV2DungeonCrossDaySettleCalcModel calcModel) { }
	// RVA: 0x2526958 VA: 0x7594b3e958
	private Void _ShowTechProgressPart(Boolean isTechMax, Single startProgress, Single endProgress, Int32 round) { }
	// RVA: 0x25268b8 VA: 0x7594b3e8b8
	private Void _ShowCalcClickAreaPart(Boolean show) { }
	// RVA: 0x2527368 VA: 0x7594b3f368
	private Boolean _IsTechTweenPlaying() { }
	// RVA: 0x25272b4 VA: 0x7594b3f2b4
	private Void _RefreshTechCircleCountTxt(Int32 currentCircle) { }
	// RVA: 0x2526510 VA: 0x7594b3e510
	private Void _HideSettleCalcPanel() { }
	// RVA: 0x25273e4 VA: 0x7594b3f3e4
	private Void _ShowDayBriefInfoPart(SandboxV2DungeonCrossDayDailyModel dailyModel) { }
	// RVA: 0x252796c VA: 0x7594b3f96c
	private Void _ShowDayExpeditionInfoPart(SandboxV2DungeonCrossDayDailyModel dailyModel) { }
	// RVA: 0x2527a6c VA: 0x7594b3fa6c
	private Void _ShowDayBaseProductInfoPart(SandboxV2DungeonCrossDayDailyModel dailyModel) { }
	// RVA: 0x2527b48 VA: 0x7594b3fb48
	private Void _ShowDaySupplyInfoPart(Boolean showSupplyPart, SandboxV2DungeonCrossDaySupplyModel supplyModel) { }
	// RVA: 0x2527dd8 VA: 0x7594b3fdd8
	private Void _PlayDayInfoEnterAnim(Boolean showLongAnim, Boolean isFirstDay, Boolean isRead) { }
	// RVA: 0x25265e0 VA: 0x7594b3e5e0
	private Void _ShowDayInfoPanel(SandboxV2DungeonCrossDayDailyModel dailyModel, Boolean showSupplyPart, SandboxV2DungeonCrossDaySupplyModel supplyModel) { }
	// RVA: 0x2528190 VA: 0x7594b40190
	private IEnumerator _StartDayPanelAutoScroll(Single delay) { }
	// RVA: 0x2528388 VA: 0x7594b40388
	private Void _RefreshDayPanelAfterAutoScrollEnd() { }
	// RVA: 0x25285a4 VA: 0x7594b405a4
	private Void _ResetCoAutoCloseDailyPanel() { }
	// RVA: 0x2527fa8 VA: 0x7594b3ffa8
	private Void _PlayDayEnterPanelTween(String animName, TweenCallback onTweenComplete) { }
	// RVA: 0x2527180 VA: 0x7594b3f180
	private Void _PlayPanelTween(String animName, TweenCallback onTweenComplete) { }
	// RVA: 0x2528680 VA: 0x7594b40680
	private IEnumerator _CoNormalDayAutoClose() { }
	// RVA: 0x2528754 VA: 0x7594b40754
	private Void _OnBackPressed() { }
	// RVA: 0x2528990 VA: 0x7594b40990
	private Void _OnCalcPanelExitAnimComplete() { }
	// RVA: 0x2528a44 VA: 0x7594b40a44
	private Void _OnContinueNormalDay() { }
	// RVA: 0x2528ae8 VA: 0x7594b40ae8
	public Void EventOnDailyPanelBgClickArea() { }
	// RVA: 0x2528b54 VA: 0x7594b40b54
	public Void EventOnCalcDetailClick() { }
	// RVA: 0x252883c VA: 0x7594b4083c
	public Void EventOnContinueFromCalcClick() { }
	// RVA: 0x2528bf8 VA: 0x7594b40bf8
	public Void EventOnSupplyBtnClick() { }
	// RVA: 0x2528c9c VA: 0x7594b40c9c
	public Void EventOnDrinkTipsBtnClick() { }
	// RVA: 0x2528d40 VA: 0x7594b40d40
	public Void EventOnContinueSettleDayBtnClick() { }
	// RVA: 0x2528de4 VA: 0x7594b40de4
	public Void EventOnContinueNormalDayBtnClick() { }
	// RVA: 0x25288ec VA: 0x7594b408ec
	public Void EventOnExitDailyPanelBtnClick() { }
	// RVA: 0x2528254 VA: 0x7594b40254
	private Void _TryTriggerTutorial() { }
	// RVA: 0x25284b4 VA: 0x7594b404b4
	private Void _TryRaiseTutorialSignal() { }
	// RVA: 0x2528e54 VA: 0x7594b40e54
	public Void .ctor() { }
	// RVA: 0x2528ee4 VA: 0x7594b40ee4
	private Single <_StartDayPanelAutoScroll>b__111_0() { }
	// RVA: 0x2528f00 VA: 0x7594b40f00
	private Void <_StartDayPanelAutoScroll>b__111_1(Single val) { }
	// RVA: 0x2528f1c VA: 0x7594b40f1c
	private Void <_PlayDayEnterPanelTween>b__114_0() { }
}
```