# SandboxV2BasementStatusView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _basementHpInfoText`

- `Text _basementHpText`

- `SandboxV2CircleProgressBar _basementHpBar`

- `UISlicedCircleBar _basementHpValue`

- `Text _basementLevelText`

- `Text _basementLevelInfoText`

- `UIAtlasImage _basementBkg`

- `UIAtlasImage _basementIcon`

- `Text _basementStageNameText`

- `GameObject _pnlCanUpgrade`

- `GameObject _pnlUpgradeBtn`

- `UIAnimationLocation _animIntro`

- `UIAnimationLocation _animLoop`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `SandboxV2DungeonViewConfig m_dungeonViewConfig`

- `SandboxV2NodeType m_cachedNodeType`

- `Boolean m_cachedIsEnemyRush`

- `Boolean m_cachedIsMaxBasementLevel`

- `SeqNumChecker m_nodeSelectChecker`

- `Tween m_tween`


## Methods

- `Void Render(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`

- `Void OnClickUpgradeBtn()`

- `Void <Render>b__23_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BasementStatusView : MonoBehaviour, IHotfixable
{
	private const String BASEMENT_HEALTH_VALUE_FORMAT; // 0x0
	private Text _basementHpInfoText; // 0x18
	private Text _basementHpText; // 0x20
	private SandboxV2CircleProgressBar _basementHpBar; // 0x28
	private UISlicedCircleBar _basementHpValue; // 0x30
	private Text _basementLevelText; // 0x38
	private Text _basementLevelInfoText; // 0x40
	private UIAtlasImage _basementBkg; // 0x48
	private UIAtlasImage _basementIcon; // 0x50
	private Text _basementStageNameText; // 0x58
	private GameObject _pnlCanUpgrade; // 0x60
	private GameObject _pnlUpgradeBtn; // 0x68
	private List`1 _supportedNodeType; // 0x70
	private UIAnimationLocation _animIntro; // 0x78
	private UIAnimationLocation _animLoop; // 0x88
	private UIPageFinder m_pageFinder; // 0x98
	private UIStateFinder m_stateFinder; // 0xa8
	private SandboxV2DungeonViewConfig m_dungeonViewConfig; // 0xb8
	private SandboxV2NodeType m_cachedNodeType; // 0xc0
	private Boolean m_cachedIsEnemyRush; // 0xc4
	private Boolean m_cachedIsMaxBasementLevel; // 0xc5
	private SeqNumChecker m_nodeSelectChecker; // 0xc8
	private Tween m_tween; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickUpgradeBtn; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x250df68 VA: 0x7594b25f68
	public Void Render(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x250e6b4 VA: 0x7594b266b4
	public Void OnClickUpgradeBtn() { }
	// RVA: 0x250e76c VA: 0x7594b2676c
	public Void .ctor() { }
	// RVA: 0x250e804 VA: 0x7594b26804
	private Void <Render>b__23_0() { }
}
```