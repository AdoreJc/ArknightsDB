# CharacterShowSkillItem

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `GameObject _panelEnable`

- `GameObject _panelLocked`

- `GameObject _panelEmpty`

- `GameObject _selectFrame`

- `Image _imageSkill`

- `Text _textCost`

- `Text _textInit`

- `Text _textName`

- `GameObject _skillCost`

- `GameObject _skillInit`

- `GameObject _iconSpecGo`

- `Image _imgSpecIcon`

- `Text _textMainLv`

- `UIColorGraphic _colorGraphic`

- `Single _skillUnselectAlpha`

- `UIStateFinder m_stateFinder`

- `CharacterShowSkillModel m_skillModel`


## Methods

- `Void Render(CharacterShowSkillModel, Boolean, Boolean)`

- `Void _SetSkillItemShowType(Boolean, Boolean, Boolean, Boolean)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowSkillItem : MonoBehaviour, IHotfixable
{
	private GameObject _panelEnable; // 0x18
	private GameObject _panelLocked; // 0x20
	private GameObject _panelEmpty; // 0x28
	private GameObject _selectFrame; // 0x30
	private Image _imageSkill; // 0x38
	private Text _textCost; // 0x40
	private Text _textInit; // 0x48
	private Text _textName; // 0x50
	private GameObject _skillCost; // 0x58
	private GameObject _skillInit; // 0x60
	private GameObject _iconSpecGo; // 0x68
	private Image _imgSpecIcon; // 0x70
	private Text _textMainLv; // 0x78
	private UIColorGraphic _colorGraphic; // 0x80
	private Single _skillUnselectAlpha; // 0x88
	private UIStateFinder m_stateFinder; // 0x90
	private CharacterShowSkillModel m_skillModel; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__SetSkillItemShowType; // 0x8
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ce73d8 VA: 0x75952ff3d8
	public Void Render(CharacterShowSkillModel skillModel, Boolean isSelected, Boolean isSelectedVisible) { }
	// RVA: 0x2ce7c68 VA: 0x75952ffc68
	private Void _SetSkillItemShowType(Boolean isEmpty, Boolean isUnlock, Boolean isSelected, Boolean isSelectedVisible) { }
	// RVA: 0x2ce7d58 VA: 0x75952ffd58
	public Void EventOnItemClick() { }
	// RVA: 0x2ce7e60 VA: 0x75952ffe60
	public Void .ctor() { }
}
```