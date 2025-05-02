# Act6FunZoneMapStagePreviewInfoPanel

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `Text _txtPassTime`

- `SimpleLayoutContent _starList`

- `SimpleLayoutContent _descList`

- `Image _imgChar`

- `Text _txtNpcDialog`

- `UIAnimationLocation _animationLocation`

- `Boolean m_hasInited`

- `String m_cachedStageId`

- `Act6FunZoneMapStagePreviewPluginViewModel m_stagePreviewPluginViewModel`

- `AchieveStarItemListAdapter m_starAdapter`

- `AchieveDescItemAdapter m_descAdapter`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_showTween`


## Methods

- `Void EventOnCharPreviewItemClick()`

- `Void _InitPanelIfNot()`

- `Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler, StageViewModel)`

- `Void <>xLuaBaseProxy_RefreshView(IStageSelectHandler, StageViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapStagePreviewInfoPanel : StagePreviewInfoBasicPanel
{
	private Text _txtPassTime; // 0x148
	private SimpleLayoutContent _starList; // 0x150
	private SimpleLayoutContent _descList; // 0x158
	private Image _imgChar; // 0x160
	private Text _txtNpcDialog; // 0x168
	private UIAnimationLocation _animationLocation; // 0x170
	private Boolean m_hasInited; // 0x180
	private String m_cachedStageId; // 0x188
	private Act6FunZoneMapStagePreviewPluginViewModel m_stagePreviewPluginViewModel; // 0x190
	private AchieveStarItemListAdapter m_starAdapter; // 0x198
	private AchieveDescItemAdapter m_descAdapter; // 0x1a0
	private UIPageFinder m_pageFinder; // 0x1a8
	private AnimationSwitchTween m_showTween; // 0x1b8
	private static DelegateBridge __Hotfix0_OnZoneViewChanged; // 0x0
	private static DelegateBridge __Hotfix0_RefreshView; // 0x8
	private static DelegateBridge __Hotfix0_SelectStageViewModel; // 0x10
	private static DelegateBridge __Hotfix0_CheckToShow; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCharPreviewItemClick; // 0x20
	private static DelegateBridge __Hotfix0__InitPanelIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31b74e4 VA: 0x75957cf4e4
	protected override Boolean OnZoneViewChanged(IStageSelectHandler zoneModel, StageViewModel stageModel) { }
	// RVA: 0x31b79ec VA: 0x75957cf9ec
	protected override Void RefreshView(IStageSelectHandler zoneModel, StageViewModel selectedStage) { }
	// RVA: 0x31b7a80 VA: 0x75957cfa80
	protected override Boolean SelectStageViewModel(IStageSelectHandler zoneModel, out StageViewModel stageModel) { }
	// RVA: 0x31b7b94 VA: 0x75957cfb94
	protected override Boolean CheckToShow(IStageSelectHandler zoneModel) { }
	// RVA: 0x31b7c10 VA: 0x75957cfc10
	public Void EventOnCharPreviewItemClick() { }
	// RVA: 0x31b786c VA: 0x75957cf86c
	private Void _InitPanelIfNot() { }
	// RVA: 0x31b7dd4 VA: 0x75957cfdd4
	public Void .ctor() { }
	// RVA: 0x31b7e7c VA: 0x75957cfe7c
	private Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler P0, StageViewModel P1) { }
	// RVA: 0x31b7e84 VA: 0x75957cfe84
	private Void <>xLuaBaseProxy_RefreshView(IStageSelectHandler P0, StageViewModel P1) { }
}
```