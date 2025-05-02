# VecBreakDefenseStageView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `ThreeStateToggle _toggle`

- `Text _bossTitle`

- `Text _bossDesc`

- `Image _bossIcon`

- `Text _buffName`

- `Text _buffDesc`

- `Image _buffIcon`

- `Text _charLimitText`

- `GameObject _reward`

- `Image _rewardIcon`

- `Text _rewardText`

- `Image _bossIconActive`

- `Text _buffNameActive`

- `Text _buffDescActive`

- `Image _buffIconActive`

- `Text _lockText`

- `GameObject _tutorialBuffPanel`

- `GameObject _tutorialEnemyPanel`

- `VecBreakDefenseStageViewModel m_stageModel`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(VecBreakDefenseStageViewModel, Int32)`

- `Void OnClickEnemy()`

- `Void OnClickMap()`

- `Void OnClickRetreat()`

- `Void OnClickEnterStage()`

- `Void _TutorialOnly_RegisterTutorialGo()`

- `Void _RenderInactivePart(ILoadAsset)`

- `Void _RenderActivePart(ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseStageView : MonoBehaviour, IHotfixable
{
	private ThreeStateToggle _toggle; // 0x18
	private Text _bossTitle; // 0x20
	private Text _bossDesc; // 0x28
	private Image _bossIcon; // 0x30
	private Text _buffName; // 0x38
	private Text _buffDesc; // 0x40
	private Image _buffIcon; // 0x48
	private Text _charLimitText; // 0x50
	private GameObject[] _human; // 0x58
	private GameObject _reward; // 0x60
	private Image _rewardIcon; // 0x68
	private Text _rewardText; // 0x70
	private Image _bossIconActive; // 0x78
	private Text _buffNameActive; // 0x80
	private Text _buffDescActive; // 0x88
	private Image _buffIconActive; // 0x90
	private ThreeStateToggle[] _chars; // 0x98
	private Image[] _charAvatars; // 0xa0
	private Text _lockText; // 0xa8
	private GameObject _tutorialBuffPanel; // 0xb0
	private GameObject _tutorialEnemyPanel; // 0xb8
	private VecBreakDefenseStageViewModel m_stageModel; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private UIStateFinder m_stateFinder; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickEnemy; // 0x8
	private static DelegateBridge __Hotfix0_OnClickMap; // 0x10
	private static DelegateBridge __Hotfix0_OnClickRetreat; // 0x18
	private static DelegateBridge __Hotfix0_OnClickEnterStage; // 0x20
	private static DelegateBridge __Hotfix0__TutorialOnly_RegisterTutorialGo; // 0x28
	private static DelegateBridge __Hotfix0__RenderInactivePart; // 0x30
	private static DelegateBridge __Hotfix0__RenderActivePart; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x22cce70 VA: 0x75948e4e70
	public Void Render(VecBreakDefenseStageViewModel model, Int32 index) { }
	// RVA: 0x22cd8c0 VA: 0x75948e58c0
	public Void OnClickEnemy() { }
	// RVA: 0x22cd9b8 VA: 0x75948e59b8
	public Void OnClickMap() { }
	// RVA: 0x22cdab0 VA: 0x75948e5ab0
	public Void OnClickRetreat() { }
	// RVA: 0x22cdba8 VA: 0x75948e5ba8
	public Void OnClickEnterStage() { }
	// RVA: 0x22cd7a4 VA: 0x75948e57a4
	private Void _TutorialOnly_RegisterTutorialGo() { }
	// RVA: 0x22cd088 VA: 0x75948e5088
	private Void _RenderInactivePart(ILoadAsset assetLoader) { }
	// RVA: 0x22cd430 VA: 0x75948e5430
	private Void _RenderActivePart(ILoadAsset assetLoader) { }
	// RVA: 0x22cdca0 VA: 0x75948e5ca0
	public Void .ctor() { }
}
```