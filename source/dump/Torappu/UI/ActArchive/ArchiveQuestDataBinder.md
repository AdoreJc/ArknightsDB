# ArchiveQuestDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `CanvasGroup _canvasSelection`

- `CanvasGroup _canvasDetail`

- `GameObject _panelAvg`

- `TwoStateToggle _toggleTitleView`

- `Text _questTypeName`

- `Text _questName`

- `Text _textAvgDesc`

- `Text _textRegionName`

- `Text _textRegionNameEn`

- `SimpleLayoutContent _npcPicContent`

- `UIDynImage _imgAvgLoader`

- `GameObject _objBtnAvg`

- `GameObject _objImgAvg`

- `GameObject _panelCg`

- `GameObject _objImgCg`

- `UIDynImage _imgCgLoader`

- `Text _cgTitle`

- `Text _cgDesc`

- `CanvasGroup _arrowLeft`

- `CanvasGroup _arrowRight`

- `ArchiveQuestListView _listView`

- `UIAnimationLocation _contentAnimationLocation`

- `GameObject _objFakeFolder`

- `UIAnimationLocation _animSelectionToDetail`

- `String m_floatHubPath`

- `ArchiveQuestController m_controller`

- `NpcPicAdapter m_adapter`

- `ArchiveQuestContentAnimator m_contentAnimator`

- `Boolean m_hasInited`

- `String m_archiveId`

- `String m_cachedCgId`

- `SandboxV2ArchiveQuestType m_cachedType`

- `Int32 m_cachedFocusIndex`

- `Int32 m_previousIndex`

- `Int32 m_nextIndex`

- `UIPageFinder m_pageFinder`

- `Sequence m_sequenceDetailToSelection`

- `Sequence m_sequenceSelectiongToDetail`


## Properties

- `ArchiveQuestController controller`


## Methods

- `ArchiveQuestController get_controller()`

- `Void set_controller(ArchiveQuestController)`

- `Void _Refresh(Int32, Boolean)`

- `Void _TryPlayAnimSelectionToDetail(Int32, Boolean)`

- `Void _TryPlayAnimDetailToSelection()`

- `Void _ResetDetail()`

- `Void _RefreshIndex(Int32)`

- `Void _RefreshArrow()`

- `Void _InitIfNot()`

- `Void _RenderFocusItem()`

- `Void _RenderAVG(ArchiveQuestAVGItemModel, String)`

- `Void _RenderCG(ArchiveQuestCGItemModel)`

- `Sprite _TryLoadSpriteFromAutoPackHub(String, String)`

- `Void _OpenAvgSelectDialog(ArchiveQuestAVGItemModel)`

- `ArchiveQuestItemModel _GetSelectedItemModel()`

- `Void _OnSelectedAvg(Int32)`

- `Void _StartAvg(String)`

- `String _GetCgPath(String)`

- `Void EventOnClickLeftArrow()`

- `Void EventOnClickRightArrow()`

- `Void EventOnClickAvg()`

- `Void EventOnSelectTypeMain()`

- `Void EventOnSelectTypeSide()`

- `Void EventOnSelectTypeLocked()`

- `Void <_TryPlayAnimDetailToSelection>b__50_0()`

- `Void <_TryPlayAnimDetailToSelection>b__50_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestDataBinder : DataBinder`1
{
	private ArchiveQuestTypeBtnView[] _btnViews; // 0x20
	private CanvasGroup _canvasSelection; // 0x28
	private CanvasGroup _canvasDetail; // 0x30
	private GameObject _panelAvg; // 0x38
	private TwoStateToggle _toggleTitleView; // 0x40
	private Text _questTypeName; // 0x48
	private Text _questName; // 0x50
	private Text _textAvgDesc; // 0x58
	private Text _textRegionName; // 0x60
	private Text _textRegionNameEn; // 0x68
	private SimpleLayoutContent _npcPicContent; // 0x70
	private UIDynImage _imgAvgLoader; // 0x78
	private GameObject _objBtnAvg; // 0x80
	private GameObject _objImgAvg; // 0x88
	private GameObject _panelCg; // 0x90
	private GameObject _objImgCg; // 0x98
	private UIDynImage _imgCgLoader; // 0xa0
	private Text _cgTitle; // 0xa8
	private Text _cgDesc; // 0xb0
	private CanvasGroup _arrowLeft; // 0xb8
	private CanvasGroup _arrowRight; // 0xc0
	private ArchiveQuestListView _listView; // 0xc8
	private UIAnimationLocation _contentAnimationLocation; // 0xd0
	private GameObject _objFakeFolder; // 0xe0
	private UIAnimationLocation _animSelectionToDetail; // 0xe8
	private String m_floatHubPath; // 0xf8
	private List`1 m_npcIconIdList; // 0x100
	private Action`1 m_actionOnSelectQuestType; // 0x108
	private Action`1 m_actionOnSelectIndex; // 0x110
	private ArchiveQuestController m_controller; // 0x118
	private NpcPicAdapter m_adapter; // 0x120
	private ArchiveQuestContentAnimator m_contentAnimator; // 0x128
	private Boolean m_hasInited; // 0x130
	private String m_archiveId; // 0x138
	private String m_cachedCgId; // 0x140
	private List`1 m_cachedItems; // 0x148
	private SandboxV2ArchiveQuestType m_cachedType; // 0x150
	private Int32 m_cachedFocusIndex; // 0x154
	private Int32 m_previousIndex; // 0x158
	private Int32 m_nextIndex; // 0x15c
	private UIPageFinder m_pageFinder; // 0x160
	private Sequence m_sequenceDetailToSelection; // 0x170
	private Sequence m_sequenceSelectiongToDetail; // 0x178
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__Refresh; // 0x18
	private static DelegateBridge __Hotfix0__TryPlayAnimSelectionToDetail; // 0x20
	private static DelegateBridge __Hotfix0__TryPlayAnimDetailToSelection; // 0x28
	private static DelegateBridge __Hotfix0__ResetDetail; // 0x30
	private static DelegateBridge __Hotfix0__RefreshIndex; // 0x38
	private static DelegateBridge __Hotfix0__RefreshArrow; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0__RenderFocusItem; // 0x50
	private static DelegateBridge __Hotfix0__RenderAVG; // 0x58
	private static DelegateBridge __Hotfix0__RenderCG; // 0x60
	private static DelegateBridge __Hotfix0__TryLoadSpriteFromAutoPackHub; // 0x68
	private static DelegateBridge __Hotfix0__OpenAvgSelectDialog; // 0x70
	private static DelegateBridge __Hotfix0__GetSelectedItemModel; // 0x78
	private static DelegateBridge __Hotfix0__OnSelectedAvg; // 0x80
	private static DelegateBridge __Hotfix0__StartAvg; // 0x88
	private static DelegateBridge __Hotfix0__GetCgPath; // 0x90
	private static DelegateBridge __Hotfix0_EventOnClickLeftArrow; // 0x98
	private static DelegateBridge __Hotfix0_EventOnClickRightArrow; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnClickAvg; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnSelectTypeMain; // 0xb0
	private static DelegateBridge __Hotfix0_EventOnSelectTypeSide; // 0xb8
	private static DelegateBridge __Hotfix0_EventOnSelectTypeLocked; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public ArchiveQuestController controller { get; set; }

	// RVA: 0x3070ce8 VA: 0x7595688ce8
	public ArchiveQuestController get_controller() { }
	// RVA: 0x307070c VA: 0x759568870c
	public Void set_controller(ArchiveQuestController value) { }
	// RVA: 0x3070fc0 VA: 0x7595688fc0
	public override Void OnValueChanged(ArchiveQuestProperty property) { }
	// RVA: 0x30718dc VA: 0x75956898dc
	private Void _Refresh(Int32 focusIndex, Boolean isFastMode) { }
	// RVA: 0x3071668 VA: 0x7595689668
	private Void _TryPlayAnimSelectionToDetail(Int32 focusIndex, Boolean isFastMode) { }
	// RVA: 0x3071994 VA: 0x7595689994
	private Void _TryPlayAnimDetailToSelection() { }
	// RVA: 0x307136c VA: 0x759568936c
	private Void _ResetDetail() { }
	// RVA: 0x3071dd8 VA: 0x7595689dd8
	private Void _RefreshIndex(Int32 focusIndex) { }
	// RVA: 0x3071f30 VA: 0x7595689f30
	private Void _RefreshArrow() { }
	// RVA: 0x3070d50 VA: 0x7595688d50
	private Void _InitIfNot() { }
	// RVA: 0x30722c4 VA: 0x759568a2c4
	private Void _RenderFocusItem() { }
	// RVA: 0x3072548 VA: 0x759568a548
	private Void _RenderAVG(ArchiveQuestAVGItemModel model, String archiveId) { }
	// RVA: 0x3072744 VA: 0x759568a744
	private Void _RenderCG(ArchiveQuestCGItemModel model) { }
	// RVA: 0x307295c VA: 0x759568a95c
	private Sprite _TryLoadSpriteFromAutoPackHub(String spriteId, String hubPath) { }
	// RVA: 0x3072ab4 VA: 0x759568aab4
	private Void _OpenAvgSelectDialog(ArchiveQuestAVGItemModel itemModel) { }
	// RVA: 0x3072c80 VA: 0x759568ac80
	private ArchiveQuestItemModel _GetSelectedItemModel() { }
	// RVA: 0x3072d18 VA: 0x759568ad18
	private Void _OnSelectedAvg(Int32 index) { }
	// RVA: 0x3072de8 VA: 0x759568ade8
	private Void _StartAvg(String storyId) { }
	// RVA: 0x307289c VA: 0x759568a89c
	private String _GetCgPath(String picPath) { }
	// RVA: 0x3072f60 VA: 0x759568af60
	public Void EventOnClickLeftArrow() { }
	// RVA: 0x3072fec VA: 0x759568afec
	public Void EventOnClickRightArrow() { }
	// RVA: 0x3073078 VA: 0x759568b078
	public Void EventOnClickAvg() { }
	// RVA: 0x3073214 VA: 0x759568b214
	public Void EventOnSelectTypeMain() { }
	// RVA: 0x307329c VA: 0x759568b29c
	public Void EventOnSelectTypeSide() { }
	// RVA: 0x3073324 VA: 0x759568b324
	public Void EventOnSelectTypeLocked() { }
	// RVA: 0x307340c VA: 0x759568b40c
	public Void .ctor() { }
	// RVA: 0x3073540 VA: 0x759568b540
	private Void <_TryPlayAnimDetailToSelection>b__50_0() { }
	// RVA: 0x3073568 VA: 0x759568b568
	private Void <_TryPlayAnimDetailToSelection>b__50_1() { }
}
```