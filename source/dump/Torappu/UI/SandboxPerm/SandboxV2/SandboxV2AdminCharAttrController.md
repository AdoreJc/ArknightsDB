# SandboxV2AdminCharAttrController

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


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

- `SandboxV2AdminFoodAttrPanel _foodGroup`

- `GameObject _panelEmptyInfo`

- `GameObject _panelNormal`

- `GameObject _noUniEquip`

- `GameObject _lockedUniEquip`

- `GameObject _haveUniEquip`

- `Image _uniqEquipIcon`

- `Image _subProfessionIcon`

- `CanvasGroup _attrPart`

- `GameObject _statePart`

- `GameObject _supplyPart`

- `GameObject _expedPart`

- `Text _expedDay`

- `Int32 m_chrInstIdCache`

- `UIStateFinder m_stateFinder`


## Methods

- `Void RenderCharAttr(SandboxV2CharViewModel, SandboxV2CharSelectTabEnum)`

- `Void _RenderTab(SandboxV2CharViewModel, SandboxV2CharSelectTabEnum)`

- `Void _RenderSkillGroup(SandboxV2CharViewModel)`

- `Void _RenderBranchGroup(SandboxV2CharViewModel)`

- `Void _RenderFoodGroup(SandboxV2CharViewModel)`

- `Void _LoadUniqEquip(SandboxV2CharViewModel)`

- `Void InitWithPage(ILoadAsset)`

- `Void OnCharSkillSelect(String)`

- `Void OnCharEquipSelect(String)`

- `Void OnToCharInfoPage()`

- `Void OnToEatFood()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminCharAttrController : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private Text _codeName; // 0x20
	private Text _currentLevel; // 0x28
	private Text _maxLevel; // 0x30
	private Text _maxHp; // 0x38
	private Text _atk; // 0x40
	private Text _def; // 0x48
	private Text _res; // 0x50
	private Text _reviveTimeDesc; // 0x58
	private Text _cost; // 0x60
	private Text _blockNum; // 0x68
	private Text _attackSpeedDesc; // 0x70
	private Image _atkIcon; // 0x78
	private Image _defIcon; // 0x80
	private Image _maxHpIcon; // 0x88
	private Image _resIcon; // 0x90
	private Image _reviveIcon; // 0x98
	private Image _costIcon; // 0xa0
	private Image _blockIcon; // 0xa8
	private Image _attackSpeedIcon; // 0xb0
	private UICharacterAttackRangeWidget _attackRange; // 0xb8
	private CharSelectSkillGroup _skillGroup; // 0xc0
	private CharSelectBranchGroup _branchGroup; // 0xc8
	private SandboxV2AdminFoodAttrPanel _foodGroup; // 0xd0
	private GameObject _panelEmptyInfo; // 0xd8
	private GameObject _panelNormal; // 0xe0
	private GameObject _noUniEquip; // 0xe8
	private GameObject _lockedUniEquip; // 0xf0
	private GameObject _haveUniEquip; // 0xf8
	private Image _uniqEquipIcon; // 0x100
	private Image _subProfessionIcon; // 0x108
	private List`1 _attrTabItems; // 0x110
	private CanvasGroup _attrPart; // 0x118
	private GameObject _statePart; // 0x120
	private GameObject _supplyPart; // 0x128
	private GameObject _expedPart; // 0x130
	private Text _expedDay; // 0x138
	private Int32 m_chrInstIdCache; // 0x140
	private UIStateFinder m_stateFinder; // 0x148
	private static DelegateBridge __Hotfix0_RenderCharAttr; // 0x0
	private static DelegateBridge __Hotfix0__RenderTab; // 0x8
	private static DelegateBridge __Hotfix0__RenderSkillGroup; // 0x10
	private static DelegateBridge __Hotfix0__RenderBranchGroup; // 0x18
	private static DelegateBridge __Hotfix0__RenderFoodGroup; // 0x20
	private static DelegateBridge __Hotfix0__LoadUniqEquip; // 0x28
	private static DelegateBridge __Hotfix0_InitWithPage; // 0x30
	private static DelegateBridge __Hotfix0_OnCharSkillSelect; // 0x38
	private static DelegateBridge __Hotfix0_OnCharEquipSelect; // 0x40
	private static DelegateBridge __Hotfix0_OnToCharInfoPage; // 0x48
	private static DelegateBridge __Hotfix0_OnToEatFood; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x24857d0 VA: 0x7594a9d7d0
	public Void RenderCharAttr(SandboxV2CharViewModel viewModel, SandboxV2CharSelectTabEnum tabEnum) { }
	// RVA: 0x2485d40 VA: 0x7594a9dd40
	private Void _RenderTab(SandboxV2CharViewModel viewModel, SandboxV2CharSelectTabEnum type) { }
	// RVA: 0x24862a4 VA: 0x7594a9e2a4
	private Void _RenderSkillGroup(SandboxV2CharViewModel viewModel) { }
	// RVA: 0x2486424 VA: 0x7594a9e424
	private Void _RenderBranchGroup(SandboxV2CharViewModel viewModel) { }
	// RVA: 0x24865a4 VA: 0x7594a9e5a4
	private Void _RenderFoodGroup(SandboxV2CharViewModel viewModel) { }
	// RVA: 0x2485ea8 VA: 0x7594a9dea8
	private Void _LoadUniqEquip(SandboxV2CharViewModel viewModel) { }
	// RVA: 0x2485ff8 VA: 0x7594a9dff8
	public Void InitWithPage(ILoadAsset assets) { }
	// RVA: 0x2486818 VA: 0x7594a9e818
	public Void OnCharSkillSelect(String skillId) { }
	// RVA: 0x2486924 VA: 0x7594a9e924
	public Void OnCharEquipSelect(String equipId) { }
	// RVA: 0x2486a30 VA: 0x7594a9ea30
	public Void OnToCharInfoPage() { }
	// RVA: 0x2486ae4 VA: 0x7594a9eae4
	public Void OnToEatFood() { }
	// RVA: 0x2486b98 VA: 0x7594a9eb98
	public Void .ctor() { }
}
```