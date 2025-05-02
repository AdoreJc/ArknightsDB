# UniEquipArchiveEntryCollectionInfoItemViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `UniEquipArchiveCollectionInfoType <type>k__BackingField`

- `String <infoName>k__BackingField`

- `Boolean <showTotalCount>k__BackingField`

- `Int32 <curCount>k__BackingField`

- `Int32 <totalCount>k__BackingField`

- `Boolean <showSplitLine>k__BackingField`


## Properties

- `UniEquipArchiveCollectionInfoType type`

- `String infoName`

- `Boolean showTotalCount`

- `Int32 curCount`

- `Int32 totalCount`

- `Boolean showSplitLine`


## Methods

- `UniEquipArchiveCollectionInfoType get_type()`

- `Void set_type(UniEquipArchiveCollectionInfoType)`

- `String get_infoName()`

- `Void set_infoName(String)`

- `Boolean get_showTotalCount()`

- `Void set_showTotalCount(Boolean)`

- `Int32 get_curCount()`

- `Void set_curCount(Int32)`

- `Int32 get_totalCount()`

- `Void set_totalCount(Int32)`

- `Boolean get_showSplitLine()`

- `Void set_showSplitLine(Boolean)`

- `Void LoadData(UniEquipArchiveCollectionInfoType, Boolean, Boolean)`

- `Void RefreshCountData(UniEquipArchiveEntryCollectionInfoData)`

- `Void RefreshShowTotal(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveEntryCollectionInfoItemViewModel : IHotfixable
{
	private UniEquipArchiveCollectionInfoType <type>k__BackingField; // 0x10
	private String <infoName>k__BackingField; // 0x18
	private Boolean <showTotalCount>k__BackingField; // 0x20
	private Int32 <curCount>k__BackingField; // 0x24
	private Int32 <totalCount>k__BackingField; // 0x28
	private Boolean <showSplitLine>k__BackingField; // 0x2c
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_set_type; // 0x8
	private static DelegateBridge __Hotfix0_get_infoName; // 0x10
	private static DelegateBridge __Hotfix0_set_infoName; // 0x18
	private static DelegateBridge __Hotfix0_get_showTotalCount; // 0x20
	private static DelegateBridge __Hotfix0_set_showTotalCount; // 0x28
	private static DelegateBridge __Hotfix0_get_curCount; // 0x30
	private static DelegateBridge __Hotfix0_set_curCount; // 0x38
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x40
	private static DelegateBridge __Hotfix0_set_totalCount; // 0x48
	private static DelegateBridge __Hotfix0_get_showSplitLine; // 0x50
	private static DelegateBridge __Hotfix0_set_showSplitLine; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0_RefreshCountData; // 0x68
	private static DelegateBridge __Hotfix0_RefreshShowTotal; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public UniEquipArchiveCollectionInfoType type { get; set; }
	public String infoName { get; set; }
	public Boolean showTotalCount { get; set; }
	public Int32 curCount { get; set; }
	public Int32 totalCount { get; set; }
	public Boolean showSplitLine { get; set; }

	// RVA: 0x22edc74 VA: 0x7594905c74
	public UniEquipArchiveCollectionInfoType get_type() { }
	// RVA: 0x22f568c VA: 0x759490d68c
	private Void set_type(UniEquipArchiveCollectionInfoType value) { }
	// RVA: 0x22edcdc VA: 0x7594905cdc
	public String get_infoName() { }
	// RVA: 0x22f5708 VA: 0x759490d708
	private Void set_infoName(String value) { }
	// RVA: 0x22ede7c VA: 0x7594905e7c
	public Boolean get_showTotalCount() { }
	// RVA: 0x22f578c VA: 0x759490d78c
	private Void set_showTotalCount(Boolean value) { }
	// RVA: 0x22eddac VA: 0x7594905dac
	public Int32 get_curCount() { }
	// RVA: 0x22f580c VA: 0x759490d80c
	private Void set_curCount(Int32 value) { }
	// RVA: 0x22ede14 VA: 0x7594905e14
	public Int32 get_totalCount() { }
	// RVA: 0x22f5888 VA: 0x759490d888
	private Void set_totalCount(Int32 value) { }
	// RVA: 0x22edd44 VA: 0x7594905d44
	public Boolean get_showSplitLine() { }
	// RVA: 0x22f5904 VA: 0x759490d904
	private Void set_showSplitLine(Boolean value) { }
	// RVA: 0x22f49f8 VA: 0x759490c9f8
	public Void LoadData(UniEquipArchiveCollectionInfoType infoType, Boolean isLastOne, Boolean showTotal) { }
	// RVA: 0x22f4bfc VA: 0x759490cbfc
	public Void RefreshCountData(UniEquipArchiveEntryCollectionInfoData infoData) { }
	// RVA: 0x22f47e4 VA: 0x759490c7e4
	public Void RefreshShowTotal(Boolean showTotal) { }
	// RVA: 0x22f4988 VA: 0x759490c988
	public Void .ctor() { }
}
```