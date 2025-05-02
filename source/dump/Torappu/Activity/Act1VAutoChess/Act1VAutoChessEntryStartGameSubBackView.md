# Act1VAutoChessEntryStartGameSubBackView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _selectDescText`

- `Image _bandIconImage`

- `Image _bandCharIconImage`

- `Text _bandNameText`

- `Text _bandHpText`

- `Text _bandDescText`

- `ScrollRect _bandDescScrollRect`

- `UIAnimationLocation _selectAnimation`

- `UIAnimationLocation _toForceAnimation`

- `UIAnimationLocation _toBandAnimation`

- `CanvasGroup _interactGroup`

- `Act1VAutoChessEntryStartGameAnimEventListener _listener`

- `GameObject _tutorialOnly_enemyInfoPanel`

- `GameObject _tutorialOnly_bandInfoPanel`

- `Boolean m_hasInited`

- `UIPageFinder m_finder`

- `ILoadAsset m_iLoadAsset`

- `AnimationWrapper m_animationWrapper`

- `Tween m_switchTween`

- `String m_cachedBandId`

- `ShowState m_showState`

- `Boolean m_tutorialOnly_bandShowSignalAppended`


## Methods

- `Void _TutorialOnlyTryInvokeBandShowSignal()`

- `Void OnSwitchShowEvent()`

- `Void _InitIfNot()`

- `Void _RenderBand(BandViewModel, ShowState)`

- `Void _RenderForces(List`1, ShowState)`

- `Void _StopAnimation()`

- `Void _SwitchStateIfNeed(ShowState)`

- `Void _ReleaseBlocking()`

- `Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel)`

- `Void <>xLuaBaseProxy_TutorialOnlyRegisterTutorialGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryStartGameSubBackView : Act1VAutoChessBaseSubView
{
	private Text _selectDescText; // 0x18
	private Image _bandIconImage; // 0x20
	private Image _bandCharIconImage; // 0x28
	private Text _bandNameText; // 0x30
	private Text _bandHpText; // 0x38
	private Text _bandDescText; // 0x40
	private ScrollRect _bandDescScrollRect; // 0x48
	private List`1 _forceInfos; // 0x50
	private UIAnimationLocation _selectAnimation; // 0x58
	private UIAnimationLocation _toForceAnimation; // 0x68
	private UIAnimationLocation _toBandAnimation; // 0x78
	private CanvasGroup _interactGroup; // 0x88
	private Act1VAutoChessEntryStartGameAnimEventListener _listener; // 0x90
	private GameObject _tutorialOnly_enemyInfoPanel; // 0x98
	private GameObject _tutorialOnly_bandInfoPanel; // 0xa0
	private Boolean m_hasInited; // 0xa8
	private UIPageFinder m_finder; // 0xb0
	private ILoadAsset m_iLoadAsset; // 0xc0
	private AnimationWrapper m_animationWrapper; // 0xc8
	private Tween m_switchTween; // 0xd0
	private String m_cachedBandId; // 0xd8
	private readonly Dictionary`2 m_cachedForceIds; // 0xe0
	private ShowState m_showState; // 0xe8
	private Boolean m_tutorialOnly_bandShowSignalAppended; // 0xec
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_TutorialOnlyRegisterTutorialGo; // 0x8
	private static DelegateBridge __Hotfix0__TutorialOnlyTryInvokeBandShowSignal; // 0x10
	private static DelegateBridge __Hotfix0_OnSwitchShowEvent; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__RenderBand; // 0x28
	private static DelegateBridge __Hotfix0__RenderForces; // 0x30
	private static DelegateBridge __Hotfix0__StopAnimation; // 0x38
	private static DelegateBridge __Hotfix0__SwitchStateIfNeed; // 0x40
	private static DelegateBridge __Hotfix0__ReleaseBlocking; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x334b6ec VA: 0x75959636ec
	public override Void Render(Act1VAutoChessEntryBaseSubViewModel subViewModel) { }
	// RVA: 0x334c374 VA: 0x7595964374
	public override Void TutorialOnlyRegisterTutorialGo() { }
	// RVA: 0x334c4cc VA: 0x75959644cc
	private Void _TutorialOnlyTryInvokeBandShowSignal() { }
	// RVA: 0x334c5bc VA: 0x75959645bc
	public Void OnSwitchShowEvent() { }
	// RVA: 0x334b8cc VA: 0x75959638cc
	private Void _InitIfNot() { }
	// RVA: 0x334bacc VA: 0x7595963acc
	private Void _RenderBand(BandViewModel band, ShowState showState) { }
	// RVA: 0x334bd2c VA: 0x7595963d2c
	private Void _RenderForces(List`1 forces, ShowState showState) { }
	// RVA: 0x334c068 VA: 0x7595964068
	private Void _StopAnimation() { }
	// RVA: 0x334c0f8 VA: 0x75959640f8
	private Void _SwitchStateIfNeed(ShowState toState) { }
	// RVA: 0x334c670 VA: 0x7595964670
	private Void _ReleaseBlocking() { }
	// RVA: 0x334c724 VA: 0x7595964724
	public Void .ctor() { }
	// RVA: 0x334c7e8 VA: 0x75959647e8
	private Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel P0) { }
	// RVA: 0x334c7f0 VA: 0x75959647f0
	private Void <>xLuaBaseProxy_TutorialOnlyRegisterTutorialGo() { }
}
```