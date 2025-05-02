# Rl01OuterBuffItemDetailView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `RectTransform _panel`

- `Image _buffIcon`

- `Text _buffName`

- `Text _buffType`

- `Text _buffEffect`

- `Rl01OuterBuffConfirmButton _confirmButton`

- `String m_cachedBuffId`

- `RoguelikeTopicOuterBuffSkillTreeModel m_cachedModel`

- `Rl01TopicOuterBuffController <bindTopicController>k__BackingField`

- `Rl01OuterBuffView <outerBuffView>k__BackingField`


## Properties

- `Rl01TopicOuterBuffController bindTopicController`

- `Rl01OuterBuffView outerBuffView`

- `RectTransform panel`


## Methods

- `Rl01TopicOuterBuffController get_bindTopicController()`

- `Void set_bindTopicController(Rl01TopicOuterBuffController)`

- `Rl01OuterBuffView get_outerBuffView()`

- `Void set_outerBuffView(Rl01OuterBuffView)`

- `RectTransform get_panel()`

- `Void Init(Rl01OuterBuffView, Rl01TopicOuterBuffController)`

- `Void _Render(RoguelikeTopicOuterBuffSkillTreeModel)`

- `Void UpgradeNodeClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01OuterBuffItemDetailView : DataBinder`1
{
	private RectTransform _panel; // 0x20
	private Image _buffIcon; // 0x28
	private Text _buffName; // 0x30
	private Text _buffType; // 0x38
	private Text _buffEffect; // 0x40
	private Rl01OuterBuffConfirmButton _confirmButton; // 0x48
	private String m_cachedBuffId; // 0x50
	private RoguelikeTopicOuterBuffSkillTreeModel m_cachedModel; // 0x58
	private Rl01TopicOuterBuffController <bindTopicController>k__BackingField; // 0x60
	private Rl01OuterBuffView <outerBuffView>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_bindTopicController; // 0x0
	private static DelegateBridge __Hotfix0_set_bindTopicController; // 0x8
	private static DelegateBridge __Hotfix0_get_outerBuffView; // 0x10
	private static DelegateBridge __Hotfix0_set_outerBuffView; // 0x18
	private static DelegateBridge __Hotfix0_get_panel; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0__Render; // 0x38
	private static DelegateBridge __Hotfix0_UpgradeNodeClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Rl01TopicOuterBuffController bindTopicController { get; set; }
	private Rl01OuterBuffView outerBuffView { get; set; }
	public RectTransform panel { get; }

	// RVA: 0x26c7674 VA: 0x7594cdf674
	private Rl01TopicOuterBuffController get_bindTopicController() { }
	// RVA: 0x26c76dc VA: 0x7594cdf6dc
	private Void set_bindTopicController(Rl01TopicOuterBuffController value) { }
	// RVA: 0x26c7760 VA: 0x7594cdf760
	private Rl01OuterBuffView get_outerBuffView() { }
	// RVA: 0x26c77c8 VA: 0x7594cdf7c8
	private Void set_outerBuffView(Rl01OuterBuffView value) { }
	// RVA: 0x26c784c VA: 0x7594cdf84c
	public RectTransform get_panel() { }
	// RVA: 0x26c78b4 VA: 0x7594cdf8b4
	public Void Init(Rl01OuterBuffView view, Rl01TopicOuterBuffController topicController) { }
	// RVA: 0x26c7948 VA: 0x7594cdf948
	public override Void OnValueChanged(RoguelikeTopicOuterBuffSkillTreeProperty property) { }
	// RVA: 0x26c79f0 VA: 0x7594cdf9f0
	private Void _Render(RoguelikeTopicOuterBuffSkillTreeModel model) { }
	// RVA: 0x26c7f84 VA: 0x7594cdff84
	public Void UpgradeNodeClicked() { }
	// RVA: 0x26c8178 VA: 0x7594ce0178
	public Void .ctor() { }
}
```