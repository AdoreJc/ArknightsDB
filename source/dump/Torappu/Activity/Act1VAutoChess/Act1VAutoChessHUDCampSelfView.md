# Act1VAutoChessHUDCampSelfView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _campIconImage`

- `Image _campCharImage`

- `Text _campNameText`

- `Text _campNameExtraText`

- `Text _campFeatureText`

- `SimpleLayoutContent _buffContent`

- `CanvasGroup _choiceCanvasGroup`

- `UIAnimationLocation _showAnimation`

- `UIAnimationLocation _optionShowAnimation`

- `UIAnimationLocation _headHighlightAnimation`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_showTween`

- `AnimationSwitchTween m_optionShowTween`

- `AnimationSwitchTween m_headHighlightTween`

- `String m_campIconId`

- `String m_campCharId`

- `HUDSeqNumChecker m_stateChecker`

- `HUDSeqNumChecker m_campUpgradeChecker`

- `HUDSeqNumChecker m_campUpdateChecker`

- `HUDSeqNumChecker m_campSwitchChecker`


## Methods

- `Void Render(HUDCampShowState, Act1VAutoChessHUDCampSelfViewModel, Int32[])`

- `Void _StartTutorialSignalCoroutine()`

- `IEnumerator _TryRaiseTutorialSignal()`

- `Void _RaiseTutorialSignal()`

- `Void _InitIfNot()`

- `Void _OnSelectEvent(Int32)`

- `Void _OnConfirmSelectEvent()`

- `Boolean <_TryRaiseTutorialSignal>b__27_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampSelfView : MonoBehaviour, IHotfixable
{
	private Image _campIconImage; // 0x18
	private Image _campCharImage; // 0x20
	private Text _campNameText; // 0x28
	private Text _campNameExtraText; // 0x30
	private Text _campFeatureText; // 0x38
	private SimpleLayoutContent _buffContent; // 0x40
	private List`1 _optionViews; // 0x48
	private CanvasGroup _choiceCanvasGroup; // 0x50
	private UIAnimationLocation _showAnimation; // 0x58
	private UIAnimationLocation _optionShowAnimation; // 0x68
	private UIAnimationLocation _headHighlightAnimation; // 0x78
	private Boolean m_hasInited; // 0x88
	private ILoadAsset m_iLoadAsset; // 0x90
	private UIPageFinder m_pageFinder; // 0x98
	private readonly CampBuffAdapter m_buffAdapter; // 0xa8
	private AnimationSwitchTween m_showTween; // 0xb0
	private AnimationSwitchTween m_optionShowTween; // 0xb8
	private AnimationSwitchTween m_headHighlightTween; // 0xc0
	private String m_campIconId; // 0xc8
	private String m_campCharId; // 0xd0
	private HUDSeqNumChecker m_stateChecker; // 0xd8
	private HUDSeqNumChecker m_campUpgradeChecker; // 0xe0
	private HUDSeqNumChecker m_campUpdateChecker; // 0xe8
	private HUDSeqNumChecker m_campSwitchChecker; // 0xf0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__StartTutorialSignalCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__TryRaiseTutorialSignal; // 0x10
	private static DelegateBridge __Hotfix0__RaiseTutorialSignal; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnSelectEvent; // 0x28
	private static DelegateBridge __Hotfix0__OnConfirmSelectEvent; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3368314 VA: 0x7595980314
	public Void Render(HUDCampShowState campState, Act1VAutoChessHUDCampSelfViewModel model, Int32[] seqNums) { }
	// RVA: 0x3368c50 VA: 0x7595980c50
	private Void _StartTutorialSignalCoroutine() { }
	// RVA: 0x3369304 VA: 0x7595981304
	private IEnumerator _TryRaiseTutorialSignal() { }
	// RVA: 0x3368cf8 VA: 0x7595980cf8
	private Void _RaiseTutorialSignal() { }
	// RVA: 0x3368930 VA: 0x7595980930
	private Void _InitIfNot() { }
	// RVA: 0x33693d8 VA: 0x75959813d8
	private Void _OnSelectEvent(Int32 index) { }
	// RVA: 0x33694e4 VA: 0x75959814e4
	private Void _OnConfirmSelectEvent() { }
	// RVA: 0x3369598 VA: 0x7595981598
	public Void .ctor() { }
	// RVA: 0x3369724 VA: 0x7595981724
	private Boolean <_TryRaiseTutorialSignal>b__27_0() { }
}
```