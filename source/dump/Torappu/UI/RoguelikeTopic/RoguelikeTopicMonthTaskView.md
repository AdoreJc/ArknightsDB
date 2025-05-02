# RoguelikeTopicMonthTaskView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `SimpleLayoutContent _taskList`

- `Text _textRule`

- `Text _textRefreshCount`

- `Text _textUpdateTime`

- `Text _textUpdateCaption`

- `Text _textFinishCaption`

- `UIAtlasImage _imgGreyMask`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `UIPageFinder m_pageFinder`


## Methods

- `Void set_onTaskRefreshAction(Action`1)`

- `Void _InitIfNot()`

- `Void PlayAnim(RoguelikeTopicMonthTaskModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthTaskView : DataBinder`1
{
	private SimpleLayoutContent _taskList; // 0x20
	private Text _textRule; // 0x28
	private Text _textRefreshCount; // 0x30
	private Text _textUpdateTime; // 0x38
	private Text _textUpdateCaption; // 0x40
	private Text _textFinishCaption; // 0x48
	private UIAtlasImage _imgGreyMask; // 0x50
	private Action`1 <onTaskRefreshAction>k__BackingField; // 0x58
	private Boolean m_hasInited; // 0x60
	private Adapter m_adapter; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private static DelegateBridge __Hotfix0_get_onTaskRefreshAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onTaskRefreshAction; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onTaskRefreshAction { get; set; }

	// RVA: 0x265b884 VA: 0x7594c73884
	private Action`1 get_onTaskRefreshAction() { }
	// RVA: 0x2659918 VA: 0x7594c71918
	public Void set_onTaskRefreshAction(Action`1 value) { }
	// RVA: 0x265b8ec VA: 0x7594c738ec
	public override Void OnValueChanged(RoguelikeTopicMonthTaskProperty property) { }
	// RVA: 0x265bc9c VA: 0x7594c73c9c
	private Void _InitIfNot() { }
	// RVA: 0x265a7b4 VA: 0x7594c727b4
	public Void PlayAnim(RoguelikeTopicMonthTaskModel taskModel) { }
	// RVA: 0x265bfd0 VA: 0x7594c73fd0
	public Void .ctor() { }
}
```