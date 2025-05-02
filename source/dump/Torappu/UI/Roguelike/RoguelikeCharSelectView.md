# RoguelikeCharSelectView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Transform _controllerContainer`

- `RoguelikeCharSelectAttrController _controller`

- `RoguelikeCharSelectAttrController m_controller`

- `RoguelikeCharRecycleAdapter _adapter`

- `GameObject _popPart`

- `RoguelikePopBarView _popText`

- `GameObject _emptyPart`

- `RoguelikeCharAttrTabTypeMessage onAttrTabClickEvent`

- `UIStringEvent onSkillSelectEvent`

- `UIStringEvent onBranchSelectEvent`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void InjectPlugin(IRoguelikeCharCardPlugin)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectView : DataBinder`1, IHotfixable
{
	private Transform _controllerContainer; // 0x20
	private RoguelikeCharSelectAttrController _controller; // 0x28
	private RoguelikeCharSelectAttrController m_controller; // 0x30
	private RoguelikeCharRecycleAdapter _adapter; // 0x38
	private GameObject _popPart; // 0x40
	private RoguelikePopBarView _popText; // 0x48
	private GameObject _emptyPart; // 0x50
	private RoguelikeCharAttrTabTypeMessage onAttrTabClickEvent; // 0x58
	private UIStringEvent onSkillSelectEvent; // 0x60
	private UIStringEvent onBranchSelectEvent; // 0x68
	private Boolean m_isInited; // 0x70
	private List`1 m_plugins; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2acf2cc VA: 0x75950e72cc
	private Void _InitIfNot() { }
	// RVA: 0x2acf3b4 VA: 0x75950e73b4
	public override Void OnValueChanged(RoguelikeSelectCharProperty property) { }
	// RVA: 0x2ac5654 VA: 0x75950dd654
	public Void InjectPlugin(IRoguelikeCharCardPlugin plugin) { }
	// RVA: 0x2acf9e4 VA: 0x75950e79e4
	public Void .ctor() { }
}
```