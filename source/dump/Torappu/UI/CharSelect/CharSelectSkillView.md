# CharSelectSkillView

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `Image _skillIcon`

- `Text _skillName`

- `GameObject _defaultSkillTag`

- `Transform _skillTagLayout`

- `UISkillTagGroup _skillTagGroup`

- `Text _spCost`

- `Text _skillDesc`

- `Boolean _darkColorDescComment`

- `Text _textDisable`

- `CanvasGroup _selectedAlpha`

- `GameObject _panelInitCost`

- `Text _textInitCost`

- `Image _skillLevelIcon`

- `GameObject _activePart`

- `GameObject _unActivePart`

- `GameObject _disablePart`

- `GameObject _panelLock`

- `Text _lockText`

- `Image _unlockIcon`

- `GameObject _panelSkillLevel`

- `Text _textSkillLevel`

- `Boolean m_isUnlockedCache`

- `Boolean m_isInited`

- `String m_skillId`

- `UICommentedText m_commentSkillDesc`

- `Boolean m_isSelected`

- `FadeSwitchTween m_selectedSwitch`


## Properties

- `Boolean showDefaultSkillTag`


## Methods

- `Boolean get_showDefaultSkillTag()`

- `Void set_showDefaultSkillTag(Boolean)`

- `Void set_onSkillClicked(Action`1)`

- `Void Render(CharSelectSkillItemViewModel, Boolean)`

- `Void OnSkillClicked()`

- `Void _InitIfNot()`

- `Void _SetUnlockState(Boolean)`

- `Void _SetSelectedStatus(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectSkillView : MonoBehaviour, IHotfixable
{
	private Image _skillIcon; // 0x18
	private Text _skillName; // 0x20
	private GameObject _defaultSkillTag; // 0x28
	private Transform _skillTagLayout; // 0x30
	private UISkillTagGroup _skillTagGroup; // 0x38
	private Text _spCost; // 0x40
	private Text _skillDesc; // 0x48
	private Boolean _darkColorDescComment; // 0x50
	private Text _textDisable; // 0x58
	private CanvasGroup _selectedAlpha; // 0x60
	private GameObject _panelInitCost; // 0x68
	private Text _textInitCost; // 0x70
	private Sprite[] _skillLevelImages; // 0x78
	private Image _skillLevelIcon; // 0x80
	private GameObject _activePart; // 0x88
	private GameObject _unActivePart; // 0x90
	private GameObject _disablePart; // 0x98
	private GameObject _panelLock; // 0xa0
	private Text _lockText; // 0xa8
	private Image _unlockIcon; // 0xb0
	private Sprite[] _unlcokSprites; // 0xb8
	private GameObject _panelSkillLevel; // 0xc0
	private Text _textSkillLevel; // 0xc8
	private Boolean m_isUnlockedCache; // 0xd0
	private Boolean m_isInited; // 0xd1
	private String m_skillId; // 0xd8
	private Action`1 m_onSkillClicked; // 0xe0
	private SkillTagViewModel[] m_tagCache; // 0xe8
	private UICommentedText m_commentSkillDesc; // 0xf0
	private Boolean m_isSelected; // 0xf8
	private FadeSwitchTween m_selectedSwitch; // 0x100
	private static DelegateBridge __Hotfix0_get_showDefaultSkillTag; // 0x0
	private static DelegateBridge __Hotfix0_set_showDefaultSkillTag; // 0x8
	private static DelegateBridge __Hotfix0_set_onSkillClicked; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_OnSkillClicked; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__SetUnlockState; // 0x30
	private static DelegateBridge __Hotfix0__SetSelectedStatus; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean showDefaultSkillTag { get; set; }
	public Action`1 onSkillClicked { set; }

	// RVA: 0x2cf74ec VA: 0x759530f4ec
	public Boolean get_showDefaultSkillTag() { }
	// RVA: 0x2cf6f54 VA: 0x759530ef54
	public Void set_showDefaultSkillTag(Boolean value) { }
	// RVA: 0x2cf7008 VA: 0x759530f008
	public Void set_onSkillClicked(Action`1 value) { }
	// RVA: 0x2cf708c VA: 0x759530f08c
	public Void Render(CharSelectSkillItemViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x2cf77d0 VA: 0x759530f7d0
	public Void OnSkillClicked() { }
	// RVA: 0x2cf7560 VA: 0x759530f560
	private Void _InitIfNot() { }
	// RVA: 0x2cf7740 VA: 0x759530f740
	private Void _SetUnlockState(Boolean isUnlock) { }
	// RVA: 0x2cf75e8 VA: 0x759530f5e8
	private Void _SetSelectedStatus(Boolean isSelected) { }
	// RVA: 0x2cf7858 VA: 0x759530f858
	public Void .ctor() { }
}
```