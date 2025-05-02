# CommonCharSelectDetailDefaultView

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `Text _name`

- `Text _codeName`

- `Text _currentLevel`

- `Text _maxLevel`

- `Text _maxHp`

- `Text _atk`

- `Text _def`

- `Text _res`

- `Text _reviveTimeDesc`

- `Text _cost`

- `Text _blockNum`

- `Text _attackSpeedDesc`

- `Image _iconMaxHp`

- `Image _iconAtk`

- `Image _iconDef`

- `Image _iconRes`

- `Image _iconReviveTime`

- `Image _iconCost`

- `Image _iconBlockNum`

- `Image _iconAtkSpeed`

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

- `ButtonType m_selectType`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _RenderEmpty()`

- `Void _RenderCharSelect()`

- `Void _SetAttrSprite(Image, CharacterSortType)`

- `Void _RenderGroup()`

- `Void _RenderUniqEquip(CharSelectBranchGroupViewModel)`

- `Void OnSelectSkill(String)`

- `Void OnSelectEquip(String)`

- `Void OnSelectSkillBar()`

- `Void OnSelectBranchBar()`

- `Void OnChangeState(ButtonType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectDetailDefaultView : TemplateCharSelectDetailViewBase`1
{
	private Text _name; // 0x30
	private Text _codeName; // 0x38
	private Text _currentLevel; // 0x40
	private Text _maxLevel; // 0x48
	private Text _maxHp; // 0x50
	private Text _atk; // 0x58
	private Text _def; // 0x60
	private Text _res; // 0x68
	private Text _reviveTimeDesc; // 0x70
	private Text _cost; // 0x78
	private Text _blockNum; // 0x80
	private Text _attackSpeedDesc; // 0x88
	private Image _iconMaxHp; // 0x90
	private Image _iconAtk; // 0x98
	private Image _iconDef; // 0xa0
	private Image _iconRes; // 0xa8
	private Image _iconReviveTime; // 0xb0
	private Image _iconCost; // 0xb8
	private Image _iconBlockNum; // 0xc0
	private Image _iconAtkSpeed; // 0xc8
	private UICharacterAttackRangeWidget _attackRange; // 0xd0
	private CharSelectSkillGroup _skillGroup; // 0xd8
	private CharSelectBranchGroup _branchGroup; // 0xe0
	private GameObject _panelEmptyInfo; // 0xe8
	private GameObject _panelHaveInfo; // 0xf0
	private GameObject _infoButton; // 0xf8
	private GameObject _disabledInfoBtn; // 0x100
	private GameObject _predefinedBtn; // 0x108
	private GameObject _noUniEquip; // 0x110
	private GameObject _lockedUniEquip; // 0x118
	private GameObject _haveUniEquip; // 0x120
	private Image _uniqEquipIcon; // 0x128
	private Image _subProfessionIcon; // 0x130
	private List`1 _buttonList; // 0x138
	private ButtonType m_selectType; // 0x140
	private UIPageFinder m_pageFinder; // 0x148
	private static DelegateBridge __Hotfix0_OnRenderViewModel; // 0x0
	private static DelegateBridge __Hotfix0__RenderEmpty; // 0x8
	private static DelegateBridge __Hotfix0__RenderCharSelect; // 0x10
	private static DelegateBridge __Hotfix0__SetAttrSprite; // 0x18
	private static DelegateBridge __Hotfix0__RenderGroup; // 0x20
	private static DelegateBridge __Hotfix0__RenderUniqEquip; // 0x28
	private static DelegateBridge __Hotfix0_OnSelectSkill; // 0x30
	private static DelegateBridge __Hotfix0_OnSelectEquip; // 0x38
	private static DelegateBridge __Hotfix0_OnSelectSkillBar; // 0x40
	private static DelegateBridge __Hotfix0_OnSelectBranchBar; // 0x48
	private static DelegateBridge __Hotfix0_OnChangeState; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2c53f1c VA: 0x759526bf1c
	protected override Void OnRenderViewModel() { }
	// RVA: 0x2c53fd8 VA: 0x759526bfd8
	private Void _RenderEmpty() { }
	// RVA: 0x2c54058 VA: 0x759526c058
	private Void _RenderCharSelect() { }
	// RVA: 0x2c54598 VA: 0x759526c598
	private Void _SetAttrSprite(Image imgIcon, CharacterSortType sortType) { }
	// RVA: 0x2c54844 VA: 0x759526c844
	private Void _RenderGroup() { }
	// RVA: 0x2c546fc VA: 0x759526c6fc
	private Void _RenderUniqEquip(CharSelectBranchGroupViewModel branch) { }
	// RVA: 0x2c54b30 VA: 0x759526cb30
	public Void OnSelectSkill(String skillId) { }
	// RVA: 0x2c54c00 VA: 0x759526cc00
	public Void OnSelectEquip(String equipId) { }
	// RVA: 0x2c54cd0 VA: 0x759526ccd0
	public Void OnSelectSkillBar() { }
	// RVA: 0x2c54dbc VA: 0x759526cdbc
	public Void OnSelectBranchBar() { }
	// RVA: 0x2c54d3c VA: 0x759526cd3c
	public Void OnChangeState(ButtonType btnType) { }
	// RVA: 0x2c54e28 VA: 0x759526ce28
	public Void .ctor() { }
}
```