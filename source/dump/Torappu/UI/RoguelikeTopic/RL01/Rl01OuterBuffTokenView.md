# Rl01OuterBuffTokenView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `Text _textTokenNum`

- `Text _textTokenName`

- `UIAtlasImage _iconToken`

- `UIAtlasImage _imgAllCompleted`

- `UIAtlasImage _bkgLeft`

- `UIAtlasImage _bkg`

- `CanvasGroup _pnlNotCompleted`

- `CanvasGroup _pnlCompleted`

- `String m_cachedTopicId`

- `SwitchTween m_switchTween`

- `Rl01TopicOuterBuffController <bindTopicController>k__BackingField`


## Properties

- `Rl01TopicOuterBuffController bindTopicController`


## Methods

- `Rl01TopicOuterBuffController get_bindTopicController()`

- `Void set_bindTopicController(Rl01TopicOuterBuffController)`

- `Void _Render(RoguelikeTopicOuterBuffSkillTreeModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01OuterBuffTokenView : DataBinder`1
{
	private Text _textTokenNum; // 0x20
	private Text _textTokenName; // 0x28
	private UIAtlasImage _iconToken; // 0x30
	private UIAtlasImage _imgAllCompleted; // 0x38
	private UIAtlasImage _bkgLeft; // 0x40
	private UIAtlasImage _bkg; // 0x48
	private CanvasGroup _pnlNotCompleted; // 0x50
	private CanvasGroup _pnlCompleted; // 0x58
	private String m_cachedTopicId; // 0x60
	private SwitchTween m_switchTween; // 0x68
	private Rl01TopicOuterBuffController <bindTopicController>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_bindTopicController; // 0x0
	private static DelegateBridge __Hotfix0_set_bindTopicController; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Rl01TopicOuterBuffController bindTopicController { get; set; }

	// RVA: 0x26d129c VA: 0x7594ce929c
	private Rl01TopicOuterBuffController get_bindTopicController() { }
	// RVA: 0x26d1304 VA: 0x7594ce9304
	private Void set_bindTopicController(Rl01TopicOuterBuffController value) { }
	// RVA: 0x26d1388 VA: 0x7594ce9388
	public virtual Void Init(Rl01TopicOuterBuffController topicController) { }
	// RVA: 0x26d14dc VA: 0x7594ce94dc
	public override Void OnValueChanged(RoguelikeTopicOuterBuffSkillTreeProperty property) { }
	// RVA: 0x26d1584 VA: 0x7594ce9584
	private Void _Render(RoguelikeTopicOuterBuffSkillTreeModel model) { }
	// RVA: 0x26d167c VA: 0x7594ce967c
	public Void .ctor() { }
}
```