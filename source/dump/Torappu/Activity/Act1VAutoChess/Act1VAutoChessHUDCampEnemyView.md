# Act1VAutoChessHUDCampEnemyView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `GameObject _encounteringPanel`

- `Image _campIconImage`

- `Image _campCharImage`

- `Text _campNameText`

- `Text _campNameExtraText`

- `Text _campFeatureText`

- `SimpleLayoutContent _tempBuffContent`

- `SimpleLayoutContent _permBuffContent`

- `UIAnimationLocation _showAnimation`

- `CanvasGroup _contentGroup`

- `Single _fadeDuration`

- `Boolean m_hasInited`

- `Int32 m_presentingIndex`

- `Int32 m_displayingIndex`

- `UIPageFinder m_pageFinder`

- `ILoadAsset m_iLoadAsset`

- `AnimationSwitchTween m_showTween`

- `Sequence m_switchTween`

- `Act1VAutoChessHUDCampEnemyItemViewModel m_presentingItem`

- `String m_campIconId`

- `String m_campCharId`

- `HUDSeqNumChecker m_stateChecker`

- `HUDSeqNumChecker m_campUpdateChecker`

- `HUDSeqNumChecker m_campSwitchChecker`


## Methods

- `Void Render(HUDCampShowState, Act1VAutoChessHUDCampEnemyViewModel, Int32[])`

- `Void _StartTutorialSignalCoroutine()`

- `IEnumerator _TryRaiseTutorialSignal()`

- `Void _RaiseTutorialSignal()`

- `Void _InitIfNot()`

- `Void _SwitchPresentingItem(Act1VAutoChessHUDCampEnemyItemViewModel, Int32, Boolean)`

- `Void _UpdateView()`

- `Boolean <_TryRaiseTutorialSignal>b__29_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampEnemyView : MonoBehaviour, IHotfixable
{
	private GameObject _encounteringPanel; // 0x18
	private Image _campIconImage; // 0x20
	private Image _campCharImage; // 0x28
	private Text _campNameText; // 0x30
	private Text _campNameExtraText; // 0x38
	private Text _campFeatureText; // 0x40
	private SimpleLayoutContent _tempBuffContent; // 0x48
	private SimpleLayoutContent _permBuffContent; // 0x50
	private UIAnimationLocation _showAnimation; // 0x58
	private CanvasGroup _contentGroup; // 0x68
	private Single _fadeDuration; // 0x70
	private Boolean m_hasInited; // 0x74
	private Int32 m_presentingIndex; // 0x78
	private Int32 m_displayingIndex; // 0x7c
	private UIPageFinder m_pageFinder; // 0x80
	private ILoadAsset m_iLoadAsset; // 0x90
	private readonly CampBuffAdapter m_tempBuffAdapter; // 0x98
	private readonly CampBuffAdapter m_permBuffAdapter; // 0xa0
	private AnimationSwitchTween m_showTween; // 0xa8
	private Sequence m_switchTween; // 0xb0
	private Act1VAutoChessHUDCampEnemyItemViewModel m_presentingItem; // 0xb8
	private String m_campIconId; // 0xc0
	private String m_campCharId; // 0xc8
	private HUDSeqNumChecker m_stateChecker; // 0xd0
	private HUDSeqNumChecker m_campUpdateChecker; // 0xd8
	private HUDSeqNumChecker m_campSwitchChecker; // 0xe0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__StartTutorialSignalCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__TryRaiseTutorialSignal; // 0x10
	private static DelegateBridge __Hotfix0__RaiseTutorialSignal; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__SwitchPresentingItem; // 0x28
	private static DelegateBridge __Hotfix0__UpdateView; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x336698c VA: 0x759597e98c
	public Void Render(HUDCampShowState campState, Act1VAutoChessHUDCampEnemyViewModel model, Int32[] seqNums) { }
	// RVA: 0x3366ce0 VA: 0x759597ece0
	private Void _StartTutorialSignalCoroutine() { }
	// RVA: 0x33670e8 VA: 0x759597f0e8
	private IEnumerator _TryRaiseTutorialSignal() { }
	// RVA: 0x3366d88 VA: 0x759597ed88
	private Void _RaiseTutorialSignal() { }
	// RVA: 0x3366b80 VA: 0x759597eb80
	private Void _InitIfNot() { }
	// RVA: 0x3366ebc VA: 0x759597eebc
	private Void _SwitchPresentingItem(Act1VAutoChessHUDCampEnemyItemViewModel presentingItem, Int32 presentIndex, Boolean fastMode) { }
	// RVA: 0x33671bc VA: 0x759597f1bc
	private Void _UpdateView() { }
	// RVA: 0x336785c VA: 0x759597f85c
	public Void .ctor() { }
	// RVA: 0x33679f8 VA: 0x759597f9f8
	private Boolean <_TryRaiseTutorialSignal>b__29_0() { }
}
```