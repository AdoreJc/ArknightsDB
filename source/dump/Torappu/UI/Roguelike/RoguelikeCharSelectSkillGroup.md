# RoguelikeCharSelectSkillGroup

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `SimpleLayoutContent _skillLayout`

- `GameObject _panelDisable`

- `Text _textDisable`

- `ScrollRect _skillScroll`

- `SkillAdapter m_adapter`

- `Boolean m_isInited`

- `String m_lastActiveChar`

- `UIStringEvent m_onSkillSelected`


## Methods

- `Void _InitIfNot()`

- `Void _OnSkillClicked(String)`

- `Void RenderSkills(RoguelikeCharSelectSkillGroupViewModel, UIStringEvent)`

- `Boolean _UpdateLastActiveChar(RoguelikeCharSelectSkillGroupViewModel)`

- `Void _ResetSkillScroll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectSkillGroup : MonoBehaviour
{
	private SimpleLayoutContent _skillLayout; // 0x18
	private GameObject _panelDisable; // 0x20
	private Text _textDisable; // 0x28
	private ScrollRect _skillScroll; // 0x30
	private SkillAdapter m_adapter; // 0x38
	private Boolean m_isInited; // 0x40
	private String m_lastActiveChar; // 0x48
	private UIStringEvent m_onSkillSelected; // 0x50


	// RVA: 0x2ace164 VA: 0x75950e6164
	private Void _InitIfNot() { }
	// RVA: 0x2ace17c VA: 0x75950e617c
	private Void _OnSkillClicked(String skillId) { }
	// RVA: 0x2acc8c0 VA: 0x75950e48c0
	public Void RenderSkills(RoguelikeCharSelectSkillGroupViewModel viewModel, UIStringEvent onSkillSelect) { }
	// RVA: 0x2ace24c VA: 0x75950e624c
	private Boolean _UpdateLastActiveChar(RoguelikeCharSelectSkillGroupViewModel viewModel) { }
	// RVA: 0x2ace2b4 VA: 0x75950e62b4
	private Void _ResetSkillScroll() { }
	// RVA: 0x2ace33c VA: 0x75950e633c
	public Void .ctor() { }
}
```