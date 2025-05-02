# SandboxV2DungeonView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2NodePreviewView _nodePreviewViewPrefab`

- `RectTransform _nodePreviewViewHolder`

- `CanvasGroup _nodePreviewViewAlphaHandler`

- `RectTransform _homeTipViewHolder`

- `SandboxV2DungeonSideBar _sideBar`

- `SandboxV2DungeonBottomBar _bottomBar`

- `RectTransform _topBarContainer`

- `SandboxV2TopBarPanelView _topBarPrefab`

- `Boolean m_inited`

- `SeqNumChecker m_nodeSelectChecker`

- `SeqNumChecker m_dungeonDataChangeChecker`

- `UIPageFinder m_pageFinder`

- `SandboxV2NodePreviewView m_nodePreviewView`

- `UISwitchTween m_nodePreviewViewShowTween`

- `SandboxV2DungeonHomeTipView m_homeTipView`

- `SandboxV2TopBarPanelView m_topBarView`


## Methods

- `Void _InitIfNot()`

- `Void _TutorialOnly_TryRaiseNodePreviewRoutedAVGSignal()`

- `GameObject TutorialOnly_GetCookPanelBtnGo()`

- `GameObject TutorialOnly_GetWorkbenchPanelBtnGo()`

- `GameObject TutorialOnly_GetSphereBtnGo()`

- `GameObject TutorialOnly_GetCrossDayBtnGo()`

- `GameObject TutorialOnly_GetBottomBarHomeBtnGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonView : DataBinder`1
{
	private SandboxV2NodePreviewView _nodePreviewViewPrefab; // 0x20
	private RectTransform _nodePreviewViewHolder; // 0x28
	private CanvasGroup _nodePreviewViewAlphaHandler; // 0x30
	private RectTransform _homeTipViewHolder; // 0x38
	private SandboxV2DungeonSideBar _sideBar; // 0x40
	private SandboxV2DungeonBottomBar _bottomBar; // 0x48
	private RectTransform _topBarContainer; // 0x50
	private SandboxV2TopBarPanelView _topBarPrefab; // 0x58
	private Boolean m_inited; // 0x60
	private SeqNumChecker m_nodeSelectChecker; // 0x68
	private SeqNumChecker m_dungeonDataChangeChecker; // 0x78
	private UIPageFinder m_pageFinder; // 0x88
	private SandboxV2NodePreviewView m_nodePreviewView; // 0x98
	private UISwitchTween m_nodePreviewViewShowTween; // 0xa0
	private SandboxV2DungeonHomeTipView m_homeTipView; // 0xa8
	private SandboxV2TopBarPanelView m_topBarView; // 0xb0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRaiseNodePreviewRoutedAVGSignal; // 0x10
	private static DelegateBridge __Hotfix0_TutorialOnly_GetCookPanelBtnGo; // 0x18
	private static DelegateBridge __Hotfix0_TutorialOnly_GetWorkbenchPanelBtnGo; // 0x20
	private static DelegateBridge __Hotfix0_TutorialOnly_GetSphereBtnGo; // 0x28
	private static DelegateBridge __Hotfix0_TutorialOnly_GetCrossDayBtnGo; // 0x30
	private static DelegateBridge __Hotfix0_TutorialOnly_GetBottomBarHomeBtnGo; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x25ae50c VA: 0x7594bc650c
	private Void _InitIfNot() { }
	// RVA: 0x25ae7f8 VA: 0x7594bc67f8
	public override Void OnValueChanged(SandboxV2DungeonProperty property) { }
	// RVA: 0x25aea50 VA: 0x7594bc6a50
	private Void _TutorialOnly_TryRaiseNodePreviewRoutedAVGSignal() { }
	// RVA: 0x25aeda0 VA: 0x7594bc6da0
	public GameObject TutorialOnly_GetCookPanelBtnGo() { }
	// RVA: 0x25aee14 VA: 0x7594bc6e14
	public GameObject TutorialOnly_GetWorkbenchPanelBtnGo() { }
	// RVA: 0x25aee88 VA: 0x7594bc6e88
	public GameObject TutorialOnly_GetSphereBtnGo() { }
	// RVA: 0x25aef04 VA: 0x7594bc6f04
	public GameObject TutorialOnly_GetCrossDayBtnGo() { }
	// RVA: 0x25aef80 VA: 0x7594bc6f80
	public GameObject TutorialOnly_GetBottomBarHomeBtnGo() { }
	// RVA: 0x25aeffc VA: 0x7594bc6ffc
	public Void .ctor() { }
}
```