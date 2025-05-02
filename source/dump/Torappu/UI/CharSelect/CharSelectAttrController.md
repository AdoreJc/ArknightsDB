# CharSelectAttrController

**Namespace:** `Torappu.UI.CharSelect`


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

- `Image _atkIcon`

- `Image _defIcon`

- `Image _maxHpIcon`

- `Image _resIcon`

- `Image _reviveIcon`

- `Image _costIcon`

- `Image _blockIcon`

- `Image _attackSpeedIcon`

- `UICharacterAttackRangeWidget _attackRange`

- `CharSelectSkillGroup _skillGroup`

- `CharSelectBranchGroup _branchGroup`

- `GameObject _panelEmptyInfo`

- `GameObject _infoButton`

- `GameObject _disabledInfoBtn`

- `GameObject _predefinedBtn`

- `GameObject _noUniEquip`

- `GameObject _lockedUniEquip`

- `GameObject _haveUniEquip`

- `Image _uniqEquipIcon`

- `Image _subProfessionIcon`

- `String uipageName`

- `Int32 m_chrInstIdCache`


## Methods

- `Void _RenderTab(CharAttrViewModel)`

- `Void _RenderSkillGroup(CharAttrViewModel)`

- `Void _RenderBranchGroup(CharAttrViewModel)`

- `Void _LoadUniqEquip(CharAttrViewModel)`

- `Void InitWithPage(UIPage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectAttrController : DataBinder`1
{
	private Text _name; // 0x20
	private Text _codeName; // 0x28
	private Text _currentLevel; // 0x30
	private Text _maxLevel; // 0x38
	private Text _maxHp; // 0x40
	private Text _atk; // 0x48
	private Text _def; // 0x50
	private Text _res; // 0x58
	private Text _reviveTimeDesc; // 0x60
	private Text _cost; // 0x68
	private Text _blockNum; // 0x70
	private Text _attackSpeedDesc; // 0x78
	private Image _atkIcon; // 0x80
	private Image _defIcon; // 0x88
	private Image _maxHpIcon; // 0x90
	private Image _resIcon; // 0x98
	private Image _reviveIcon; // 0xa0
	private Image _costIcon; // 0xa8
	private Image _blockIcon; // 0xb0
	private Image _attackSpeedIcon; // 0xb8
	private UICharacterAttackRangeWidget _attackRange; // 0xc0
	private CharSelectSkillGroup _skillGroup; // 0xc8
	private CharSelectBranchGroup _branchGroup; // 0xd0
	private GameObject _panelEmptyInfo; // 0xd8
	private GameObject _infoButton; // 0xe0
	private GameObject _disabledInfoBtn; // 0xe8
	private GameObject _predefinedBtn; // 0xf0
	private GameObject _noUniEquip; // 0xf8
	private GameObject _lockedUniEquip; // 0x100
	private GameObject _haveUniEquip; // 0x108
	private Image _uniqEquipIcon; // 0x110
	private Image _subProfessionIcon; // 0x118
	public String uipageName; // 0x120
	private Int32 m_chrInstIdCache; // 0x128
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderTab; // 0x8
	private static DelegateBridge __Hotfix0__RenderSkillGroup; // 0x10
	private static DelegateBridge __Hotfix0__RenderBranchGroup; // 0x18
	private static DelegateBridge __Hotfix0__LoadUniqEquip; // 0x20
	private static DelegateBridge __Hotfix0_InitWithPage; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2cf3324 VA: 0x759530b324
	public override Void OnValueChanged(CharAttrViewProperty property) { }
	// RVA: 0x2cf37d8 VA: 0x759530b7d8
	private Void _RenderTab(CharAttrViewModel viewModel) { }
	// RVA: 0x2cf39e4 VA: 0x759530b9e4
	private Void _RenderSkillGroup(CharAttrViewModel viewModel) { }
	// RVA: 0x2cf3aa8 VA: 0x759530baa8
	private Void _RenderBranchGroup(CharAttrViewModel viewModel) { }
	// RVA: 0x2cf3898 VA: 0x759530b898
	private Void _LoadUniqEquip(CharAttrViewModel viewModel) { }
	// RVA: 0x2cf4064 VA: 0x759530c064
	public Void InitWithPage(UIPage page) { }
	// RVA: 0x2cf421c VA: 0x759530c21c
	public Void .ctor() { }
}
```