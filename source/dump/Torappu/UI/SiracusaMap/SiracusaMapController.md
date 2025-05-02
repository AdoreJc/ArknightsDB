# SiracusaMapController

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaMapZoneMapHolder _zoneMapHolder`

- `RectTransform _charCardContainer`

- `RectTransform _bigMapNavigationContainer`

- `RectTransform _smallMapStageDtailContainer`

- `SiracusaCharCardView _charCardViewPrefab`

- `SiracusaMapNavigationView _bigMapNavigationViewPrefab`

- `SiracusaMapStageDetailView _smallMapStageDetailViewPrefab`

- `SiracusaMapPointInfoHolder _pointInfoViewHolder`

- `SiracusaMapCoinView _coinView`

- `RectTransform _storyPreviewViewContainer`

- `SiracusaMapStageStoryPreviewView _storyPreviewViewPrefab`

- `SiracusaMapStagePreviewView _stagePreviewView`

- `GameObject _mapTips`

- `Image _previewImg`

- `Image _backMask`

- `SiracusaCharCardView m_charCardView`

- `SiracusaMapNavigationView m_bigMapNavigationView`

- `SiracusaMapStageDetailView m_smallMapStageDetailView`

- `SiracusaMapStageStoryPreviewView m_storyStagePreviewView`

- `SiracusaMapPanelMapProperty m_panelMapProperty`

- `Coroutine m_bubbleCoroutine`

- `AutoPackSpriteHub m_charCardItemSpriteHub`

- `AutoPackSpriteHub m_charCardSpriteHub`

- `AutoPackSpriteHub m_charCardItalyNameSpriteHub`

- `AutoPackSpriteHub m_areaPointIconSpriteHub`

- `AutoPackSpriteHub m_taskCharAvatarSpriteHub`

- `String m_groupId`

- `Boolean m_hasInited`

- `Boolean m_isRetro`


## Properties

- `String groupId`

- `Boolean isRetro`

- `SiracusaMapPanelMapProperty panelMapProperty`

- `Image backMask`

- `Image previewImg`

- `GameObject mapTips`

- `Boolean hasInited`


## Methods

- `String get_groupId()`

- `Boolean get_isRetro()`

- `SiracusaMapPanelMapProperty get_panelMapProperty()`

- `Image get_backMask()`

- `Image get_previewImg()`

- `GameObject get_mapTips()`

- `Boolean get_hasInited()`

- `Void _LoadSpriteHubs(UIPage)`

- `AutoPackSpriteHub GetCharCardItemSpriteHub()`

- `AutoPackSpriteHub GetCharCardSpriteHub()`

- `AutoPackSpriteHub GetCharCardItalyNameSpriteHub()`

- `AutoPackSpriteHub GetAreaPointIconSpriteHub()`

- `AutoPackSpriteHub GetTaskCharAvatarCharHub()`

- `Boolean CheckIfInBigMapViewAndHandle()`

- `Boolean _IsSelectingStage()`

- `Boolean _IsInSmallMapState()`

- `Void _SwitchToBigMapState()`

- `Void _TryUnselectPoint(Boolean)`

- `Void _TryUnselectNaviDetailStage()`

- `Void UpdateCharCardProp()`

- `Void UpdateReviewCharCard(String)`

- `SiracusaMapChatParam GetSiracusaMapChatParam()`

- `Boolean CanTaskRingTakeReward()`

- `Void ShowToast(String)`

- `Param GeneRecoverPageParam(String, String)`

- `Void NotifyAreaUnlock(String)`

- `Void TryToUnselectNode(Boolean)`

- `Void _InitZoneMapView()`

- `Void _OnMapNodeClicked(SiracusaMapMapNodeViewModel)`

- `Void _OnMapBlankClicked()`

- `Void _InitCharCardView()`

- `Void _OnTaskClick(String, String)`

- `Void _OnCharCardBagClick()`

- `Void _OnCharChangeClick()`

- `Void _ShowBubble()`

- `Void _SelectTaskRing(Int32)`

- `Void _CloseBubbleAfterDelay()`

- `Void _InitNavigationView()`

- `Void _OnNavigationSelect(String, NavigationType)`

- `Void _OnNavigationDetailStageItemSelect(String)`

- `Void _OnNavigationStageItemUnSelect()`

- `Void _NavigationDetailStageItemSelect(String)`

- `Boolean _CheckIfNavigationDetailStageCurSelectNothing()`

- `Void _InitStoryStagePreviewView()`

- `Void _OnPlayStory(SiracusaMapStageDetailInfoViewModel)`

- `UIPageControllerParam _GeneRecoverParamWithStory(SiracusaMapController, Boolean, String, String, String, StoryOnlyStartBattleResponse)`

- `Void _InitStagePreviewView()`

- `Void _OnPreviewBeHard(String)`

- `Void _OnPreviewBeNormal(String)`

- `Void _OnRewardClick(String)`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapController : PageSingleComponent
{
	private SiracusaMapZoneMapHolder _zoneMapHolder; // 0x20
	private RectTransform _charCardContainer; // 0x28
	private RectTransform _bigMapNavigationContainer; // 0x30
	private RectTransform _smallMapStageDtailContainer; // 0x38
	private SiracusaCharCardView _charCardViewPrefab; // 0x40
	private SiracusaMapNavigationView _bigMapNavigationViewPrefab; // 0x48
	private SiracusaMapStageDetailView _smallMapStageDetailViewPrefab; // 0x50
	private SiracusaMapPointInfoHolder _pointInfoViewHolder; // 0x58
	private SiracusaMapCoinView _coinView; // 0x60
	private RectTransform _storyPreviewViewContainer; // 0x68
	private SiracusaMapStageStoryPreviewView _storyPreviewViewPrefab; // 0x70
	private SiracusaMapStagePreviewView _stagePreviewView; // 0x78
	private GameObject _mapTips; // 0x80
	private Image _previewImg; // 0x88
	private Image _backMask; // 0x90
	private SiracusaCharCardView m_charCardView; // 0x98
	private SiracusaMapNavigationView m_bigMapNavigationView; // 0xa0
	private SiracusaMapStageDetailView m_smallMapStageDetailView; // 0xa8
	private SiracusaMapStageStoryPreviewView m_storyStagePreviewView; // 0xb0
	private SiracusaMapPanelMapProperty m_panelMapProperty; // 0xb8
	private Coroutine m_bubbleCoroutine; // 0xc0
	private AutoPackSpriteHub m_charCardItemSpriteHub; // 0xc8
	private AutoPackSpriteHub m_charCardSpriteHub; // 0xd0
	private AutoPackSpriteHub m_charCardItalyNameSpriteHub; // 0xd8
	private AutoPackSpriteHub m_areaPointIconSpriteHub; // 0xe0
	private AutoPackSpriteHub m_taskCharAvatarSpriteHub; // 0xe8
	private String m_groupId; // 0xf0
	private Boolean m_hasInited; // 0xf8
	private Boolean m_isRetro; // 0xf9
	private static DelegateBridge __Hotfix0_get_groupId; // 0x0
	private static DelegateBridge __Hotfix0_get_isRetro; // 0x8
	private static DelegateBridge __Hotfix0_get_panelMapProperty; // 0x10
	private static DelegateBridge __Hotfix0_get_backMask; // 0x18
	private static DelegateBridge __Hotfix0_get_previewImg; // 0x20
	private static DelegateBridge __Hotfix0_get_mapTips; // 0x28
	private static DelegateBridge __Hotfix0_get_hasInited; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge __Hotfix0__LoadSpriteHubs; // 0x48
	private static DelegateBridge __Hotfix0_GetCharCardItemSpriteHub; // 0x50
	private static DelegateBridge __Hotfix0_GetCharCardSpriteHub; // 0x58
	private static DelegateBridge __Hotfix0_GetCharCardItalyNameSpriteHub; // 0x60
	private static DelegateBridge __Hotfix0_GetAreaPointIconSpriteHub; // 0x68
	private static DelegateBridge __Hotfix0_GetTaskCharAvatarCharHub; // 0x70
	private static DelegateBridge __Hotfix0_CheckIfInBigMapViewAndHandle; // 0x78
	private static DelegateBridge __Hotfix0__IsSelectingStage; // 0x80
	private static DelegateBridge __Hotfix0__IsInSmallMapState; // 0x88
	private static DelegateBridge __Hotfix0__SwitchToBigMapState; // 0x90
	private static DelegateBridge __Hotfix0__TryUnselectPoint; // 0x98
	private static DelegateBridge __Hotfix0__TryUnselectNaviDetailStage; // 0xa0
	private static DelegateBridge __Hotfix0_UpdateCharCardProp; // 0xa8
	private static DelegateBridge __Hotfix0_UpdateReviewCharCard; // 0xb0
	private static DelegateBridge __Hotfix0_GetSiracusaMapChatParam; // 0xb8
	private static DelegateBridge __Hotfix0_CanTaskRingTakeReward; // 0xc0
	private static DelegateBridge __Hotfix0_ShowToast; // 0xc8
	private static DelegateBridge __Hotfix0_GeneRecoverPageParam; // 0xd0
	private static DelegateBridge __Hotfix0_NotifyAreaUnlock; // 0xd8
	private static DelegateBridge __Hotfix0_TryToUnselectNode; // 0xe0
	private static DelegateBridge __Hotfix0__InitZoneMapView; // 0xe8
	private static DelegateBridge __Hotfix0__OnMapNodeClicked; // 0xf0
	private static DelegateBridge __Hotfix0__OnMapBlankClicked; // 0xf8
	private static DelegateBridge __Hotfix0__InitCharCardView; // 0x100
	private static DelegateBridge __Hotfix0__OnTaskClick; // 0x108
	private static DelegateBridge __Hotfix0__OnCharCardBagClick; // 0x110
	private static DelegateBridge __Hotfix0__OnCharChangeClick; // 0x118
	private static DelegateBridge __Hotfix0__ShowBubble; // 0x120
	private static DelegateBridge __Hotfix0__SelectTaskRing; // 0x128
	private static DelegateBridge __Hotfix0__CloseBubbleAfterDelay; // 0x130
	private static DelegateBridge __Hotfix0__InitNavigationView; // 0x138
	private static DelegateBridge __Hotfix0__OnNavigationSelect; // 0x140
	private static DelegateBridge __Hotfix0__OnNavigationDetailStageItemSelect; // 0x148
	private static DelegateBridge __Hotfix0__OnNavigationStageItemUnSelect; // 0x150
	private static DelegateBridge __Hotfix0__NavigationDetailStageItemSelect; // 0x158
	private static DelegateBridge __Hotfix0__CheckIfNavigationDetailStageCurSelectNothing; // 0x160
	private static DelegateBridge __Hotfix0__InitStoryStagePreviewView; // 0x168
	private static DelegateBridge __Hotfix0__OnPlayStory; // 0x170
	private static DelegateBridge __Hotfix0__GeneRecoverParamWithStory; // 0x178
	private static DelegateBridge __Hotfix0__InitStagePreviewView; // 0x180
	private static DelegateBridge __Hotfix0__OnPreviewBeHard; // 0x188
	private static DelegateBridge __Hotfix0__OnPreviewBeNormal; // 0x190
	private static DelegateBridge __Hotfix0__OnRewardClick; // 0x198
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1a0

	public String groupId { get; }
	public Boolean isRetro { get; }
	public SiracusaMapPanelMapProperty panelMapProperty { get; }
	public Image backMask { get; }
	public Image previewImg { get; }
	public GameObject mapTips { get; }
	public Boolean hasInited { get; }

	// RVA: 0x23fff40 VA: 0x7594a17f40
	public String get_groupId() { }
	// RVA: 0x23fffa8 VA: 0x7594a17fa8
	public Boolean get_isRetro() { }
	// RVA: 0x23fe344 VA: 0x7594a16344
	public SiracusaMapPanelMapProperty get_panelMapProperty() { }
	// RVA: 0x23fe20c VA: 0x7594a1620c
	public Image get_backMask() { }
	// RVA: 0x23fe274 VA: 0x7594a16274
	public Image get_previewImg() { }
	// RVA: 0x23fe2dc VA: 0x7594a162dc
	public GameObject get_mapTips() { }
	// RVA: 0x2400010 VA: 0x7594a18010
	public Boolean get_hasInited() { }
	// RVA: 0x2400078 VA: 0x7594a18078
	protected override Void OnCreate() { }
	// RVA: 0x24011dc VA: 0x7594a191dc
	protected override Void OnDestroy() { }
	// RVA: 0x2400514 VA: 0x7594a18514
	private Void _LoadSpriteHubs(UIPage page) { }
	// RVA: 0x2401248 VA: 0x7594a19248
	public AutoPackSpriteHub GetCharCardItemSpriteHub() { }
	// RVA: 0x24012b0 VA: 0x7594a192b0
	public AutoPackSpriteHub GetCharCardSpriteHub() { }
	// RVA: 0x2401318 VA: 0x7594a19318
	public AutoPackSpriteHub GetCharCardItalyNameSpriteHub() { }
	// RVA: 0x2401380 VA: 0x7594a19380
	public AutoPackSpriteHub GetAreaPointIconSpriteHub() { }
	// RVA: 0x24013e8 VA: 0x7594a193e8
	public AutoPackSpriteHub GetTaskCharAvatarCharHub() { }
	// RVA: 0x2401450 VA: 0x7594a19450
	public Boolean CheckIfInBigMapViewAndHandle() { }
	// RVA: 0x24014f0 VA: 0x7594a194f0
	private Boolean _IsSelectingStage() { }
	// RVA: 0x24016c8 VA: 0x7594a196c8
	private Boolean _IsInSmallMapState() { }
	// RVA: 0x2401760 VA: 0x7594a19760
	private Void _SwitchToBigMapState() { }
	// RVA: 0x24015bc VA: 0x7594a195bc
	private Void _TryUnselectPoint(Boolean needChangeShowSelectedFlag) { }
	// RVA: 0x2401820 VA: 0x7594a19820
	private Void _TryUnselectNaviDetailStage() { }
	// RVA: 0x24018d8 VA: 0x7594a198d8
	public Void UpdateCharCardProp() { }
	// RVA: 0x2401998 VA: 0x7594a19998
	public Void UpdateReviewCharCard(String charCardId) { }
	// RVA: 0x2401a88 VA: 0x7594a19a88
	public SiracusaMapChatParam GetSiracusaMapChatParam() { }
	// RVA: 0x2401c34 VA: 0x7594a19c34
	public Boolean CanTaskRingTakeReward() { }
	// RVA: 0x2401cfc VA: 0x7594a19cfc
	public Void ShowToast(String toast) { }
	// RVA: 0x2401f18 VA: 0x7594a19f18
	public Param GeneRecoverPageParam(String storyId, String pointId) { }
	// RVA: 0x2401fd4 VA: 0x7594a19fd4
	public Void NotifyAreaUnlock(String areaId) { }
	// RVA: 0x23fdeb4 VA: 0x7594a15eb4
	public Void TryToUnselectNode(Boolean needChangeShowSelectedFlag) { }
	// RVA: 0x24006b4 VA: 0x7594a186b4
	private Void _InitZoneMapView() { }
	// RVA: 0x24020d0 VA: 0x7594a1a0d0
	private Void _OnMapNodeClicked(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x240256c VA: 0x7594a1a56c
	private Void _OnMapBlankClicked() { }
	// RVA: 0x2400a74 VA: 0x7594a18a74
	private Void _InitCharCardView() { }
	// RVA: 0x24021f4 VA: 0x7594a1a1f4
	private Void _OnTaskClick(String taskRingId, String taskId) { }
	// RVA: 0x2402788 VA: 0x7594a1a788
	private Void _OnCharCardBagClick() { }
	// RVA: 0x2402a84 VA: 0x7594a1aa84
	private Void _OnCharChangeClick() { }
	// RVA: 0x2402c20 VA: 0x7594a1ac20
	private Void _ShowBubble() { }
	// RVA: 0x2402e10 VA: 0x7594a1ae10
	private Void _SelectTaskRing(Int32 index) { }
	// RVA: 0x2402cf4 VA: 0x7594a1acf4
	private Void _CloseBubbleAfterDelay() { }
	// RVA: 0x24007f8 VA: 0x7594a187f8
	private Void _InitNavigationView() { }
	// RVA: 0x2402ee4 VA: 0x7594a1aee4
	private Void _OnNavigationSelect(String entryId, NavigationType entryType) { }
	// RVA: 0x240301c VA: 0x7594a1b01c
	private Void _OnNavigationDetailStageItemSelect(String itemId) { }
	// RVA: 0x2403190 VA: 0x7594a1b190
	private Void _OnNavigationStageItemUnSelect() { }
	// RVA: 0x240309c VA: 0x7594a1b09c
	private Void _NavigationDetailStageItemSelect(String itemId) { }
	// RVA: 0x2403230 VA: 0x7594a1b230
	private Boolean _CheckIfNavigationDetailStageCurSelectNothing() { }
	// RVA: 0x2400fac VA: 0x7594a18fac
	private Void _InitStoryStagePreviewView() { }
	// RVA: 0x24032d8 VA: 0x7594a1b2d8
	private Void _OnPlayStory(SiracusaMapStageDetailInfoViewModel data) { }
	// RVA: 0x24036e0 VA: 0x7594a1b6e0
	private UIPageControllerParam _GeneRecoverParamWithStory(SiracusaMapController controller, Boolean isFirstPassedStage, String zoneId, String stageId, String pointId, StoryOnlyStartBattleResponse response) { }
	// RVA: 0x2400cd8 VA: 0x7594a18cd8
	private Void _InitStagePreviewView() { }
	// RVA: 0x2403bc8 VA: 0x7594a1bbc8
	private Void _OnPreviewBeHard(String _) { }
	// RVA: 0x2403cac VA: 0x7594a1bcac
	private Void _OnPreviewBeNormal(String _) { }
	// RVA: 0x2403d8c VA: 0x7594a1bd8c
	private Void _OnRewardClick(String _) { }
	// RVA: 0x2403f48 VA: 0x7594a1bf48
	public Void .ctor() { }
	// RVA: 0x2403ff8 VA: 0x7594a1bff8
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2404000 VA: 0x7594a1c000
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```