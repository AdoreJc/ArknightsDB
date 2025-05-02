# Act25sideResearchAreaView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Text _areaName`

- `Text _areaProgress`

- `Image _progressIcon`

- `GameObject _panelAreaDesc`

- `GameObject _panelMission`

- `GameObject _panelAreaEnd`

- `GameObject _panelBattleEnd`

- `GameObject _panelMissionUncomplete`

- `GameObject _panelMissionComplete`

- `GameObject _panelAreaComplete`

- `SimpleLayoutContent _rewardContent`

- `Single _itemCardScale`

- `Text _textAreaDesc`

- `Text _textCostCount`

- `Text _textMissionDesc`

- `Text _textAreaEnd`

- `UIAnimationLocation _maskSwitchAnim`

- `Transform _areaContainer`

- `UICommonPageEffectHolder _pageEffectHolder`

- `GameObject _panelArchiveButton`

- `CanvasGroup _areaBtnCanvasGroup`

- `Single _areaEmptyAlpha`

- `Boolean m_isInited`

- `Boolean m_isSwitching`

- `AnimationSwitchTween m_maskSwitchAnim`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `Act25sideAreaViewModel m_cachedViewModel`

- `RewardAdapter m_adapter`

- `Act25sideResearchAreaBackView m_currentAreaView`

- `GameObject m_areaPrefab`

- `Coroutine m_switchCoroutine`


## Methods

- `Void Init(UIPage)`

- `Void Render(Act25sideAreaViewModel, Boolean)`

- `IEnumerator _SwitchAnimCoroutine()`

- `Void _LoadArea()`

- `Void _LoadAreaImpl()`

- `Void _RenderArea()`

- `Void _InitIfNot()`

- `Sprite _LoadProgressIcon(String)`

- `Void OnRouteToStage()`

- `Void OnAcceptMission()`

- `Void OnCompleteMission()`

- `Void OnOpenArchive()`

- `Void OnShowReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchAreaView : MonoBehaviour, IHotfixable
{
	private Text _areaName; // 0x18
	private Text _areaProgress; // 0x20
	private Image _progressIcon; // 0x28
	private GameObject _panelAreaDesc; // 0x30
	private GameObject _panelMission; // 0x38
	private GameObject _panelAreaEnd; // 0x40
	private GameObject _panelBattleEnd; // 0x48
	private GameObject _panelMissionUncomplete; // 0x50
	private GameObject _panelMissionComplete; // 0x58
	private GameObject _panelAreaComplete; // 0x60
	private SimpleLayoutContent _rewardContent; // 0x68
	private Single _itemCardScale; // 0x70
	private Text _textAreaDesc; // 0x78
	private Text _textCostCount; // 0x80
	private Text _textMissionDesc; // 0x88
	private Text _textAreaEnd; // 0x90
	private UIAnimationLocation _maskSwitchAnim; // 0x98
	private Transform _areaContainer; // 0xa8
	private UICommonPageEffectHolder _pageEffectHolder; // 0xb0
	private GameObject _panelArchiveButton; // 0xb8
	private CanvasGroup _areaBtnCanvasGroup; // 0xc0
	private Single _areaEmptyAlpha; // 0xc8
	private Boolean m_isInited; // 0xcc
	private Boolean m_isSwitching; // 0xcd
	private AnimationSwitchTween m_maskSwitchAnim; // 0xd0
	private UIPageFinder m_pageFinder; // 0xd8
	private UIStateFinder m_stateFinder; // 0xe8
	private Act25sideAreaViewModel m_cachedViewModel; // 0xf8
	private RewardAdapter m_adapter; // 0x100
	private Act25sideResearchAreaBackView m_currentAreaView; // 0x108
	private GameObject m_areaPrefab; // 0x110
	private Coroutine m_switchCoroutine; // 0x118
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__SwitchAnimCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__LoadArea; // 0x18
	private static DelegateBridge __Hotfix0__LoadAreaImpl; // 0x20
	private static DelegateBridge __Hotfix0__RenderArea; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__LoadProgressIcon; // 0x38
	private static DelegateBridge __Hotfix0_OnRouteToStage; // 0x40
	private static DelegateBridge __Hotfix0_OnAcceptMission; // 0x48
	private static DelegateBridge __Hotfix0_OnCompleteMission; // 0x50
	private static DelegateBridge __Hotfix0_OnOpenArchive; // 0x58
	private static DelegateBridge __Hotfix0_OnShowReward; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x3282e60 VA: 0x759589ae60
	public Void Init(UIPage page) { }
	// RVA: 0x3282f48 VA: 0x759589af48
	public Void Render(Act25sideAreaViewModel viewModel, Boolean isInit) { }
	// RVA: 0x3283794 VA: 0x759589b794
	private IEnumerator _SwitchAnimCoroutine() { }
	// RVA: 0x32836a0 VA: 0x759589b6a0
	private Void _LoadArea() { }
	// RVA: 0x3283868 VA: 0x759589b868
	private Void _LoadAreaImpl() { }
	// RVA: 0x3283278 VA: 0x759589b278
	public Void _RenderArea() { }
	// RVA: 0x32830f8 VA: 0x759589b0f8
	private Void _InitIfNot() { }
	// RVA: 0x3283cfc VA: 0x759589bcfc
	private Sprite _LoadProgressIcon(String iconId) { }
	// RVA: 0x3283fd4 VA: 0x759589bfd4
	public Void OnRouteToStage() { }
	// RVA: 0x3284270 VA: 0x759589c270
	public Void OnAcceptMission() { }
	// RVA: 0x328437c VA: 0x759589c37c
	public Void OnCompleteMission() { }
	// RVA: 0x3284490 VA: 0x759589c490
	public Void OnOpenArchive() { }
	// RVA: 0x328459c VA: 0x759589c59c
	public Void OnShowReward() { }
	// RVA: 0x32846a8 VA: 0x759589c6a8
	public Void .ctor() { }
}
```