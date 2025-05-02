# Act1VAutoChessChessShopMainView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `CanvasGroup _canvasCharList`

- `RectTransform _transCharListViewContainer`

- `Act1VAutoChessChessShopCharListView _charListViewPrefab`

- `CanvasGroup _canvasTrapList`

- `RectTransform _transTrapListViewContainer`

- `Act1VAutoChessChessShopTrapListView _trapListViewPrefab`

- `CanvasGroup _canvasMenuView`

- `RectTransform _transMenuViewContainer`

- `Act1VAutoChessChessShopMenuView _menuViewPrefab`

- `CanvasGroup _canvasTopView`

- `RectTransform _transTopViewContainer`

- `Act1VAutoChessChessShopTopView _topViewPrefab`

- `CanvasGroup _canvasDetailView`

- `RectTransform _detailViewContainer`

- `Act1VAutoChessChessShopDetailView _detailViewPrefab`

- `CanvasGroup _canvasDetailCharList`

- `RectTransform _transDetailCharListViewContainer`

- `Act1VAutoChessChessShopDetailCharListView _detailCharListViewPrefab`

- `CanvasGroup _canvasSkillAndModuleEditCharList`

- `RectTransform _transSkillAndModuleEditCharListViewContainer`

- `Act1VAutoChessChessShopSkillAndModuleEditCharListView _skillAndModuleEditListViewPrefab`

- `RectTransform _rectTopMenuContainer`

- `Boolean m_hasInited`

- `Act1VAutoChessChessShopCharListView m_charListView`

- `Act1VAutoChessChessShopTrapListView m_trapListView`

- `Act1VAutoChessChessShopMenuView m_menuView`

- `Act1VAutoChessChessShopTopView m_topView`

- `Act1VAutoChessChessShopDetailView m_detailView`

- `Act1VAutoChessChessShopDetailCharListView m_detailCharListView`

- `Act1VAutoChessChessShopSkillAndModuleEditCharListView m_skillAndModuleEditCharListView`

- `FadeSwitchTween m_tweenCharList`

- `FadeSwitchTween m_tweenDetailCharList`

- `FadeSwitchTween m_tweenSkillAndModuleEditCharList`

- `FadeSwitchTween m_tweenTrapList`

- `FadeSwitchTween m_tweenMenuView`

- `FadeSwitchTween m_tweenTopView`

- `FadeSwitchTween m_tweenDetailView`

- `UIStateFinder m_stateFinder`

- `Coroutine m_tutorialCoroutine`

- `Act1VAutoChessEntryPage m_page`


## Properties

- `Act1VAutoChessChessShopSkillAndModuleEditCharListView multiEditCharListView`

- `Act1VAutoChessChessShopCharListView charListView`


## Methods

- `Act1VAutoChessChessShopSkillAndModuleEditCharListView get_multiEditCharListView()`

- `Act1VAutoChessChessShopCharListView get_charListView()`

- `Void Init(Act1VAutoChessEntryPage)`

- `Void OnEnter()`

- `Void _InitIfNot()`

- `Builder _GetListFadeBuilder(CanvasGroup)`

- `Void _TryStartTutorial()`

- `IEnumerator _TutorialOnly_TryRaiseAVGSignal()`

- `Void TutorialOnly_RegisterTutorialGoLevelFiveDiyCharItem()`

- `Void _EventOnReturnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopMainView : DataBinder`1
{
	private CanvasGroup _canvasCharList; // 0x20
	private RectTransform _transCharListViewContainer; // 0x28
	private Act1VAutoChessChessShopCharListView _charListViewPrefab; // 0x30
	private CanvasGroup _canvasTrapList; // 0x38
	private RectTransform _transTrapListViewContainer; // 0x40
	private Act1VAutoChessChessShopTrapListView _trapListViewPrefab; // 0x48
	private CanvasGroup _canvasMenuView; // 0x50
	private RectTransform _transMenuViewContainer; // 0x58
	private Act1VAutoChessChessShopMenuView _menuViewPrefab; // 0x60
	private CanvasGroup _canvasTopView; // 0x68
	private RectTransform _transTopViewContainer; // 0x70
	private Act1VAutoChessChessShopTopView _topViewPrefab; // 0x78
	private CanvasGroup _canvasDetailView; // 0x80
	private RectTransform _detailViewContainer; // 0x88
	private Act1VAutoChessChessShopDetailView _detailViewPrefab; // 0x90
	private CanvasGroup _canvasDetailCharList; // 0x98
	private RectTransform _transDetailCharListViewContainer; // 0xa0
	private Act1VAutoChessChessShopDetailCharListView _detailCharListViewPrefab; // 0xa8
	private CanvasGroup _canvasSkillAndModuleEditCharList; // 0xb0
	private RectTransform _transSkillAndModuleEditCharListViewContainer; // 0xb8
	private Act1VAutoChessChessShopSkillAndModuleEditCharListView _skillAndModuleEditListViewPrefab; // 0xc0
	private RectTransform _rectTopMenuContainer; // 0xc8
	private Boolean m_hasInited; // 0xd0
	private Act1VAutoChessChessShopCharListView m_charListView; // 0xd8
	private Act1VAutoChessChessShopTrapListView m_trapListView; // 0xe0
	private Act1VAutoChessChessShopMenuView m_menuView; // 0xe8
	private Act1VAutoChessChessShopTopView m_topView; // 0xf0
	private Act1VAutoChessChessShopDetailView m_detailView; // 0xf8
	private Act1VAutoChessChessShopDetailCharListView m_detailCharListView; // 0x100
	private Act1VAutoChessChessShopSkillAndModuleEditCharListView m_skillAndModuleEditCharListView; // 0x108
	private FadeSwitchTween m_tweenCharList; // 0x110
	private FadeSwitchTween m_tweenDetailCharList; // 0x118
	private FadeSwitchTween m_tweenSkillAndModuleEditCharList; // 0x120
	private FadeSwitchTween m_tweenTrapList; // 0x128
	private FadeSwitchTween m_tweenMenuView; // 0x130
	private FadeSwitchTween m_tweenTopView; // 0x138
	private FadeSwitchTween m_tweenDetailView; // 0x140
	private UIStateFinder m_stateFinder; // 0x148
	private Coroutine m_tutorialCoroutine; // 0x158
	private Act1VAutoChessEntryPage m_page; // 0x160
	private const Single LIST_SWITCH_TWEEN_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_get_multiEditCharListView; // 0x0
	private static DelegateBridge __Hotfix0_get_charListView; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__GetListFadeBuilder; // 0x30
	private static DelegateBridge __Hotfix0__TryStartTutorial; // 0x38
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRaiseAVGSignal; // 0x40
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterTutorialGoLevelFiveDiyCharItem; // 0x48
	private static DelegateBridge __Hotfix0__EventOnReturnClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Act1VAutoChessChessShopSkillAndModuleEditCharListView multiEditCharListView { get; }
	public Act1VAutoChessChessShopCharListView charListView { get; }

	// RVA: 0x330eb84 VA: 0x7595926b84
	public Act1VAutoChessChessShopSkillAndModuleEditCharListView get_multiEditCharListView() { }
	// RVA: 0x33124a8 VA: 0x759592a4a8
	public Act1VAutoChessChessShopCharListView get_charListView() { }
	// RVA: 0x330e768 VA: 0x7595926768
	public Void Init(Act1VAutoChessEntryPage page) { }
	// RVA: 0x330d6cc VA: 0x75959256cc
	public Void OnEnter() { }
	// RVA: 0x3314184 VA: 0x759592c184
	public override Void OnValueChanged(Act1VAutoChessChessShopViewProperty property) { }
	// RVA: 0x3313ce8 VA: 0x759592bce8
	private Void _InitIfNot() { }
	// RVA: 0x3314c28 VA: 0x759592cc28
	private Builder _GetListFadeBuilder(CanvasGroup canvasGroup) { }
	// RVA: 0x3314b20 VA: 0x759592cb20
	private Void _TryStartTutorial() { }
	// RVA: 0x3314cf0 VA: 0x759592ccf0
	private IEnumerator _TutorialOnly_TryRaiseAVGSignal() { }
	// RVA: 0x3311f54 VA: 0x7595929f54
	public Void TutorialOnly_RegisterTutorialGoLevelFiveDiyCharItem() { }
	// RVA: 0x3314ec8 VA: 0x759592cec8
	private Void _EventOnReturnClick() { }
	// RVA: 0x3314f6c VA: 0x759592cf6c
	public Void .ctor() { }
}
```