# Act1VAutoChessCharSelectDetailPanel

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `UIAnimationLocation _goldSwitchAnim`

- `Text _normalLevel`

- `Image _normalIcon`

- `Text _goldenLevel`

- `Image _goldenIcon`

- `Image _levelIcon`

- `Text _levelText`

- `Image _campLogo`

- `Text _campName`

- `Text _name`

- `Text _codeName`

- `Text _currentLevel`

- `Text _maxLevel`

- `Transform _attrContainer`

- `UICharacterAttackRangeWidget _attackRange`

- `CharSelectSkillGroup _skillGroup`

- `CharSelectBranchGroup _branchGroup`

- `GameObject _panelEmptyInfo`

- `GameObject _panelHaveInfo`

- `GameObject _infoButton`

- `GameObject _disabledInfoBtn`

- `GameObject _predefinedBtn`

- `GameObject _noUniEquip`

- `GameObject _lockedUniEquip`

- `GameObject _haveUniEquip`

- `Image _uniqEquipIcon`

- `Image _subProfessionIcon`

- `GameObject _branchTips`

- `HorizontalLayoutGroup _branchLayout`

- `ButtonType m_selectType`

- `AnimationSwitchTween m_goldSwitch`

- `UIPageFinder m_pageFinder`

- `CommonCharSelectDetailAttrView m_attr`

- `Act1VAutoChessCharSelectDetailViewModel m_cacheModel`

- `Int32 m_branchTopBlank`

- `ICtrl <ctrl>k__BackingField`


## Properties

- `ICtrl ctrl`


## Methods

- `ICtrl get_ctrl()`

- `Void set_ctrl(ICtrl)`

- `Void RenderViewModel(Act1VAutoChessCharSelectDetailViewModel)`

- `Void _InitIfNot()`

- `Act1VAutoChessCharSelectDetailViewModel _GetCachedModel()`

- `Void _RenderEmpty()`

- `Void _RenderCharSelect()`

- `Void _RenderGroup()`

- `Void _RenderUniqEquip(CharSelectBranchGroupViewModel)`

- `Void _SwitchGold(Boolean, Boolean)`

- `Void OnSwitchGold()`

- `Void OnSelectSkill(String)`

- `Void OnSelectEquip(String)`

- `Void OnSelectSkillBar()`

- `Void OnSelectBranchBar()`

- `Void OnChangeState(ButtonType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectDetailPanel : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _goldSwitchAnim; // 0x18
	private Text _normalLevel; // 0x28
	private Image _normalIcon; // 0x30
	private Text _goldenLevel; // 0x38
	private Image _goldenIcon; // 0x40
	private Image _levelIcon; // 0x48
	private Text _levelText; // 0x50
	private Image _campLogo; // 0x58
	private Text _campName; // 0x60
	private Text _name; // 0x68
	private Text _codeName; // 0x70
	private Text _currentLevel; // 0x78
	private Text _maxLevel; // 0x80
	private Transform _attrContainer; // 0x88
	private UICharacterAttackRangeWidget _attackRange; // 0x90
	private CharSelectSkillGroup _skillGroup; // 0x98
	private CharSelectBranchGroup _branchGroup; // 0xa0
	private GameObject _panelEmptyInfo; // 0xa8
	private GameObject _panelHaveInfo; // 0xb0
	private GameObject _infoButton; // 0xb8
	private GameObject _disabledInfoBtn; // 0xc0
	private GameObject _predefinedBtn; // 0xc8
	private GameObject _noUniEquip; // 0xd0
	private GameObject _lockedUniEquip; // 0xd8
	private GameObject _haveUniEquip; // 0xe0
	private Image _uniqEquipIcon; // 0xe8
	private Image _subProfessionIcon; // 0xf0
	private List`1 _buttonList; // 0xf8
	private GameObject _branchTips; // 0x100
	private HorizontalLayoutGroup _branchLayout; // 0x108
	private ButtonType m_selectType; // 0x110
	private AnimationSwitchTween m_goldSwitch; // 0x118
	private UIPageFinder m_pageFinder; // 0x120
	private CommonCharSelectDetailAttrView m_attr; // 0x130
	private Act1VAutoChessCharSelectDetailViewModel m_cacheModel; // 0x138
	private Int32 m_branchTopBlank; // 0x140
	private ICtrl <ctrl>k__BackingField; // 0x148
	private static DelegateBridge __Hotfix0_get_ctrl; // 0x0
	private static DelegateBridge __Hotfix0_set_ctrl; // 0x8
	private static DelegateBridge __Hotfix0_RenderViewModel; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__GetCachedModel; // 0x20
	private static DelegateBridge __Hotfix0__RenderEmpty; // 0x28
	private static DelegateBridge __Hotfix0__RenderCharSelect; // 0x30
	private static DelegateBridge __Hotfix0__RenderGroup; // 0x38
	private static DelegateBridge __Hotfix0__RenderUniqEquip; // 0x40
	private static DelegateBridge __Hotfix0__SwitchGold; // 0x48
	private static DelegateBridge __Hotfix0_OnSwitchGold; // 0x50
	private static DelegateBridge __Hotfix0_OnSelectSkill; // 0x58
	private static DelegateBridge __Hotfix0_OnSelectEquip; // 0x60
	private static DelegateBridge __Hotfix0_OnSelectSkillBar; // 0x68
	private static DelegateBridge __Hotfix0_OnSelectBranchBar; // 0x70
	private static DelegateBridge __Hotfix0_OnChangeState; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public ICtrl ctrl { get; set; }

	// RVA: 0x3386a04 VA: 0x759599ea04
	public ICtrl get_ctrl() { }
	// RVA: 0x3386a6c VA: 0x759599ea6c
	public Void set_ctrl(ICtrl value) { }
	// RVA: 0x3386af0 VA: 0x759599eaf0
	public Void RenderViewModel(Act1VAutoChessCharSelectDetailViewModel subModel) { }
	// RVA: 0x3386ccc VA: 0x759599eccc
	private Void _InitIfNot() { }
	// RVA: 0x3387bf4 VA: 0x759599fbf4
	private Act1VAutoChessCharSelectDetailViewModel _GetCachedModel() { }
	// RVA: 0x3386f3c VA: 0x759599ef3c
	private Void _RenderEmpty() { }
	// RVA: 0x338719c VA: 0x759599f19c
	private Void _RenderCharSelect() { }
	// RVA: 0x33880e0 VA: 0x75959a00e0
	private Void _RenderGroup() { }
	// RVA: 0x3387f98 VA: 0x759599ff98
	private Void _RenderUniqEquip(CharSelectBranchGroupViewModel branch) { }
	// RVA: 0x3387024 VA: 0x759599f024
	private Void _SwitchGold(Boolean isGold, Boolean immediately) { }
	// RVA: 0x33883ac VA: 0x75959a03ac
	public Void OnSwitchGold() { }
	// RVA: 0x33884c4 VA: 0x75959a04c4
	public Void OnSelectSkill(String skillId) { }
	// RVA: 0x33885dc VA: 0x75959a05dc
	public Void OnSelectEquip(String equipId) { }
	// RVA: 0x33886f4 VA: 0x75959a06f4
	public Void OnSelectSkillBar() { }
	// RVA: 0x33887e0 VA: 0x75959a07e0
	public Void OnSelectBranchBar() { }
	// RVA: 0x3388760 VA: 0x75959a0760
	public Void OnChangeState(ButtonType btnType) { }
	// RVA: 0x338884c VA: 0x75959a084c
	public Void .ctor() { }
}
```