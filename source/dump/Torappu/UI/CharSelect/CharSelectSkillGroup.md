# CharSelectSkillGroup

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `SimpleLayoutContent _skillLayout`

- `GameObject _panelDisable`

- `Text _textDisable`

- `ScrollRect _skillScroll`

- `SkillSelectEvent _onSkillSelected`

- `SkillAdapter m_adapter`

- `Boolean m_isInited`

- `String m_lastActiveChar`


## Methods

- `Void _InitIfNot()`

- `Void _OnSkillClicked(String)`

- `Void RenderSkills(CharSelectSkillGroupViewModel)`

- `Boolean _UpdateLastActiveChar(CharSelectSkillGroupViewModel)`

- `Void _ResetSkillScroll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectSkillGroup : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _skillLayout; // 0x18
	private GameObject _panelDisable; // 0x20
	private Text _textDisable; // 0x28
	private ScrollRect _skillScroll; // 0x30
	private SkillSelectEvent _onSkillSelected; // 0x38
	private SkillAdapter m_adapter; // 0x40
	private Boolean m_isInited; // 0x48
	private String m_lastActiveChar; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__OnSkillClicked; // 0x8
	private static DelegateBridge __Hotfix0_RenderSkills; // 0x10
	private static DelegateBridge __Hotfix0__UpdateLastActiveChar; // 0x18
	private static DelegateBridge __Hotfix0__ResetSkillScroll; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2cf6888 VA: 0x759530e888
	private Void _InitIfNot() { }
	// RVA: 0x2cf68fc VA: 0x759530e8fc
	private Void _OnSkillClicked(String skillId) { }
	// RVA: 0x2cf3b6c VA: 0x759530bb6c
	public Void RenderSkills(CharSelectSkillGroupViewModel viewModel) { }
	// RVA: 0x2cf6a18 VA: 0x759530ea18
	private Boolean _UpdateLastActiveChar(CharSelectSkillGroupViewModel viewModel) { }
	// RVA: 0x2cf6ad8 VA: 0x759530ead8
	private Void _ResetSkillScroll() { }
	// RVA: 0x2cf6b98 VA: 0x759530eb98
	public Void .ctor() { }
}
```