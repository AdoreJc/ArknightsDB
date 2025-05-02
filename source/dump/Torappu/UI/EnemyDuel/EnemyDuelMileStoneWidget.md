# EnemyDuelMileStoneWidget

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Text _progressTextCurrent`

- `Text _progressTextTotal`

- `Slider _progressBar`

- `Text _curLevelText`

- `GameObject _isMaxTag`

- `GameObject _panelLevel`

- `Text _mileStoneName`

- `Text _rewardName`

- `Text _rewardText`

- `RectTransform _rewardContainer`

- `UIPageFinder m_pageFinder`

- `UIItemViewModel m_avatarItemViewModel`

- `GameObject m_rewardGameObject`


## Methods

- `Void _LoadRewardIfNecessary(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelMileStoneWidget : TemplateActivityMilestoneWidget
{
	private Text _progressTextCurrent; // 0x18
	private Text _progressTextTotal; // 0x20
	private Slider _progressBar; // 0x28
	private Text _curLevelText; // 0x30
	private GameObject _isMaxTag; // 0x38
	private GameObject _panelLevel; // 0x40
	private Text _mileStoneName; // 0x48
	private Text _rewardName; // 0x50
	private Text _rewardText; // 0x58
	private RectTransform _rewardContainer; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private UIItemViewModel m_avatarItemViewModel; // 0x78
	private GameObject m_rewardGameObject; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__LoadRewardIfNecessary; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2978920 VA: 0x7594f90920
	public override Void Render(TemplateActivityMilestoneGroupViewModel milestoneViewModel) { }
	// RVA: 0x2978cbc VA: 0x7594f90cbc
	private Void _LoadRewardIfNecessary(String actId) { }
	// RVA: 0x2978e80 VA: 0x7594f90e80
	public Void .ctor() { }
}
```