# UniEquipUnlockViewModel

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Int32 charInstId`

- `String templateId`

- `UniEquipData uniEquipData`

- `String subProfessionId`

- `Boolean <isPreview>k__BackingField`

- `PlayerCharacter m_playerChar`


## Properties

- `Boolean isPreview`

- `Int32 infoCount`

- `Int32 infoPreviewCount`

- `String equipName`

- `String equipId`


## Methods

- `Void set_isPreview(Boolean)`

- `Boolean get_isPreview()`

- `Int32 get_infoCount()`

- `Int32 get_infoPreviewCount()`

- `Void set_requireViewModels(List`1)`

- `String get_equipName()`

- `String get_equipId()`

- `Void LoadData(PlayerCharacter, CharacterData)`

- `Void RefreshRequires()`

- `Void SetPreviewTrans()`

- `Void _GeneInfoData(PlayerCharacter, CharacterData, Int32)`

- `Void _GeneRequireViewModels()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipUnlockViewModel : IHotfixable
{
	public Int32 charInstId; // 0x10
	public String templateId; // 0x18
	public UniEquipData uniEquipData; // 0x20
	public String subProfessionId; // 0x28
	public List`1 uniEquipMissionList; // 0x30
	public List`1 infoList; // 0x38
	public List`1 infoListPreview; // 0x40
	private Boolean <isPreview>k__BackingField; // 0x48
	private PlayerCharacter m_playerChar; // 0x50
	private List`1 <requireViewModels>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_set_isPreview; // 0x0
	private static DelegateBridge __Hotfix0_get_isPreview; // 0x8
	private static DelegateBridge __Hotfix0_get_infoCount; // 0x10
	private static DelegateBridge __Hotfix0_get_infoPreviewCount; // 0x18
	private static DelegateBridge __Hotfix0_set_requireViewModels; // 0x20
	private static DelegateBridge __Hotfix0_get_requireViewModels; // 0x28
	private static DelegateBridge __Hotfix0_get_equipName; // 0x30
	private static DelegateBridge __Hotfix0_get_equipId; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshRequires; // 0x48
	private static DelegateBridge __Hotfix0_SetPreviewTrans; // 0x50
	private static DelegateBridge __Hotfix0__GeneInfoData; // 0x58
	private static DelegateBridge __Hotfix0__GeneRequireViewModels; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Boolean isPreview { get; set; }
	public Int32 infoCount { get; }
	public Int32 infoPreviewCount { get; }
	public List`1 requireViewModels { get; set; }
	public String equipName { get; }
	public String equipId { get; }

	// RVA: 0x230d8b0 VA: 0x75949258b0
	private Void set_isPreview(Boolean value) { }
	// RVA: 0x230d930 VA: 0x7594925930
	public Boolean get_isPreview() { }
	// RVA: 0x230d998 VA: 0x7594925998
	public Int32 get_infoCount() { }
	// RVA: 0x230da18 VA: 0x7594925a18
	public Int32 get_infoPreviewCount() { }
	// RVA: 0x230da98 VA: 0x7594925a98
	private Void set_requireViewModels(List`1 value) { }
	// RVA: 0x230d4a0 VA: 0x75949254a0
	public List`1 get_requireViewModels() { }
	// RVA: 0x230db1c VA: 0x7594925b1c
	public String get_equipName() { }
	// RVA: 0x230dbb0 VA: 0x7594925bb0
	public String get_equipId() { }
	// RVA: 0x230cf98 VA: 0x7594924f98
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x230d120 VA: 0x7594925120
	public Void RefreshRequires() { }
	// RVA: 0x230ecc8 VA: 0x7594926cc8
	public Void SetPreviewTrans() { }
	// RVA: 0x230dc44 VA: 0x7594925c44
	private Void _GeneInfoData(PlayerCharacter playerChar, CharacterData charData, Int32 equipLevel) { }
	// RVA: 0x230eb20 VA: 0x7594926b20
	private Void _GeneRequireViewModels() { }
	// RVA: 0x230ce50 VA: 0x7594924e50
	public Void .ctor() { }
}
```