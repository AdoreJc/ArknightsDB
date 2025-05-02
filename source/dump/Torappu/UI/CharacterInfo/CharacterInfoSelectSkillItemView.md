# CharacterInfoSelectSkillItemView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _panelEnable`

- `GameObject _panelLocked`

- `GameObject _panelEmpty`

- `Image _imageSkillIcon`

- `Text _textCost`

- `Text _textName`

- `UISkillTagGroup _tagGroup`

- `Text _textDesc`

- `UIFontSizeVerticalFitter _descFitter`

- `TwoStateToggle _selectToggle`

- `Text _textUnlockCond`

- `Text _skillLvl`

- `Image _skillSpeicializedImage`

- `Int32 m_indexCache`

- `String m_skillIdCache`


## Methods

- `Void Render(SkillItemViewModel, Int32, Boolean)`

- `Void EventOnToggleButtonClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSelectSkillItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEnable; // 0x18
	private GameObject _panelLocked; // 0x20
	private GameObject _panelEmpty; // 0x28
	private Image _imageSkillIcon; // 0x30
	private Text _textCost; // 0x38
	private Text _textName; // 0x40
	private UISkillTagGroup _tagGroup; // 0x48
	private Text _textDesc; // 0x50
	private UIFontSizeVerticalFitter _descFitter; // 0x58
	private TwoStateToggle _selectToggle; // 0x60
	private Text _textUnlockCond; // 0x68
	private Text _skillLvl; // 0x70
	private Image _skillSpeicializedImage; // 0x78
	private Int32 m_indexCache; // 0x80
	private String m_skillIdCache; // 0x88
	public Action`1 onToggleClick; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnToggleButtonClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d888b0 VA: 0x75953a08b0
	public Void Render(SkillItemViewModel viewModel, Int32 index, Boolean isSelected) { }
	// RVA: 0x2d88c0c VA: 0x75953a0c0c
	public Void EventOnToggleButtonClick() { }
	// RVA: 0x2d88c94 VA: 0x75953a0c94
	public Void .ctor() { }
}
```