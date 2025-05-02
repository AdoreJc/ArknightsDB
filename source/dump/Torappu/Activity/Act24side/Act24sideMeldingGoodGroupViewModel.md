# Act24sideMeldingGoodGroupViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String <boxId>k__BackingField`

- `Boolean <containUnlimitGoods>k__BackingField`

- `MeldingGachaBoxData <boxData>k__BackingField`

- `Single m_inputPerPriceBestTweenDur`


## Properties

- `String boxId`

- `Boolean containUnlimitGoods`

- `MeldingGachaBoxData boxData`


## Methods

- `String get_boxId()`

- `Void set_boxId(String)`

- `Boolean get_containUnlimitGoods()`

- `Void set_containUnlimitGoods(Boolean)`

- `MeldingGachaBoxData get_boxData()`

- `Void set_boxData(MeldingGachaBoxData)`

- `Void LoadData(MeldingGachaBoxData, List`1)`

- `Void RefreshData(Dictionary`2)`

- `Single GetInputPerPriceDur(Int32)`

- `Boolean IsGachaBoxAllTakeOut()`

- `Boolean IsGachaDisplayTypeGridAllTakeOut(MeldingGoodDisplayType)`

- `Single GetGoodLayoutScrollTarget(Int32, Single, Int32)`

- `Int32 GetGachaBoxRemainCount()`

- `Int32 GetMaxCanDrawPriceCount(Boolean)`

- `Boolean _IsInputsOverMaxTweenDur(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingGoodGroupViewModel : IHotfixable
{
	private String <boxId>k__BackingField; // 0x10
	private Boolean <containUnlimitGoods>k__BackingField; // 0x18
	private MeldingGachaBoxData <boxData>k__BackingField; // 0x20
	public ListDict`2 goodDisplayViewModelList; // 0x28
	public List`1 goodItemViewModelList; // 0x30
	private const Int32 PER_ROW_GOOD_MAX_COUNT; // 0x0
	private const Int32 PER_DISPLAY_TITLE_HEIGHT; // 0x0
	private const Int32 PER_DISPLAY_ITEM_HEIGHT; // 0x0
	private const Int32 PER_DISPLAY_ITEM_SPACE; // 0x0
	private Single m_inputPerPriceBestTweenDur; // 0x38
	private const Single INPUT_MAX_TWEEN_DUR; // 0x0
	private const Single INPUT_SINGLE_SEGMENT_TWEEN_DUR; // 0x0
	private const Int32 TINY_INPUT_LIMIT_UP; // 0x0
	private const Single SMALL_INPUT_SINGLE_PRICE_TWEEN_DUR; // 0x0
	private const Int32 SMALL_INPUT_LIMIT_UP; // 0x0
	private const Single TINY_INPUT_SINGLE_PRICE_TWEEN_DUR; // 0x0
	private static DelegateBridge __Hotfix0_get_boxId; // 0x0
	private static DelegateBridge __Hotfix0_set_boxId; // 0x8
	private static DelegateBridge __Hotfix0_get_containUnlimitGoods; // 0x10
	private static DelegateBridge __Hotfix0_set_containUnlimitGoods; // 0x18
	private static DelegateBridge __Hotfix0_get_boxData; // 0x20
	private static DelegateBridge __Hotfix0_set_boxData; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_RefreshData; // 0x38
	private static DelegateBridge __Hotfix0_GetInputPerPriceDur; // 0x40
	private static DelegateBridge __Hotfix0_IsGachaBoxAllTakeOut; // 0x48
	private static DelegateBridge __Hotfix0_IsGachaDisplayTypeGridAllTakeOut; // 0x50
	private static DelegateBridge __Hotfix0_GetGoodLayoutScrollTarget; // 0x58
	private static DelegateBridge __Hotfix0_GetGachaBoxRemainCount; // 0x60
	private static DelegateBridge __Hotfix0_GetMaxCanDrawPriceCount; // 0x68
	private static DelegateBridge __Hotfix0__IsInputsOverMaxTweenDur; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public String boxId { get; set; }
	public Boolean containUnlimitGoods { get; set; }
	public MeldingGachaBoxData boxData { get; set; }

	// RVA: 0x32b1864 VA: 0x75958c9864
	public String get_boxId() { }
	// RVA: 0x32b18cc VA: 0x75958c98cc
	private Void set_boxId(String value) { }
	// RVA: 0x32b1950 VA: 0x75958c9950
	public Boolean get_containUnlimitGoods() { }
	// RVA: 0x32b19b8 VA: 0x75958c99b8
	private Void set_containUnlimitGoods(Boolean value) { }
	// RVA: 0x32b1a38 VA: 0x75958c9a38
	public MeldingGachaBoxData get_boxData() { }
	// RVA: 0x32b1aa0 VA: 0x75958c9aa0
	private Void set_boxData(MeldingGachaBoxData value) { }
	// RVA: 0x32b1b24 VA: 0x75958c9b24
	public Void LoadData(MeldingGachaBoxData gachaBoxData, List`1 goodDataList) { }
	// RVA: 0x32b2114 VA: 0x75958ca114
	public Void RefreshData(Dictionary`2 dicGachaGoodInfo) { }
	// RVA: 0x32b2278 VA: 0x75958ca278
	public Single GetInputPerPriceDur(Int32 totalChangePrice) { }
	// RVA: 0x32b2440 VA: 0x75958ca440
	public Boolean IsGachaBoxAllTakeOut() { }
	// RVA: 0x32b2548 VA: 0x75958ca548
	public Boolean IsGachaDisplayTypeGridAllTakeOut(MeldingGoodDisplayType displayType) { }
	// RVA: 0x32b2640 VA: 0x75958ca640
	public Single GetGoodLayoutScrollTarget(Int32 layoutTopSpace, Single layoutSpace, Int32 layoutDownSpace) { }
	// RVA: 0x32b29f8 VA: 0x75958ca9f8
	public Int32 GetGachaBoxRemainCount() { }
	// RVA: 0x32b2b28 VA: 0x75958cab28
	public Int32 GetMaxCanDrawPriceCount(Boolean canOver) { }
	// RVA: 0x32b2374 VA: 0x75958ca374
	private Boolean _IsInputsOverMaxTweenDur(Int32 totalInputPrice) { }
	// RVA: 0x32b2be4 VA: 0x75958cabe4
	public Void .ctor() { }
}
```