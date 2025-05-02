# Act24sideMeldingChoiceItemViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String <actId>k__BackingField`

- `String <itemId>k__BackingField`

- `Act24sideMeldingItemViewModel <itemViewModel>k__BackingField`

- `Act24sideMeldingSmallItemViewModel <smallItemViewModel>k__BackingField`

- `Int32 <hasCount>k__BackingField`

- `Int32 <useCount>k__BackingField`

- `Boolean <showLine>k__BackingField`

- `Int32 <price>k__BackingField`


## Properties

- `String actId`

- `String itemId`

- `Act24sideMeldingItemViewModel itemViewModel`

- `Act24sideMeldingSmallItemViewModel smallItemViewModel`

- `Int32 hasCount`

- `Int32 useCount`

- `Boolean showLine`

- `Int32 price`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_itemId()`

- `Void set_itemId(String)`

- `Act24sideMeldingItemViewModel get_itemViewModel()`

- `Void set_itemViewModel(Act24sideMeldingItemViewModel)`

- `Act24sideMeldingSmallItemViewModel get_smallItemViewModel()`

- `Void set_smallItemViewModel(Act24sideMeldingSmallItemViewModel)`

- `Int32 get_hasCount()`

- `Void set_hasCount(Int32)`

- `Int32 get_useCount()`

- `Void set_useCount(Int32)`

- `Boolean get_showLine()`

- `Void set_showLine(Boolean)`

- `Int32 get_price()`

- `Void set_price(Int32)`

- `Void LoadData(String, MeldingItemData)`

- `Void InitShowLine(Boolean)`

- `Void RefreshHasCount(Int32)`

- `Void RefreshUseCount(Int32)`

- `Void InputAllHasCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingChoiceItemViewModel : IHotfixable
{
	private String <actId>k__BackingField; // 0x10
	private String <itemId>k__BackingField; // 0x18
	private Act24sideMeldingItemViewModel <itemViewModel>k__BackingField; // 0x20
	private Act24sideMeldingSmallItemViewModel <smallItemViewModel>k__BackingField; // 0x28
	private Int32 <hasCount>k__BackingField; // 0x30
	private Int32 <useCount>k__BackingField; // 0x34
	private Boolean <showLine>k__BackingField; // 0x38
	private Int32 <price>k__BackingField; // 0x3c
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_itemId; // 0x10
	private static DelegateBridge __Hotfix0_set_itemId; // 0x18
	private static DelegateBridge __Hotfix0_get_itemViewModel; // 0x20
	private static DelegateBridge __Hotfix0_set_itemViewModel; // 0x28
	private static DelegateBridge __Hotfix0_get_smallItemViewModel; // 0x30
	private static DelegateBridge __Hotfix0_set_smallItemViewModel; // 0x38
	private static DelegateBridge __Hotfix0_get_hasCount; // 0x40
	private static DelegateBridge __Hotfix0_set_hasCount; // 0x48
	private static DelegateBridge __Hotfix0_get_useCount; // 0x50
	private static DelegateBridge __Hotfix0_set_useCount; // 0x58
	private static DelegateBridge __Hotfix0_get_showLine; // 0x60
	private static DelegateBridge __Hotfix0_set_showLine; // 0x68
	private static DelegateBridge __Hotfix0_get_price; // 0x70
	private static DelegateBridge __Hotfix0_set_price; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x80
	private static DelegateBridge __Hotfix0_InitShowLine; // 0x88
	private static DelegateBridge __Hotfix0_RefreshHasCount; // 0x90
	private static DelegateBridge __Hotfix0_RefreshUseCount; // 0x98
	private static DelegateBridge __Hotfix0_InputAllHasCount; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public String actId { get; set; }
	public String itemId { get; set; }
	public Act24sideMeldingItemViewModel itemViewModel { get; set; }
	public Act24sideMeldingSmallItemViewModel smallItemViewModel { get; set; }
	public Int32 hasCount { get; set; }
	public Int32 useCount { get; set; }
	public Boolean showLine { get; set; }
	public Int32 price { get; set; }

	// RVA: 0x32a0c44 VA: 0x75958b8c44
	public String get_actId() { }
	// RVA: 0x32af778 VA: 0x75958c7778
	private Void set_actId(String value) { }
	// RVA: 0x32ac6f8 VA: 0x75958c46f8
	public String get_itemId() { }
	// RVA: 0x32af7fc VA: 0x75958c77fc
	private Void set_itemId(String value) { }
	// RVA: 0x32a097c VA: 0x75958b897c
	public Act24sideMeldingItemViewModel get_itemViewModel() { }
	// RVA: 0x32af880 VA: 0x75958c7880
	private Void set_itemViewModel(Act24sideMeldingItemViewModel value) { }
	// RVA: 0x32aa344 VA: 0x75958c2344
	public Act24sideMeldingSmallItemViewModel get_smallItemViewModel() { }
	// RVA: 0x32af904 VA: 0x75958c7904
	private Void set_smallItemViewModel(Act24sideMeldingSmallItemViewModel value) { }
	// RVA: 0x32a0cac VA: 0x75958b8cac
	public Int32 get_hasCount() { }
	// RVA: 0x32af988 VA: 0x75958c7988
	private Void set_hasCount(Int32 value) { }
	// RVA: 0x32a0d14 VA: 0x75958b8d14
	public Int32 get_useCount() { }
	// RVA: 0x32afa04 VA: 0x75958c7a04
	private Void set_useCount(Int32 value) { }
	// RVA: 0x32a0d7c VA: 0x75958b8d7c
	public Boolean get_showLine() { }
	// RVA: 0x32afa80 VA: 0x75958c7a80
	private Void set_showLine(Boolean value) { }
	// RVA: 0x32ad50c VA: 0x75958c550c
	public Int32 get_price() { }
	// RVA: 0x32afb00 VA: 0x75958c7b00
	private Void set_price(Int32 value) { }
	// RVA: 0x32abed8 VA: 0x75958c3ed8
	public Void LoadData(String activityId, MeldingItemData itemData) { }
	// RVA: 0x32ac05c VA: 0x75958c405c
	public Void InitShowLine(Boolean isLastOne) { }
	// RVA: 0x32ae7e8 VA: 0x75958c67e8
	public Void RefreshHasCount(Int32 count) { }
	// RVA: 0x32ad978 VA: 0x75958c5978
	public Void RefreshUseCount(Int32 count) { }
	// RVA: 0x32adb7c VA: 0x75958c5b7c
	public Void InputAllHasCount() { }
	// RVA: 0x32abe68 VA: 0x75958c3e68
	public Void .ctor() { }
}
```