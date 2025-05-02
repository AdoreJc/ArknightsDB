# SandboxV2AdminMainWorkbenchPanelModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_waterId`

- `String m_goldId`

- `Int32 m_waterStock`

- `Int32 m_goldStock`

- `Boolean m_materialDirty`

- `Boolean m_tacticalActive`

- `Boolean m_tacticalDirty`

- `Boolean m_baseBuildingActive`

- `Boolean m_baseBuildingDirty`

- `Boolean m_combatBuildingActive`

- `Boolean m_combatBuildingDirty`

- `Boolean m_alchemyActive`

- `Boolean m_alchemyDirty`

- `String <topicId>k__BackingField`

- `SandboxV2AdminMainWorkbenchInitParam <initParam>k__BackingField`

- `SandboxV2AdminMainWorkbenchType <currWorkbenchType>k__BackingField`

- `Boolean <initShow>k__BackingField`

- `Boolean <filterCantMake>k__BackingField`


## Properties

- `String topicId`

- `SandboxV2AdminMainWorkbenchInitParam initParam`

- `SandboxV2AdminMainWorkbenchType currWorkbenchType`

- `Boolean initShow`

- `Boolean filterCantMake`

- `Int32 goldStock`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `SandboxV2AdminMainWorkbenchInitParam get_initParam()`

- `Void set_initParam(SandboxV2AdminMainWorkbenchInitParam)`

- `SandboxV2AdminMainWorkbenchType get_currWorkbenchType()`

- `Void set_currWorkbenchType(SandboxV2AdminMainWorkbenchType)`

- `Boolean get_initShow()`

- `Void set_initShow(Boolean)`

- `Boolean get_filterCantMake()`

- `Void set_filterCantMake(Boolean)`

- `Int32 get_goldStock()`

- `Void LoadData(String, SandboxV2AdminMainWorkbenchInitParam)`

- `Void RefreshPlayerData()`

- `Boolean CheckTypeActive(SandboxV2AdminMainWorkbenchType)`

- `Boolean SetWorkbenchType(SandboxV2AdminMainWorkbenchType, Boolean)`

- `Void _LoadCommonItems(SandboxV2Data, PlayerSandboxV2, List`1, List`1, SandboxV2CraftItemType)`

- `Void _LoadAlchemyItems(SandboxV2Data, PlayerSandboxV2)`

- `Void _LoadMaterialsIfNeed(PlayerSandboxV2)`

- `Void _GenerateWaterItem(List`1, Int32, out)`

- `Void _GenerateGoldItem(List`1, Int32, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainWorkbenchPanelModel
{
	private readonly List`1 m_materialItems; // 0x10
	private readonly List`1 m_tacticalItems; // 0x18
	private readonly List`1 m_tacticalItemsFiltered; // 0x20
	private readonly List`1 m_baseBuildingItems; // 0x28
	private readonly List`1 m_baseBuildingItemsFiltered; // 0x30
	private readonly List`1 m_combatBuildingItems; // 0x38
	private readonly List`1 m_combatBuildingItemsFiltered; // 0x40
	private readonly List`1 m_alchemyItems; // 0x48
	private String m_waterId; // 0x50
	private String m_goldId; // 0x58
	private Int32 m_waterStock; // 0x60
	private Int32 m_goldStock; // 0x64
	private Boolean m_materialDirty; // 0x68
	private Boolean m_tacticalActive; // 0x69
	private Boolean m_tacticalDirty; // 0x6a
	private Boolean m_baseBuildingActive; // 0x6b
	private Boolean m_baseBuildingDirty; // 0x6c
	private Boolean m_combatBuildingActive; // 0x6d
	private Boolean m_combatBuildingDirty; // 0x6e
	private Boolean m_alchemyActive; // 0x6f
	private Boolean m_alchemyDirty; // 0x70
	private String <topicId>k__BackingField; // 0x78
	private SandboxV2AdminMainWorkbenchInitParam <initParam>k__BackingField; // 0x80
	private SandboxV2AdminMainWorkbenchType <currWorkbenchType>k__BackingField; // 0x88
	private Boolean <initShow>k__BackingField; // 0x8c
	private Boolean <filterCantMake>k__BackingField; // 0x8d

	public String topicId { get; set; }
	public SandboxV2AdminMainWorkbenchInitParam initParam { get; set; }
	public SandboxV2AdminMainWorkbenchType currWorkbenchType { get; set; }
	public Boolean initShow { get; set; }
	public Boolean filterCantMake { get; set; }
	public List`1 materialItems { get; }
	public Int32 goldStock { get; }

	// RVA: 0x24edca0 VA: 0x7594b05ca0
	public String get_topicId() { }
	// RVA: 0x24edca8 VA: 0x7594b05ca8
	private Void set_topicId(String value) { }
	// RVA: 0x24edcb0 VA: 0x7594b05cb0
	public SandboxV2AdminMainWorkbenchInitParam get_initParam() { }
	// RVA: 0x24edcb8 VA: 0x7594b05cb8
	private Void set_initParam(SandboxV2AdminMainWorkbenchInitParam value) { }
	// RVA: 0x24edcc0 VA: 0x7594b05cc0
	public SandboxV2AdminMainWorkbenchType get_currWorkbenchType() { }
	// RVA: 0x24edcc8 VA: 0x7594b05cc8
	private Void set_currWorkbenchType(SandboxV2AdminMainWorkbenchType value) { }
	// RVA: 0x24edcd0 VA: 0x7594b05cd0
	public Boolean get_initShow() { }
	// RVA: 0x24edcd8 VA: 0x7594b05cd8
	public Void set_initShow(Boolean value) { }
	// RVA: 0x24edce4 VA: 0x7594b05ce4
	public Boolean get_filterCantMake() { }
	// RVA: 0x24edcec VA: 0x7594b05cec
	public Void set_filterCantMake(Boolean value) { }
	// RVA: 0x24edcf8 VA: 0x7594b05cf8
	public List`1 get_materialItems() { }
	// RVA: 0x24edd00 VA: 0x7594b05d00
	public Int32 get_goldStock() { }
	// RVA: 0x24ed4d8 VA: 0x7594b054d8
	public Void LoadData(String topicId, SandboxV2AdminMainWorkbenchInitParam initParam) { }
	// RVA: 0x24ed1a0 VA: 0x7594b051a0
	public Void RefreshPlayerData() { }
	// RVA: 0x24ee730 VA: 0x7594b06730
	public Boolean CheckTypeActive(SandboxV2AdminMainWorkbenchType type) { }
	// RVA: 0x24ee788 VA: 0x7594b06788
	public Boolean SetWorkbenchType(SandboxV2AdminMainWorkbenchType workbenchType, Boolean init) { }
	// RVA: 0x24ed974 VA: 0x7594b05974
	public List`1 GetCurrentItems() { }
	// RVA: 0x24edd08 VA: 0x7594b05d08
	private Void _LoadCommonItems(SandboxV2Data gameData, PlayerSandboxV2 playerData, List`1 list, List`1 listFiltered, SandboxV2CraftItemType type) { }
	// RVA: 0x24ee3a4 VA: 0x7594b063a4
	private Void _LoadAlchemyItems(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24ee99c VA: 0x7594b0699c
	private Void _LoadMaterialsIfNeed(PlayerSandboxV2 playerData) { }
	// RVA: 0x24ee244 VA: 0x7594b06244
	private static Boolean _CheckAlchemyUnlocked(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24eee1c VA: 0x7594b06e1c
	private List`1 _GenerateMaterials(PlayerSandboxV2 playerData, Dictionary`2 materialDict, out Boolean canMake) { }
	// RVA: 0x24ef154 VA: 0x7594b07154
	private List`1 _GenerateMaterials(PlayerSandboxV2 playerData, List`1 materialList, out Boolean canMake) { }
	// RVA: 0x24ef3cc VA: 0x7594b073cc
	private static Void _GenerateMaterialItem(PlayerSandboxV2 playerData, List`1 result, String matId, Int32 matCount, out Boolean valid) { }
	// RVA: 0x24ef594 VA: 0x7594b07594
	private Void _GenerateWaterItem(List`1 result, Int32 waterCount, out Boolean valid) { }
	// RVA: 0x24ef6b8 VA: 0x7594b076b8
	private Void _GenerateGoldItem(List`1 result, Int32 goldCount, out Boolean valid) { }
	// RVA: 0x24ef0a0 VA: 0x7594b070a0
	private static Int32 _GetCommonItemStock(PlayerSandboxV2 playerData, String itemId, SandboxV2CraftItemType type) { }
	// RVA: 0x24ef7dc VA: 0x7594b077dc
	private static Int32 _MatComparison(SandboxV2AdminMainMaterialModel x, SandboxV2AdminMainMaterialModel y) { }
	// RVA: 0x24ef850 VA: 0x7594b07850
	private static Int32 _ItemComparison(SandboxV2WorkbenchItemModel x, SandboxV2WorkbenchItemModel y) { }
	// RVA: 0x24ef8f8 VA: 0x7594b078f8
	public Void .ctor() { }
}
```