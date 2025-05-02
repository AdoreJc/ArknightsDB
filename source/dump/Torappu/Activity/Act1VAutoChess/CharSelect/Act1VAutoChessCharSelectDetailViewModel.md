# Act1VAutoChessCharSelectDetailViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `AttributesData m_attrData`

- `AttackRangeDescModel m_attackRange`

- `Act1VAutoChessShopCharChessCardViewModel <targetChessModel>k__BackingField`

- `CharacterData <charData>k__BackingField`

- `Act1VAutoChessCultivateRelationData <cultivateEffect>k__BackingField`

- `Act1VAutoChessCharShopChessData <shopChessData>k__BackingField`

- `Act1VAutoChessCharChessStatusData <normalStatusData>k__BackingField`

- `Act1VAutoChessCharChessStatusData <goldenStatusData>k__BackingField`

- `Act1VAutoChessFactionData <charFactionData>k__BackingField`

- `CharSelectBranchGroupViewModel <branchViewModel>k__BackingField`

- `CharSelectSkillGroupViewModel <skillViewModel>k__BackingField`

- `Boolean <isGold>k__BackingField`

- `Act1VAutoChessCharSelectCardViewModel m_targetChar`


## Properties

- `Act1VAutoChessShopCharChessCardViewModel targetChessModel`

- `AttributesData attributesData`

- `CharacterData charData`

- `Act1VAutoChessCultivateRelationData cultivateEffect`

- `Act1VAutoChessCharShopChessData shopChessData`

- `Act1VAutoChessCharChessStatusData normalStatusData`

- `Act1VAutoChessCharChessStatusData goldenStatusData`

- `Act1VAutoChessFactionData charFactionData`

- `CharSelectBranchGroupViewModel branchViewModel`

- `CharSelectSkillGroupViewModel skillViewModel`

- `Boolean isGold`

- `AttackRangeDescModel attackRange`


## Methods

- `Act1VAutoChessShopCharChessCardViewModel get_targetChessModel()`

- `Void set_targetChessModel(Act1VAutoChessShopCharChessCardViewModel)`

- `AttributesData get_attributesData()`

- `CharacterData get_charData()`

- `Void set_charData(CharacterData)`

- `Act1VAutoChessCultivateRelationData get_cultivateEffect()`

- `Void set_cultivateEffect(Act1VAutoChessCultivateRelationData)`

- `Act1VAutoChessCharShopChessData get_shopChessData()`

- `Void set_shopChessData(Act1VAutoChessCharShopChessData)`

- `Act1VAutoChessCharChessStatusData get_normalStatusData()`

- `Void set_normalStatusData(Act1VAutoChessCharChessStatusData)`

- `Act1VAutoChessCharChessStatusData get_goldenStatusData()`

- `Void set_goldenStatusData(Act1VAutoChessCharChessStatusData)`

- `Act1VAutoChessFactionData get_charFactionData()`

- `Void set_charFactionData(Act1VAutoChessFactionData)`

- `CharSelectBranchGroupViewModel get_branchViewModel()`

- `Void set_branchViewModel(CharSelectBranchGroupViewModel)`

- `CharSelectSkillGroupViewModel get_skillViewModel()`

- `Void set_skillViewModel(CharSelectSkillGroupViewModel)`

- `Boolean get_isGold()`

- `Void set_isGold(Boolean)`

- `AttackRangeDescModel get_attackRange()`

- `Boolean SwitchGold(Boolean)`

- `Void UpdateWitchChessModel(ActivityAutoChessVerify1Data, Act1VAutoChessShopCharChessCardViewModel, Boolean)`

- `Void _UpdateViewModel(ActivityAutoChessVerify1Data, Act1VAutoChessShopCharChessCardViewModel, ChessData, Boolean)`

- `Void _UpdateAttrData(Act1VAutoChessShopCharChessCardViewModel, Boolean)`

- `Void _UpdateSkillViewModel(Boolean)`

- `CharSelectSkillItemViewModel _CreateSkill(Act1VAutoChessCharChessStatusData, Int32, Int32, Int32)`

- `Void _UpdateBranchViewModel(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectDetailViewModel : TemplateCharSelectDetailViewModelBase`1
{
	private AttributesData m_attrData; // 0x10
	private AttackRangeDescModel m_attackRange; // 0x18
	private Act1VAutoChessShopCharChessCardViewModel <targetChessModel>k__BackingField; // 0x28
	private CharacterData <charData>k__BackingField; // 0x30
	private Act1VAutoChessCultivateRelationData <cultivateEffect>k__BackingField; // 0x38
	private Act1VAutoChessCharShopChessData <shopChessData>k__BackingField; // 0x40
	private Act1VAutoChessCharChessStatusData <normalStatusData>k__BackingField; // 0x48
	private Act1VAutoChessCharChessStatusData <goldenStatusData>k__BackingField; // 0x50
	private Act1VAutoChessFactionData <charFactionData>k__BackingField; // 0x58
	private CharSelectBranchGroupViewModel <branchViewModel>k__BackingField; // 0x60
	private CharSelectSkillGroupViewModel <skillViewModel>k__BackingField; // 0x68
	private Boolean <isGold>k__BackingField; // 0x70
	private Act1VAutoChessCharSelectCardViewModel m_targetChar; // 0x78
	private static DelegateBridge __Hotfix0_get_targetChessModel; // 0x0
	private static DelegateBridge __Hotfix0_set_targetChessModel; // 0x8
	private static DelegateBridge __Hotfix0_get_attributesData; // 0x10
	private static DelegateBridge __Hotfix0_get_charData; // 0x18
	private static DelegateBridge __Hotfix0_set_charData; // 0x20
	private static DelegateBridge __Hotfix0_get_cultivateEffect; // 0x28
	private static DelegateBridge __Hotfix0_set_cultivateEffect; // 0x30
	private static DelegateBridge __Hotfix0_get_shopChessData; // 0x38
	private static DelegateBridge __Hotfix0_set_shopChessData; // 0x40
	private static DelegateBridge __Hotfix0_get_normalStatusData; // 0x48
	private static DelegateBridge __Hotfix0_set_normalStatusData; // 0x50
	private static DelegateBridge __Hotfix0_get_goldenStatusData; // 0x58
	private static DelegateBridge __Hotfix0_set_goldenStatusData; // 0x60
	private static DelegateBridge __Hotfix0_get_charFactionData; // 0x68
	private static DelegateBridge __Hotfix0_set_charFactionData; // 0x70
	private static DelegateBridge __Hotfix0_get_branchViewModel; // 0x78
	private static DelegateBridge __Hotfix0_set_branchViewModel; // 0x80
	private static DelegateBridge __Hotfix0_get_skillViewModel; // 0x88
	private static DelegateBridge __Hotfix0_set_skillViewModel; // 0x90
	private static DelegateBridge __Hotfix0_get_isGold; // 0x98
	private static DelegateBridge __Hotfix0_set_isGold; // 0xa0
	private static DelegateBridge __Hotfix0_get_attackRange; // 0xa8
	private static DelegateBridge __Hotfix0_SwitchGold; // 0xb0
	private static DelegateBridge __Hotfix0_get_targetChar; // 0xb8
	private static DelegateBridge __Hotfix0_OnUpdateWithChar; // 0xc0
	private static DelegateBridge __Hotfix0_UpdateWitchChessModel; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateViewModel; // 0xd0
	private static DelegateBridge __Hotfix0__UpdateAttrData; // 0xd8
	private static DelegateBridge __Hotfix0__UpdateSkillViewModel; // 0xe0
	private static DelegateBridge __Hotfix0__CreateSkill; // 0xe8
	private static DelegateBridge __Hotfix0__UpdateBranchViewModel; // 0xf0
	private static DelegateBridge __Hotfix0__InstTemplateCharSelectBranchViewModel; // 0xf8
	private static DelegateBridge __Hotfix0_Reset; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	public Act1VAutoChessShopCharChessCardViewModel targetChessModel { get; set; }
	public AttributesData attributesData { get; }
	public CharacterData charData { get; set; }
	public Act1VAutoChessCultivateRelationData cultivateEffect { get; set; }
	public Act1VAutoChessCharShopChessData shopChessData { get; set; }
	public Act1VAutoChessCharChessStatusData normalStatusData { get; set; }
	public Act1VAutoChessCharChessStatusData goldenStatusData { get; set; }
	public Act1VAutoChessFactionData charFactionData { get; set; }
	public CharSelectBranchGroupViewModel branchViewModel { get; set; }
	public CharSelectSkillGroupViewModel skillViewModel { get; set; }
	public Boolean isGold { get; set; }
	public AttackRangeDescModel attackRange { get; }
	public override TemplateCharSelectCardViewModel targetChar { get; }

	// RVA: 0x3386ed4 VA: 0x759599eed4
	public Act1VAutoChessShopCharChessCardViewModel get_targetChessModel() { }
	// RVA: 0x3388e4c VA: 0x75959a0e4c
	private Void set_targetChessModel(Act1VAutoChessShopCharChessCardViewModel value) { }
	// RVA: 0x3387e64 VA: 0x759599fe64
	public AttributesData get_attributesData() { }
	// RVA: 0x3387dfc VA: 0x759599fdfc
	public CharacterData get_charData() { }
	// RVA: 0x3388ed0 VA: 0x75959a0ed0
	private Void set_charData(CharacterData value) { }
	// RVA: 0x3387d94 VA: 0x759599fd94
	public Act1VAutoChessCultivateRelationData get_cultivateEffect() { }
	// RVA: 0x3388f54 VA: 0x75959a0f54
	private Void set_cultivateEffect(Act1VAutoChessCultivateRelationData value) { }
	// RVA: 0x3387d2c VA: 0x759599fd2c
	public Act1VAutoChessCharShopChessData get_shopChessData() { }
	// RVA: 0x3388fd8 VA: 0x75959a0fd8
	private Void set_shopChessData(Act1VAutoChessCharShopChessData value) { }
	// RVA: 0x3387cc4 VA: 0x759599fcc4
	public Act1VAutoChessCharChessStatusData get_normalStatusData() { }
	// RVA: 0x338905c VA: 0x75959a105c
	private Void set_normalStatusData(Act1VAutoChessCharChessStatusData value) { }
	// RVA: 0x3387c5c VA: 0x759599fc5c
	public Act1VAutoChessCharChessStatusData get_goldenStatusData() { }
	// RVA: 0x33890e0 VA: 0x75959a10e0
	private Void set_goldenStatusData(Act1VAutoChessCharChessStatusData value) { }
	// RVA: 0x3387134 VA: 0x759599f134
	public Act1VAutoChessFactionData get_charFactionData() { }
	// RVA: 0x3389164 VA: 0x75959a1164
	private Void set_charFactionData(Act1VAutoChessFactionData value) { }
	// RVA: 0x3387f30 VA: 0x759599ff30
	public CharSelectBranchGroupViewModel get_branchViewModel() { }
	// RVA: 0x33891e8 VA: 0x75959a11e8
	private Void set_branchViewModel(CharSelectBranchGroupViewModel value) { }
	// RVA: 0x3388344 VA: 0x75959a0344
	public CharSelectSkillGroupViewModel get_skillViewModel() { }
	// RVA: 0x338926c VA: 0x75959a126c
	private Void set_skillViewModel(CharSelectSkillGroupViewModel value) { }
	// RVA: 0x3386fbc VA: 0x759599efbc
	public Boolean get_isGold() { }
	// RVA: 0x33892f0 VA: 0x75959a12f0
	private Void set_isGold(Boolean value) { }
	// RVA: 0x3387ecc VA: 0x759599fecc
	public AttackRangeDescModel get_attackRange() { }
	// RVA: 0x3388b3c VA: 0x75959a0b3c
	public Boolean SwitchGold(Boolean gold) { }
	// RVA: 0x338a01c VA: 0x75959a201c
	public override TemplateCharSelectCardViewModel get_targetChar() { }
	// RVA: 0x338a084 VA: 0x75959a2084
	protected override Void OnUpdateWithChar(Act1VAutoChessCharSelectCardViewModel charModel, Boolean forceUpdate) { }
	// RVA: 0x338a68c VA: 0x75959a268c
	public Void UpdateWitchChessModel(ActivityAutoChessVerify1Data actData, Act1VAutoChessShopCharChessCardViewModel chessModel, Boolean forceUpdate) { }
	// RVA: 0x338a20c VA: 0x75959a220c
	private Void _UpdateViewModel(ActivityAutoChessVerify1Data actData, Act1VAutoChessShopCharChessCardViewModel chessModel, ChessData chessData, Boolean forceUpdate) { }
	// RVA: 0x3389cac VA: 0x75959a1cac
	private Void _UpdateAttrData(Act1VAutoChessShopCharChessCardViewModel chessModel, Boolean aIsGold) { }
	// RVA: 0x3389370 VA: 0x75959a1370
	private Void _UpdateSkillViewModel(Boolean forceRefresh) { }
	// RVA: 0x338a82c VA: 0x75959a282c
	private CharSelectSkillItemViewModel _CreateSkill(Act1VAutoChessCharChessStatusData chessAttr, Int32 allLevel, Int32 specLevel, Int32 skillIndex) { }
	// RVA: 0x3389734 VA: 0x75959a1734
	private Void _UpdateBranchViewModel(Boolean forceRefresh) { }
	// RVA: 0x338ab1c VA: 0x75959a2b1c
	private static CharSelectBranchGroupViewModel _InstTemplateCharSelectBranchViewModel(PlayerBranchParam branchParam, CharacterData charData, String equipId, String limitEquip) { }
	// RVA: 0x338b360 VA: 0x75959a3360
	public override Void Reset(TemplateCharSelectModelResetData data) { }
	// RVA: 0x338b3e4 VA: 0x75959a33e4
	public Void .ctor() { }
}
```