# SandboxV2QuestTrackerItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _badgeIcon`

- `Text _title`

- `Text _desc`

- `Text _targetDesc`

- `LayoutElement _layoutElement`

- `Single _foldHeight`

- `Single _expandDuration`

- `Single _expandPadding`

- `GameObject _panelGo`

- `GameObject _panelSwitch`

- `GameObject _panelGoOrSwitch`

- `UIAnimationLocation _selectAnim`

- `Boolean m_isInited`

- `String m_cachedQuestId`

- `Int32 m_cachedEnterSeq`

- `Single m_cachedExpandHeight`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `ILoadAsset m_assetLoader`

- `SandboxV2DungeonViewConfig m_cachedDungeonViewConfig`

- `AnimationSwitchTween m_selectAnimTween`

- `SelectTween m_selectTween`

- `TextGenerator m_textGenerator`

- `TextGenerationSettings m_textSettings`


## Methods

- `Void Render(String, SandboxV2QuestTrackerItemViewModel, Boolean, Int32)`

- `Void _InitIfNot()`

- `Single _GetTextHeight(Text, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2QuestTrackerItemView : MonoBehaviour, IHotfixable
{
	private Image _badgeIcon; // 0x18
	private Text _title; // 0x20
	private Text _desc; // 0x28
	private Text _targetDesc; // 0x30
	private LayoutElement _layoutElement; // 0x38
	private Single _foldHeight; // 0x40
	private Single _expandDuration; // 0x44
	private Single _expandPadding; // 0x48
	private GameObject _panelGo; // 0x50
	private GameObject _panelSwitch; // 0x58
	private GameObject _panelGoOrSwitch; // 0x60
	private UIAnimationLocation _selectAnim; // 0x68
	private Boolean m_isInited; // 0x78
	private String m_cachedQuestId; // 0x80
	private Int32 m_cachedEnterSeq; // 0x88
	private Single m_cachedExpandHeight; // 0x8c
	private UIPageFinder m_pageFinder; // 0x90
	private UIStateFinder m_stateFinder; // 0xa0
	private ILoadAsset m_assetLoader; // 0xb0
	private SandboxV2DungeonViewConfig m_cachedDungeonViewConfig; // 0xb8
	private AnimationSwitchTween m_selectAnimTween; // 0xc0
	private SelectTween m_selectTween; // 0xc8
	private TextGenerator m_textGenerator; // 0xd0
	private TextGenerationSettings m_textSettings; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__GetTextHeight; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2557590 VA: 0x7594b6f590
	public Void Render(String topicId, SandboxV2QuestTrackerItemViewModel viewModel, Boolean isSelected, Int32 enterSeq) { }
	// RVA: 0x25578e8 VA: 0x7594b6f8e8
	private Void _InitIfNot() { }
	// RVA: 0x2557b08 VA: 0x7594b6fb08
	private Single _GetTextHeight(Text text, String content) { }
	// RVA: 0x2557d88 VA: 0x7594b6fd88
	public Void OnClick() { }
	// RVA: 0x2557e90 VA: 0x7594b6fe90
	public Void .ctor() { }
}
```