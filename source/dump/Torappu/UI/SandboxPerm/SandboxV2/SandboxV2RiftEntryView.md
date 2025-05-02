# SandboxV2RiftEntryView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _mainTargetTitle`

- `Text _mainTargetDesc`

- `Text _mainTargetDayCount`

- `SandboxV2RiftEntryParamItem _climateParam`

- `SandboxV2RiftEntryParamItem _terrainParam`

- `SandboxV2RiftEntryParamItem _enemyParam`

- `GameObject _globalEffectGo`

- `Text _globalEffectDesc`

- `GameObject _subTargetGo`

- `Text _subTargetDesc`

- `Text _rewardDescText`

- `GameObject _rewardEmptyPanel`

- `GameObject _rewardContentPanel`

- `SimpleLayoutContent _rewardContent`

- `ScrollRect _rewardRect`

- `UIAnimationLocation _difficultyPanelSwitchAnim`

- `TwoStateToggle _difficultyPanelToggle`

- `TwoStateToggle _difficultyDescToggle`

- `Text _difficultyLevel`

- `SimpleLayoutContent _difficultyDetailDesc`

- `TwoStateToggle _teamToggle`

- `Image _teamSmallIcon`

- `Text _teamLevel`

- `Text _teamName`

- `TwoStateToggle _riftStartToggle`

- `Text _riftStartRemainTimeText`

- `RectTransform _backPressArea`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `Int32 m_cachedDifficultyLevel`

- `RewardAdapter m_rewardAdapter`

- `DifficultyDescAdapter m_difficultyDescAdapter`

- `AnimationSwitchTween m_difficultyPanelSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void CreateRift()`

- `Void ExitRiftReservePage()`

- `Void OpenDifficultyDetailPanel()`

- `Void CloseDifficultyDetailPanel()`

- `Void OpenRiftTeamState()`

- `Void OpenRiftDifficultyState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftEntryView : DataBinder`1
{
	private static readonly Option REWARD_ITEM_CARD_OPTION; // 0x0
	private Text _mainTargetTitle; // 0x20
	private Text _mainTargetDesc; // 0x28
	private Text _mainTargetDayCount; // 0x30
	private SandboxV2RiftEntryParamItem _climateParam; // 0x38
	private SandboxV2RiftEntryParamItem _terrainParam; // 0x40
	private SandboxV2RiftEntryParamItem _enemyParam; // 0x48
	private GameObject _globalEffectGo; // 0x50
	private Text _globalEffectDesc; // 0x58
	private GameObject _subTargetGo; // 0x60
	private Text _subTargetDesc; // 0x68
	private Text _rewardDescText; // 0x70
	private GameObject _rewardEmptyPanel; // 0x78
	private GameObject _rewardContentPanel; // 0x80
	private SimpleLayoutContent _rewardContent; // 0x88
	private ScrollRect _rewardRect; // 0x90
	private UIAnimationLocation _difficultyPanelSwitchAnim; // 0x98
	private TwoStateToggle _difficultyPanelToggle; // 0xa8
	private TwoStateToggle _difficultyDescToggle; // 0xb0
	private Text _difficultyLevel; // 0xb8
	private SimpleLayoutContent _difficultyDetailDesc; // 0xc0
	private TwoStateToggle _teamToggle; // 0xc8
	private Image _teamSmallIcon; // 0xd0
	private Text _teamLevel; // 0xd8
	private Text _teamName; // 0xe0
	private TwoStateToggle _riftStartToggle; // 0xe8
	private Text _riftStartRemainTimeText; // 0xf0
	private RectTransform _backPressArea; // 0xf8
	private Boolean m_hasInited; // 0x100
	private UIStateFinder m_stateFinder; // 0x108
	private UIPageFinder m_pageFinder; // 0x118
	private List`1 m_cachedRewards; // 0x128
	private List`1 m_cachedDifficultyDesc; // 0x130
	private Int32 m_cachedDifficultyLevel; // 0x138
	private RewardAdapter m_rewardAdapter; // 0x140
	private DifficultyDescAdapter m_difficultyDescAdapter; // 0x148
	private AnimationSwitchTween m_difficultyPanelSwitchTween; // 0x150
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_CreateRift; // 0x30
	private static DelegateBridge __Hotfix0_ExitRiftReservePage; // 0x38
	private static DelegateBridge __Hotfix0_OpenDifficultyDetailPanel; // 0x40
	private static DelegateBridge __Hotfix0_CloseDifficultyDetailPanel; // 0x48
	private static DelegateBridge __Hotfix0_OpenRiftTeamState; // 0x50
	private static DelegateBridge __Hotfix0_OpenRiftDifficultyState; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x25fe25c VA: 0x7594c1625c
	public override Void OnValueChanged(SandboxV2RiftEntryProperty property) { }
	// RVA: 0x25fe7ac VA: 0x7594c167ac
	private Void _InitIfNot() { }
	// RVA: 0x25feb00 VA: 0x7594c16b00
	public Void CreateRift() { }
	// RVA: 0x25febb4 VA: 0x7594c16bb4
	public Void ExitRiftReservePage() { }
	// RVA: 0x25fec68 VA: 0x7594c16c68
	public Void OpenDifficultyDetailPanel() { }
	// RVA: 0x25fecf0 VA: 0x7594c16cf0
	public Void CloseDifficultyDetailPanel() { }
	// RVA: 0x25fed78 VA: 0x7594c16d78
	public Void OpenRiftTeamState() { }
	// RVA: 0x25fee2c VA: 0x7594c16e2c
	public Void OpenRiftDifficultyState() { }
	// RVA: 0x25feee0 VA: 0x7594c16ee0
	public Void .ctor() { }
	// RVA: 0x25fef80 VA: 0x7594c16f80
	private static Void .cctor() { }
}
```