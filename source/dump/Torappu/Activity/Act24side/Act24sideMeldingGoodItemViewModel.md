# Act24sideMeldingGoodItemViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String <goodId>k__BackingField`

- `Boolean <isCountUnlimit>k__BackingField`

- `String <remainBgCol>k__BackingField`

- `MeldingGachaBoxGoodData <data>k__BackingField`

- `UIItemViewModel <itemModel>k__BackingField`

- `Int32 <remainCount>k__BackingField`


## Properties

- `String goodId`

- `Boolean isCountUnlimit`

- `String remainBgCol`

- `MeldingGachaBoxGoodData data`

- `UIItemViewModel itemModel`

- `Int32 remainCount`


## Methods

- `String get_goodId()`

- `Void set_goodId(String)`

- `Boolean get_isCountUnlimit()`

- `Void set_isCountUnlimit(Boolean)`

- `String get_remainBgCol()`

- `Void set_remainBgCol(String)`

- `MeldingGachaBoxGoodData get_data()`

- `Void set_data(MeldingGachaBoxGoodData)`

- `UIItemViewModel get_itemModel()`

- `Void set_itemModel(UIItemViewModel)`

- `Int32 get_remainCount()`

- `Void set_remainCount(Int32)`

- `Void LoadData(MeldingGachaBoxGoodData, String)`

- `Void RefreshData(Int32)`

- `Boolean IsGoodRemain()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingGoodItemViewModel : IHotfixable
{
	private String <goodId>k__BackingField; // 0x10
	private Boolean <isCountUnlimit>k__BackingField; // 0x18
	private String <remainBgCol>k__BackingField; // 0x20
	private MeldingGachaBoxGoodData <data>k__BackingField; // 0x28
	private UIItemViewModel <itemModel>k__BackingField; // 0x30
	private Int32 <remainCount>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_goodId; // 0x0
	private static DelegateBridge __Hotfix0_set_goodId; // 0x8
	private static DelegateBridge __Hotfix0_get_isCountUnlimit; // 0x10
	private static DelegateBridge __Hotfix0_set_isCountUnlimit; // 0x18
	private static DelegateBridge __Hotfix0_get_remainBgCol; // 0x20
	private static DelegateBridge __Hotfix0_set_remainBgCol; // 0x28
	private static DelegateBridge __Hotfix0_get_data; // 0x30
	private static DelegateBridge __Hotfix0_set_data; // 0x38
	private static DelegateBridge __Hotfix0_get_itemModel; // 0x40
	private static DelegateBridge __Hotfix0_set_itemModel; // 0x48
	private static DelegateBridge __Hotfix0_get_remainCount; // 0x50
	private static DelegateBridge __Hotfix0_set_remainCount; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0_RefreshData; // 0x68
	private static DelegateBridge __Hotfix0_IsGoodRemain; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public String goodId { get; set; }
	public Boolean isCountUnlimit { get; set; }
	public String remainBgCol { get; set; }
	public MeldingGachaBoxGoodData data { get; set; }
	public UIItemViewModel itemModel { get; set; }
	public Int32 remainCount { get; set; }

	// RVA: 0x32b0b7c VA: 0x75958c8b7c
	public String get_goodId() { }
	// RVA: 0x32b0be4 VA: 0x75958c8be4
	private Void set_goodId(String value) { }
	// RVA: 0x32b0c68 VA: 0x75958c8c68
	public Boolean get_isCountUnlimit() { }
	// RVA: 0x32b0cd0 VA: 0x75958c8cd0
	private Void set_isCountUnlimit(Boolean value) { }
	// RVA: 0x32b0d50 VA: 0x75958c8d50
	public String get_remainBgCol() { }
	// RVA: 0x32b0db8 VA: 0x75958c8db8
	private Void set_remainBgCol(String value) { }
	// RVA: 0x32b0e3c VA: 0x75958c8e3c
	public MeldingGachaBoxGoodData get_data() { }
	// RVA: 0x32b0ea4 VA: 0x75958c8ea4
	private Void set_data(MeldingGachaBoxGoodData value) { }
	// RVA: 0x32b0f28 VA: 0x75958c8f28
	public UIItemViewModel get_itemModel() { }
	// RVA: 0x32b0f90 VA: 0x75958c8f90
	private Void set_itemModel(UIItemViewModel value) { }
	// RVA: 0x32b1014 VA: 0x75958c9014
	public Int32 get_remainCount() { }
	// RVA: 0x32b107c VA: 0x75958c907c
	private Void set_remainCount(Int32 value) { }
	// RVA: 0x32b10f8 VA: 0x75958c90f8
	public Void LoadData(MeldingGachaBoxGoodData goodData, String remainItemBgColor) { }
	// RVA: 0x32b126c VA: 0x75958c926c
	public Void RefreshData(Int32 takeOutCount) { }
	// RVA: 0x32b1340 VA: 0x75958c9340
	public Boolean IsGoodRemain() { }
	// RVA: 0x32b13c8 VA: 0x75958c93c8
	public Void .ctor() { }
}
```