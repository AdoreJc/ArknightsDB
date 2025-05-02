# NameCardV2EquipmentCollectionInfoItemViewModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `UniEquipArchiveCollectionInfoType <type>k__BackingField`

- `String <infoName>k__BackingField`

- `Int32 <curCount>k__BackingField`

- `Int32 <totalCount>k__BackingField`

- `Boolean <showTotalCount>k__BackingField`


## Properties

- `UniEquipArchiveCollectionInfoType type`

- `String infoName`

- `Int32 curCount`

- `Int32 totalCount`

- `Boolean showTotalCount`


## Methods

- `UniEquipArchiveCollectionInfoType get_type()`

- `Void set_type(UniEquipArchiveCollectionInfoType)`

- `String get_infoName()`

- `Void set_infoName(String)`

- `Int32 get_curCount()`

- `Void set_curCount(Int32)`

- `Int32 get_totalCount()`

- `Void set_totalCount(Int32)`

- `Boolean get_showTotalCount()`

- `Void set_showTotalCount(Boolean)`

- `Void LoadData(UniEquipArchiveCollectionInfoType, Int32, Int32, Boolean)`

- `Void RefreshShowTotal(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2EquipmentCollectionInfoItemViewModel : IHotfixable
{
	private UniEquipArchiveCollectionInfoType <type>k__BackingField; // 0x10
	private String <infoName>k__BackingField; // 0x18
	private Int32 <curCount>k__BackingField; // 0x20
	private Int32 <totalCount>k__BackingField; // 0x24
	private Boolean <showTotalCount>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_set_type; // 0x8
	private static DelegateBridge __Hotfix0_get_infoName; // 0x10
	private static DelegateBridge __Hotfix0_set_infoName; // 0x18
	private static DelegateBridge __Hotfix0_get_curCount; // 0x20
	private static DelegateBridge __Hotfix0_set_curCount; // 0x28
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x30
	private static DelegateBridge __Hotfix0_set_totalCount; // 0x38
	private static DelegateBridge __Hotfix0_get_showTotalCount; // 0x40
	private static DelegateBridge __Hotfix0_set_showTotalCount; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_RefreshShowTotal; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public UniEquipArchiveCollectionInfoType type { get; set; }
	public String infoName { get; set; }
	public Int32 curCount { get; set; }
	public Int32 totalCount { get; set; }
	public Boolean showTotalCount { get; set; }

	// RVA: 0x28c4d4c VA: 0x7594edcd4c
	public UniEquipArchiveCollectionInfoType get_type() { }
	// RVA: 0x28c4db4 VA: 0x7594edcdb4
	private Void set_type(UniEquipArchiveCollectionInfoType value) { }
	// RVA: 0x28c4e30 VA: 0x7594edce30
	public String get_infoName() { }
	// RVA: 0x28c4e98 VA: 0x7594edce98
	private Void set_infoName(String value) { }
	// RVA: 0x28c4f1c VA: 0x7594edcf1c
	public Int32 get_curCount() { }
	// RVA: 0x28c4f84 VA: 0x7594edcf84
	private Void set_curCount(Int32 value) { }
	// RVA: 0x28c5000 VA: 0x7594edd000
	public Int32 get_totalCount() { }
	// RVA: 0x28c5068 VA: 0x7594edd068
	private Void set_totalCount(Int32 value) { }
	// RVA: 0x28c50e4 VA: 0x7594edd0e4
	public Boolean get_showTotalCount() { }
	// RVA: 0x28c514c VA: 0x7594edd14c
	private Void set_showTotalCount(Boolean value) { }
	// RVA: 0x28c51cc VA: 0x7594edd1cc
	public Void LoadData(UniEquipArchiveCollectionInfoType infoType, Int32 curCnt, Int32 totalCnt, Boolean showTotal) { }
	// RVA: 0x28c52d0 VA: 0x7594edd2d0
	public Void RefreshShowTotal(Boolean showTotal) { }
	// RVA: 0x28c5350 VA: 0x7594edd350
	public Void .ctor() { }
}
```