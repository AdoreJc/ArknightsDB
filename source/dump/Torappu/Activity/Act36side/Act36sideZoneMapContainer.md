# Act36sideZoneMapContainer

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `InertiaScrollViewPager _viewPager`

- `SimpleLayoutContent _content`

- `RectTransform _rootPanel`

- `SimpleLayoutContent _backViewContent`

- `RectTransform _rectTransFront`

- `RectTransform _rectTransBack`

- `RectTransform _rectTransLine`

- `CanvasGroup _lineCanvasGroup`

- `Act36sideZoneMapContainerFocusView _focusView`

- `Act36sideZoneMapContainerArrowView _arrowLeft`

- `Act36sideZoneMapContainerArrowView _arrowRight`

- `Act36sideZoneMapCardLineView _linePrefab`

- `Single _minFlingSpd`

- `Single _maxFlingSpd`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Action m_onClosePreview`

- `Adapter m_adapter`

- `BackAdapter m_backAdapter`

- `FadeSwitchTween m_lineFade`

- `UILayoutDimensionListener m_dimensionListener`

- `Boolean m_isDragging`

- `Act36sideZoneMapCardHolder m_zoneMapPrefab`

- `ZoneViewModel m_cachedZoneModel`

- `String m_zoneMapAssetPathCache`

- `String m_currentZoneId`

- `String m_focusedStageId`

- `Int32 m_focusIndex`

- `Int32 m_cachedArrowNextIndex`

- `Int32 m_cachedUnlockedCardCheckCode`


## Methods

- `Void Update()`

- `Void _InitIfNot()`

- `Void _InitViewPager()`

- `Void _PlayOnGear()`

- `Void _PlayOnGearLock()`

- `Void _OnScrollPagerStateChanged(State)`

- `Void _OnDragging()`

- `Void _OnPageChangeEnd(Single, Boolean)`

- `Void _OnPageChangeBegin(Single)`

- `Void _OnUpdateFocusPage(Single)`

- `Void _OnUpdateArrow(Single)`

- `Void _OnLeftArrowClick()`

- `Void _OnRightArrowClick()`

- `Void _OnClosePreview()`

- `Void _OnCardClick(Int32)`

- `Void _OnStageClick(String)`

- `Void _RenderFocus(Int32, Boolean)`

- `Void _MoveToDefault(String)`

- `Void _MoveToRoundStableIfNesessary()`

- `Void _MoveToStable(Int32)`

- `Void _MoveToStage(String)`

- `Void _MoveToIndex(Int32, Boolean)`

- `Void _OnPostLayout()`

- `Void _SetUp(ZoneViewModel)`

- `Boolean _SetupZoneMapIfNeeded(ZoneViewModel)`

- `Boolean _TryCollectUnlockedCardCount(Act36sideZoneMapCardHolder, ZoneViewModel)`

- `Void _GenerateLineIfNessesary()`

- `Void _RenderLine()`

- `Void OnDestroy()`

- `Void _ClearCachedMap()`

- `Void _ClearUpdateCache()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideZoneMapContainer : StageCustomZoneContainer
{
	private const Int32 MAX_CHECK_CODE_BIAS_BIT_NUM; // 0x0
	private const Boolean SHOW_LINE_WHEN_DRAG; // 0x0
	private InertiaScrollViewPager _viewPager; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private RectTransform _rootPanel; // 0x28
	private SimpleLayoutContent _backViewContent; // 0x30
	private RectTransform _rectTransFront; // 0x38
	private RectTransform _rectTransBack; // 0x40
	private RectTransform _rectTransLine; // 0x48
	private CanvasGroup _lineCanvasGroup; // 0x50
	private Act36sideZoneMapContainerFocusView _focusView; // 0x58
	private Act36sideZoneMapContainerArrowView _arrowLeft; // 0x60
	private Act36sideZoneMapContainerArrowView _arrowRight; // 0x68
	private Act36sideZoneMapCardLineView _linePrefab; // 0x70
	private Single _minFlingSpd; // 0x78
	private Single _maxFlingSpd; // 0x7c
	private Boolean m_isInited; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private Action`1 m_onStageSelect; // 0x98
	private Action`1 m_onMapNotFound; // 0xa0
	private Action`1 m_onMapLoadFinish; // 0xa8
	private Action`1 m_onSpecialStageReward; // 0xb0
	private Action m_onClosePreview; // 0xb8
	private Adapter m_adapter; // 0xc0
	private BackAdapter m_backAdapter; // 0xc8
	private FadeSwitchTween m_lineFade; // 0xd0
	private UILayoutDimensionListener m_dimensionListener; // 0xd8
	private Dictionary`2 m_lineViews; // 0xe0
	private Boolean m_isDragging; // 0xe8
	private Act36sideZoneMapCardHolder m_zoneMapPrefab; // 0xf0
	private ZoneViewModel m_cachedZoneModel; // 0xf8
	private String m_zoneMapAssetPathCache; // 0x100
	private String m_currentZoneId; // 0x108
	private String m_focusedStageId; // 0x110
	private Int32 m_focusIndex; // 0x118
	private Int32 m_cachedArrowNextIndex; // 0x11c
	private Int32 m_cachedUnlockedCardCheckCode; // 0x120
	private List`1 m_unlockedCardPrefabs; // 0x128
	private Dictionary`2 m_unlockedCardLine; // 0x130
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__InitViewPager; // 0x10
	private static DelegateBridge __Hotfix0__PlayOnGear; // 0x18
	private static DelegateBridge __Hotfix0__PlayOnGearLock; // 0x20
	private static DelegateBridge __Hotfix0__OnScrollPagerStateChanged; // 0x28
	private static DelegateBridge __Hotfix0__OnDragging; // 0x30
	private static DelegateBridge __Hotfix0__OnPageChangeEnd; // 0x38
	private static DelegateBridge __Hotfix0__OnPageChangeBegin; // 0x40
	private static DelegateBridge __Hotfix0__OnUpdateFocusPage; // 0x48
	private static DelegateBridge __Hotfix0__OnUpdateArrow; // 0x50
	private static DelegateBridge __Hotfix0__OnLeftArrowClick; // 0x58
	private static DelegateBridge __Hotfix0__OnRightArrowClick; // 0x60
	private static DelegateBridge __Hotfix0__OnClosePreview; // 0x68
	private static DelegateBridge __Hotfix0__OnCardClick; // 0x70
	private static DelegateBridge __Hotfix0__OnStageClick; // 0x78
	private static DelegateBridge __Hotfix0_Init; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x88
	private static DelegateBridge __Hotfix0__RenderFocus; // 0x90
	private static DelegateBridge __Hotfix0__MoveToDefault; // 0x98
	private static DelegateBridge __Hotfix0__MoveToRoundStableIfNesessary; // 0xa0
	private static DelegateBridge __Hotfix0__MoveToStable; // 0xa8
	private static DelegateBridge __Hotfix0__MoveToStage; // 0xb0
	private static DelegateBridge __Hotfix0__MoveToIndex; // 0xb8
	private static DelegateBridge __Hotfix0__OnPostLayout; // 0xc0
	private static DelegateBridge __Hotfix0__SetUp; // 0xc8
	private static DelegateBridge __Hotfix0__SetupZoneMapIfNeeded; // 0xd0
	private static DelegateBridge __Hotfix0__TryCollectUnlockedCardCount; // 0xd8
	private static DelegateBridge __Hotfix0__GenerateLineIfNessesary; // 0xe0
	private static DelegateBridge __Hotfix0__RenderLine; // 0xe8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xf0
	private static DelegateBridge __Hotfix0__ClearCachedMap; // 0xf8
	private static DelegateBridge __Hotfix0__ClearUpdateCache; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108


	// RVA: 0x324aad8 VA: 0x7595862ad8
	private Void Update() { }
	// RVA: 0x324ade4 VA: 0x7595862de4
	private Void _InitIfNot() { }
	// RVA: 0x324b07c VA: 0x759586307c
	private Void _InitViewPager() { }
	// RVA: 0x324b290 VA: 0x7595863290
	private Void _PlayOnGear() { }
	// RVA: 0x324b338 VA: 0x7595863338
	private Void _PlayOnGearLock() { }
	// RVA: 0x324b3e0 VA: 0x75958633e0
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x324b4c4 VA: 0x75958634c4
	private Void _OnDragging() { }
	// RVA: 0x324b538 VA: 0x7595863538
	private Void _OnPageChangeEnd(Single index, Boolean fastMode) { }
	// RVA: 0x324b6ec VA: 0x75958636ec
	private Void _OnPageChangeBegin(Single index) { }
	// RVA: 0x324ad44 VA: 0x7595862d44
	private Void _OnUpdateFocusPage(Single index) { }
	// RVA: 0x324b830 VA: 0x7595863830
	private Void _OnUpdateArrow(Single index) { }
	// RVA: 0x324bc10 VA: 0x7595863c10
	private Void _OnLeftArrowClick() { }
	// RVA: 0x324be5c VA: 0x7595863e5c
	private Void _OnRightArrowClick() { }
	// RVA: 0x324b7ac VA: 0x75958637ac
	private Void _OnClosePreview() { }
	// RVA: 0x324c01c VA: 0x759586401c
	private Void _OnCardClick(Int32 index) { }
	// RVA: 0x324c0d4 VA: 0x75958640d4
	private Void _OnStageClick(String stageId) { }
	// RVA: 0x324c2f8 VA: 0x75958642f8
	public override Void Init(Param initParam, StageCustomZoneContainerHolder holder) { }
	// RVA: 0x324c3e8 VA: 0x75958643e8
	public override Void Render(ZoneViewModel model) { }
	// RVA: 0x324b9d8 VA: 0x75958639d8
	private Void _RenderFocus(Int32 focusIndex, Boolean fastMode) { }
	// RVA: 0x324c9a4 VA: 0x75958649a4
	private Void _MoveToDefault(String stageId) { }
	// RVA: 0x324cbe4 VA: 0x7595864be4
	private Void _MoveToRoundStableIfNesessary() { }
	// RVA: 0x324cb3c VA: 0x7595864b3c
	private Void _MoveToStable(Int32 index) { }
	// RVA: 0x324cd28 VA: 0x7595864d28
	private Void _MoveToStage(String stageId) { }
	// RVA: 0x324bdb4 VA: 0x7595863db4
	private Void _MoveToIndex(Int32 index, Boolean fastMode) { }
	// RVA: 0x324ce20 VA: 0x7595864e20
	private Void _OnPostLayout() { }
	// RVA: 0x324c6f8 VA: 0x75958646f8
	private Void _SetUp(ZoneViewModel model) { }
	// RVA: 0x324d38c VA: 0x759586538c
	private Boolean _SetupZoneMapIfNeeded(ZoneViewModel model) { }
	// RVA: 0x324d624 VA: 0x7595865624
	private Boolean _TryCollectUnlockedCardCount(Act36sideZoneMapCardHolder zoneMap, ZoneViewModel model) { }
	// RVA: 0x324ce88 VA: 0x7595864e88
	private Void _GenerateLineIfNessesary() { }
	// RVA: 0x324db88 VA: 0x7595865b88
	private Void _RenderLine() { }
	// RVA: 0x324ddb0 VA: 0x7595865db0
	private Void OnDestroy() { }
	// RVA: 0x324c510 VA: 0x7595864510
	private Void _ClearCachedMap() { }
	// RVA: 0x324c654 VA: 0x7595864654
	private Void _ClearUpdateCache() { }
	// RVA: 0x324de18 VA: 0x7595865e18
	public Void .ctor() { }
}
```