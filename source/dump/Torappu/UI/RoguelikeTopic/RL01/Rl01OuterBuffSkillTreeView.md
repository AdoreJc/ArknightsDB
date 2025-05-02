# Rl01OuterBuffSkillTreeView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `RectTransform _panel`

- `RectTransform _content`

- `Tween m_focusTween`

- `String m_cachedFocusItem`

- `Rl01TopicOuterBuffController <bindTopicController>k__BackingField`


## Properties

- `Rl01TopicOuterBuffController bindTopicController`

- `RectTransform panel`


## Methods

- `Rl01TopicOuterBuffController get_bindTopicController()`

- `Void set_bindTopicController(Rl01TopicOuterBuffController)`

- `RectTransform get_panel()`

- `Void Init(Rl01TopicOuterBuffController)`

- `Void ResetView()`

- `Void ShowView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01OuterBuffSkillTreeView : DataBinder`1
{
	private const Single FOCUS_DURATION; // 0x0
	private const Single FOCUS_START_DELTA; // 0x0
	private List`1 _mainNodeStageNumSpriteList; // 0x20
	private List`1 _progressNodeProgressBarSpriteList; // 0x28
	private RectTransform _panel; // 0x30
	private List`1 _nodes; // 0x38
	private RectTransform _content; // 0x40
	private Dictionary`2 m_nodesDict; // 0x48
	private Tween m_focusTween; // 0x50
	private String m_cachedFocusItem; // 0x58
	private Rl01TopicOuterBuffController <bindTopicController>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_nodes; // 0x0
	private static DelegateBridge __Hotfix0_get_progressNodeProgressBarSpriteList; // 0x8
	private static DelegateBridge __Hotfix0_get_mainNodeStageNumSpriteList; // 0x10
	private static DelegateBridge __Hotfix0_get_bindTopicController; // 0x18
	private static DelegateBridge __Hotfix0_set_bindTopicController; // 0x20
	private static DelegateBridge __Hotfix0_get_panel; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0_ResetView; // 0x40
	private static DelegateBridge __Hotfix0_ShowView; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public List`1 nodes { get; }
	public List`1 progressNodeProgressBarSpriteList { get; }
	public List`1 mainNodeStageNumSpriteList { get; }
	private Rl01TopicOuterBuffController bindTopicController { get; set; }
	public RectTransform panel { get; }

	// RVA: 0x26d08d0 VA: 0x7594ce88d0
	public List`1 get_nodes() { }
	// RVA: 0x26cf320 VA: 0x7594ce7320
	public List`1 get_progressNodeProgressBarSpriteList() { }
	// RVA: 0x26cdf2c VA: 0x7594ce5f2c
	public List`1 get_mainNodeStageNumSpriteList() { }
	// RVA: 0x26d0938 VA: 0x7594ce8938
	private Rl01TopicOuterBuffController get_bindTopicController() { }
	// RVA: 0x26d09a0 VA: 0x7594ce89a0
	private Void set_bindTopicController(Rl01TopicOuterBuffController value) { }
	// RVA: 0x26d0a24 VA: 0x7594ce8a24
	public RectTransform get_panel() { }
	// RVA: 0x26d0a8c VA: 0x7594ce8a8c
	public Void Init(Rl01TopicOuterBuffController topicController) { }
	// RVA: 0x26d0c90 VA: 0x7594ce8c90
	public override Void OnValueChanged(RoguelikeTopicOuterBuffSkillTreeProperty property) { }
	// RVA: 0x26d0e48 VA: 0x7594ce8e48
	public Void ResetView() { }
	// RVA: 0x26d0f1c VA: 0x7594ce8f1c
	public Void ShowView() { }
	// RVA: 0x26d1168 VA: 0x7594ce9168
	public Void .ctor() { }
}
```