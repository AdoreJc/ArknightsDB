# CharacterInfoSkillIconView

**Namespace:** `Torappu.UI.CharacterInfo`


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

- `Image _skillLevelIcon`


## Methods

- `Void Render(SkillItemViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSkillIconView : MonoBehaviour, IHotfixable
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
	private Image _skillLevelIcon; // 0x68
	private Sprite[] _levelIconList; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d872c8 VA: 0x759539f2c8
	public Void Render(SkillItemViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x2d89014 VA: 0x75953a1014
	public Void .ctor() { }
}
```