# UniEquipArchiveModuleCollectionItemViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `String <uniEquipId>k__BackingField`

- `String <typeIcon>k__BackingField`

- `UniEquipType <type>k__BackingField`

- `String <equipShiningColor>k__BackingField`

- `String <typeName1>k__BackingField`

- `String <typeName2>k__BackingField`

- `CharQuery <charQuery>k__BackingField`

- `String <charName>k__BackingField`

- `Int32 <charInstId>k__BackingField`

- `Boolean <isTmpl>k__BackingField`

- `Boolean <isCurrentTmpl>k__BackingField`

- `UniEquipArchiveModuleItemBaseViewModel m_itemBaseViewModel`

- `String m_tmplId`

- `String m_currentTmplId`


## Properties

- `String uniEquipId`

- `String typeIcon`

- `UniEquipType type`

- `String equipShiningColor`

- `String typeName1`

- `String typeName2`

- `CharQuery charQuery`

- `String charName`

- `Int32 charInstId`

- `Boolean isTmpl`

- `Boolean isCurrentTmpl`

- `UniEquipArchiveModuleItemBaseViewModel itemBaseViewModel`


## Methods

- `String get_uniEquipId()`

- `Void set_uniEquipId(String)`

- `String get_typeIcon()`

- `Void set_typeIcon(String)`

- `UniEquipType get_type()`

- `Void set_type(UniEquipType)`

- `String get_equipShiningColor()`

- `Void set_equipShiningColor(String)`

- `String get_typeName1()`

- `Void set_typeName1(String)`

- `String get_typeName2()`

- `Void set_typeName2(String)`

- `Void set_missionList(List`1)`

- `CharQuery get_charQuery()`

- `Void set_charQuery(CharQuery)`

- `String get_charName()`

- `Void set_charName(String)`

- `Int32 get_charInstId()`

- `Void set_charInstId(Int32)`

- `Boolean get_isTmpl()`

- `Void set_isTmpl(Boolean)`

- `Boolean get_isCurrentTmpl()`

- `Void set_isCurrentTmpl(Boolean)`

- `UniEquipArchiveModuleItemBaseViewModel get_itemBaseViewModel()`

- `Void LoadData(PlayerCharacter, UniEquipData)`

- `Void RefreshData(PlayerCharacter)`

- `Void _LoadBasicData(PlayerCharacter, UniEquipData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveModuleCollectionItemViewModel : IHotfixable
{
	private String <uniEquipId>k__BackingField; // 0x10
	private String <typeIcon>k__BackingField; // 0x18
	private UniEquipType <type>k__BackingField; // 0x20
	private String <equipShiningColor>k__BackingField; // 0x28
	private String <typeName1>k__BackingField; // 0x30
	private String <typeName2>k__BackingField; // 0x38
	private List`1 <missionList>k__BackingField; // 0x40
	private CharQuery <charQuery>k__BackingField; // 0x48
	private String <charName>k__BackingField; // 0x60
	private Int32 <charInstId>k__BackingField; // 0x68
	private Boolean <isTmpl>k__BackingField; // 0x6c
	private Boolean <isCurrentTmpl>k__BackingField; // 0x6d
	private UniEquipArchiveModuleItemBaseViewModel m_itemBaseViewModel; // 0x70
	private String m_tmplId; // 0x78
	private String m_currentTmplId; // 0x80
	private static DelegateBridge __Hotfix0_get_uniEquipId; // 0x0
	private static DelegateBridge __Hotfix0_set_uniEquipId; // 0x8
	private static DelegateBridge __Hotfix0_get_typeIcon; // 0x10
	private static DelegateBridge __Hotfix0_set_typeIcon; // 0x18
	private static DelegateBridge __Hotfix0_get_type; // 0x20
	private static DelegateBridge __Hotfix0_set_type; // 0x28
	private static DelegateBridge __Hotfix0_get_equipShiningColor; // 0x30
	private static DelegateBridge __Hotfix0_set_equipShiningColor; // 0x38
	private static DelegateBridge __Hotfix0_get_typeName1; // 0x40
	private static DelegateBridge __Hotfix0_set_typeName1; // 0x48
	private static DelegateBridge __Hotfix0_get_typeName2; // 0x50
	private static DelegateBridge __Hotfix0_set_typeName2; // 0x58
	private static DelegateBridge __Hotfix0_get_missionList; // 0x60
	private static DelegateBridge __Hotfix0_set_missionList; // 0x68
	private static DelegateBridge __Hotfix0_get_charQuery; // 0x70
	private static DelegateBridge __Hotfix0_set_charQuery; // 0x78
	private static DelegateBridge __Hotfix0_get_charName; // 0x80
	private static DelegateBridge __Hotfix0_set_charName; // 0x88
	private static DelegateBridge __Hotfix0_get_charInstId; // 0x90
	private static DelegateBridge __Hotfix0_set_charInstId; // 0x98
	private static DelegateBridge __Hotfix0_get_isTmpl; // 0xa0
	private static DelegateBridge __Hotfix0_set_isTmpl; // 0xa8
	private static DelegateBridge __Hotfix0_get_isCurrentTmpl; // 0xb0
	private static DelegateBridge __Hotfix0_set_isCurrentTmpl; // 0xb8
	private static DelegateBridge __Hotfix0_get_itemBaseViewModel; // 0xc0
	private static DelegateBridge __Hotfix0_LoadData; // 0xc8
	private static DelegateBridge __Hotfix0_RefreshData; // 0xd0
	private static DelegateBridge __Hotfix0__LoadBasicData; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0

	public String uniEquipId { get; set; }
	public String typeIcon { get; set; }
	public UniEquipType type { get; set; }
	public String equipShiningColor { get; set; }
	public String typeName1 { get; set; }
	public String typeName2 { get; set; }
	public List`1 missionList { get; set; }
	public CharQuery charQuery { get; set; }
	public String charName { get; set; }
	public Int32 charInstId { get; set; }
	public Boolean isTmpl { get; set; }
	public Boolean isCurrentTmpl { get; set; }
	public UniEquipArchiveModuleItemBaseViewModel itemBaseViewModel { get; }

	// RVA: 0x22f09fc VA: 0x75949089fc
	public String get_uniEquipId() { }
	// RVA: 0x22f8c40 VA: 0x7594910c40
	private Void set_uniEquipId(String value) { }
	// RVA: 0x22f0a64 VA: 0x7594908a64
	public String get_typeIcon() { }
	// RVA: 0x22f8cc4 VA: 0x7594910cc4
	private Void set_typeIcon(String value) { }
	// RVA: 0x22f0c2c VA: 0x7594908c2c
	public UniEquipType get_type() { }
	// RVA: 0x22f8d48 VA: 0x7594910d48
	private Void set_type(UniEquipType value) { }
	// RVA: 0x22f0c94 VA: 0x7594908c94
	public String get_equipShiningColor() { }
	// RVA: 0x22f8dc4 VA: 0x7594910dc4
	private Void set_equipShiningColor(String value) { }
	// RVA: 0x22f0d64 VA: 0x7594908d64
	public String get_typeName1() { }
	// RVA: 0x22f8e48 VA: 0x7594910e48
	private Void set_typeName1(String value) { }
	// RVA: 0x22f0cfc VA: 0x7594908cfc
	public String get_typeName2() { }
	// RVA: 0x22f8ecc VA: 0x7594910ecc
	private Void set_typeName2(String value) { }
	// RVA: 0x22f8f50 VA: 0x7594910f50
	public List`1 get_missionList() { }
	// RVA: 0x22f8fb8 VA: 0x7594910fb8
	private Void set_missionList(List`1 value) { }
	// RVA: 0x22f0b34 VA: 0x7594908b34
	public CharQuery get_charQuery() { }
	// RVA: 0x22f903c VA: 0x759491103c
	private Void set_charQuery(CharQuery value) { }
	// RVA: 0x22f0bc4 VA: 0x7594908bc4
	public String get_charName() { }
	// RVA: 0x22f90ec VA: 0x75949110ec
	private Void set_charName(String value) { }
	// RVA: 0x22f9170 VA: 0x7594911170
	public Int32 get_charInstId() { }
	// RVA: 0x22f91d8 VA: 0x75949111d8
	private Void set_charInstId(Int32 value) { }
	// RVA: 0x22f9254 VA: 0x7594911254
	public Boolean get_isTmpl() { }
	// RVA: 0x22f92bc VA: 0x75949112bc
	private Void set_isTmpl(Boolean value) { }
	// RVA: 0x22f933c VA: 0x759491133c
	public Boolean get_isCurrentTmpl() { }
	// RVA: 0x22f93a4 VA: 0x75949113a4
	private Void set_isCurrentTmpl(Boolean value) { }
	// RVA: 0x22f0840 VA: 0x7594908840
	public UniEquipArchiveModuleItemBaseViewModel get_itemBaseViewModel() { }
	// RVA: 0x22f72ac VA: 0x759490f2ac
	public Void LoadData(PlayerCharacter playerChar, UniEquipData equipData) { }
	// RVA: 0x22f747c VA: 0x759490f47c
	public Void RefreshData(PlayerCharacter playerChar) { }
	// RVA: 0x22f9424 VA: 0x7594911424
	private Void _LoadBasicData(PlayerCharacter playerCharacter, UniEquipData equipData) { }
	// RVA: 0x22f723c VA: 0x759490f23c
	public Void .ctor() { }
}
```