# SandboxV2CookFreeCookModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2Data m_gameData`

- `UIItemViewModel m_waterItem`

- `String <topicId>k__BackingField`

- `String <waterId>k__BackingField`

- `Boolean <initialRender>k__BackingField`

- `Int32 <mainSlotFillCount>k__BackingField`

- `Int32 <subSlotFillCount>k__BackingField`

- `SandboxV2FoodData <food>k__BackingField`

- `Int32 <foodStock>k__BackingField`

- `SandboxV2FoodVariantType <foodVariantType>k__BackingField`

- `String <foodVariantName>k__BackingField`


## Properties

- `String topicId`

- `String waterId`

- `Boolean initialRender`

- `Int32 mainSlotFillCount`

- `Int32 subSlotFillCount`

- `SandboxV2FoodData food`

- `Int32 foodStock`

- `SandboxV2FoodVariantType foodVariantType`

- `String foodVariantName`

- `Boolean canCook`

- `Boolean canClear`

- `Boolean hasWater`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `String get_waterId()`

- `Void set_waterId(String)`

- `Boolean get_initialRender()`

- `Void set_initialRender(Boolean)`

- `Int32 get_mainSlotFillCount()`

- `Void set_mainSlotFillCount(Int32)`

- `Int32 get_subSlotFillCount()`

- `Void set_subSlotFillCount(Int32)`

- `SandboxV2FoodData get_food()`

- `Void set_food(SandboxV2FoodData)`

- `Int32 get_foodStock()`

- `Void set_foodStock(Int32)`

- `SandboxV2FoodVariantType get_foodVariantType()`

- `Void set_foodVariantType(SandboxV2FoodVariantType)`

- `String get_foodVariantName()`

- `Void set_foodVariantName(String)`

- `Boolean get_canCook()`

- `Boolean get_canClear()`

- `Boolean get_hasWater()`

- `Void LoadData(String, SandboxV2Data, PlayerSandboxV2)`

- `Boolean SelectMainMat(Int32, out, out)`

- `Boolean SelectSubMat(Int32)`

- `Boolean DeselectMainMat(Int32)`

- `Boolean DeselectSubMat(Int32)`

- `Void ClearMat()`

- `Void _LoadMainMat(SandboxV2FoodMatData, PlayerSandboxV2)`

- `Void _LoadSubMat(SandboxV2FoodMatData, PlayerSandboxV2)`

- `Void _InitDeckRelated()`

- `Void _RefreshFoodData()`

- `Void _RefreshFoodVariant()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookFreeCookModel : IHotfixable
{
	private readonly List`1 m_mainMatItems; // 0x10
	private readonly List`1 m_subMatItems; // 0x18
	private readonly List`1 m_mainSlotItems; // 0x20
	private readonly List`1 m_subSlotItems; // 0x28
	private readonly List`1 m_subMatIdList; // 0x30
	private SandboxV2Data m_gameData; // 0x38
	private UIItemViewModel m_waterItem; // 0x40
	private String <topicId>k__BackingField; // 0x48
	private String <waterId>k__BackingField; // 0x50
	private Boolean <initialRender>k__BackingField; // 0x58
	private Int32 <mainSlotFillCount>k__BackingField; // 0x5c
	private Int32 <subSlotFillCount>k__BackingField; // 0x60
	private SandboxV2FoodData <food>k__BackingField; // 0x68
	private Int32 <foodStock>k__BackingField; // 0x70
	private SandboxV2FoodVariantType <foodVariantType>k__BackingField; // 0x74
	private String <foodVariantName>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_waterId; // 0x10
	private static DelegateBridge __Hotfix0_set_waterId; // 0x18
	private static DelegateBridge __Hotfix0_get_initialRender; // 0x20
	private static DelegateBridge __Hotfix0_set_initialRender; // 0x28
	private static DelegateBridge __Hotfix0_get_mainMatItems; // 0x30
	private static DelegateBridge __Hotfix0_get_subMatItems; // 0x38
	private static DelegateBridge __Hotfix0_get_mainSlotItems; // 0x40
	private static DelegateBridge __Hotfix0_get_subSlotItems; // 0x48
	private static DelegateBridge __Hotfix0_get_mainSlotFillCount; // 0x50
	private static DelegateBridge __Hotfix0_set_mainSlotFillCount; // 0x58
	private static DelegateBridge __Hotfix0_get_subSlotFillCount; // 0x60
	private static DelegateBridge __Hotfix0_set_subSlotFillCount; // 0x68
	private static DelegateBridge __Hotfix0_get_food; // 0x70
	private static DelegateBridge __Hotfix0_set_food; // 0x78
	private static DelegateBridge __Hotfix0_get_foodStock; // 0x80
	private static DelegateBridge __Hotfix0_set_foodStock; // 0x88
	private static DelegateBridge __Hotfix0_get_foodVariantType; // 0x90
	private static DelegateBridge __Hotfix0_set_foodVariantType; // 0x98
	private static DelegateBridge __Hotfix0_get_foodVariantName; // 0xa0
	private static DelegateBridge __Hotfix0_set_foodVariantName; // 0xa8
	private static DelegateBridge __Hotfix0_get_canCook; // 0xb0
	private static DelegateBridge __Hotfix0_get_canClear; // 0xb8
	private static DelegateBridge __Hotfix0_get_hasWater; // 0xc0
	private static DelegateBridge __Hotfix0_LoadData; // 0xc8
	private static DelegateBridge __Hotfix0_SelectMainMat; // 0xd0
	private static DelegateBridge __Hotfix0_SelectSubMat; // 0xd8
	private static DelegateBridge __Hotfix0_DeselectMainMat; // 0xe0
	private static DelegateBridge __Hotfix0_DeselectSubMat; // 0xe8
	private static DelegateBridge __Hotfix0_ClearMat; // 0xf0
	private static DelegateBridge __Hotfix0__LoadMainMat; // 0xf8
	private static DelegateBridge __Hotfix0__LoadSubMat; // 0x100
	private static DelegateBridge __Hotfix0__InitDeckRelated; // 0x108
	private static DelegateBridge __Hotfix0__RefreshFoodData; // 0x110
	private static DelegateBridge __Hotfix0__RefreshFoodVariant; // 0x118
	private static DelegateBridge __Hotfix0__ItemComparison; // 0x120
	private static DelegateBridge _c__Hotfix0_ctor; // 0x128

	public String topicId { get; set; }
	public String waterId { get; set; }
	public Boolean initialRender { get; set; }
	public List`1 mainMatItems { get; }
	public List`1 subMatItems { get; }
	public List`1 mainSlotItems { get; }
	public List`1 subSlotItems { get; }
	public Int32 mainSlotFillCount { get; set; }
	public Int32 subSlotFillCount { get; set; }
	public SandboxV2FoodData food { get; set; }
	public Int32 foodStock { get; set; }
	public SandboxV2FoodVariantType foodVariantType { get; set; }
	public String foodVariantName { get; set; }
	public Boolean canCook { get; }
	public Boolean canClear { get; }
	public Boolean hasWater { get; }

	// RVA: 0x24be690 VA: 0x7594ad6690
	public String get_topicId() { }
	// RVA: 0x24be6f8 VA: 0x7594ad66f8
	private Void set_topicId(String value) { }
	// RVA: 0x24be77c VA: 0x7594ad677c
	public String get_waterId() { }
	// RVA: 0x24be7e4 VA: 0x7594ad67e4
	private Void set_waterId(String value) { }
	// RVA: 0x24be868 VA: 0x7594ad6868
	public Boolean get_initialRender() { }
	// RVA: 0x24be8d0 VA: 0x7594ad68d0
	public Void set_initialRender(Boolean value) { }
	// RVA: 0x24be950 VA: 0x7594ad6950
	public List`1 get_mainMatItems() { }
	// RVA: 0x24be9b8 VA: 0x7594ad69b8
	public List`1 get_subMatItems() { }
	// RVA: 0x24bea20 VA: 0x7594ad6a20
	public List`1 get_mainSlotItems() { }
	// RVA: 0x24bea88 VA: 0x7594ad6a88
	public List`1 get_subSlotItems() { }
	// RVA: 0x24beaf0 VA: 0x7594ad6af0
	public Int32 get_mainSlotFillCount() { }
	// RVA: 0x24beb58 VA: 0x7594ad6b58
	private Void set_mainSlotFillCount(Int32 value) { }
	// RVA: 0x24bebd4 VA: 0x7594ad6bd4
	public Int32 get_subSlotFillCount() { }
	// RVA: 0x24bec3c VA: 0x7594ad6c3c
	private Void set_subSlotFillCount(Int32 value) { }
	// RVA: 0x24becb8 VA: 0x7594ad6cb8
	public SandboxV2FoodData get_food() { }
	// RVA: 0x24bed20 VA: 0x7594ad6d20
	private Void set_food(SandboxV2FoodData value) { }
	// RVA: 0x24beda4 VA: 0x7594ad6da4
	public Int32 get_foodStock() { }
	// RVA: 0x24bee0c VA: 0x7594ad6e0c
	public Void set_foodStock(Int32 value) { }
	// RVA: 0x24bee88 VA: 0x7594ad6e88
	public SandboxV2FoodVariantType get_foodVariantType() { }
	// RVA: 0x24beef0 VA: 0x7594ad6ef0
	private Void set_foodVariantType(SandboxV2FoodVariantType value) { }
	// RVA: 0x24bef6c VA: 0x7594ad6f6c
	public String get_foodVariantName() { }
	// RVA: 0x24befd4 VA: 0x7594ad6fd4
	private Void set_foodVariantName(String value) { }
	// RVA: 0x24bf058 VA: 0x7594ad7058
	public Boolean get_canCook() { }
	// RVA: 0x24bf0ec VA: 0x7594ad70ec
	public Boolean get_canClear() { }
	// RVA: 0x24bf178 VA: 0x7594ad7178
	public Boolean get_hasWater() { }
	// RVA: 0x24bf1f8 VA: 0x7594ad71f8
	public Void LoadData(String topicId, SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24bfc18 VA: 0x7594ad7c18
	public Boolean SelectMainMat(Int32 index, out Boolean empty, out String id) { }
	// RVA: 0x24c0350 VA: 0x7594ad8350
	public Boolean SelectSubMat(Int32 index) { }
	// RVA: 0x24c06d8 VA: 0x7594ad86d8
	public Boolean DeselectMainMat(Int32 index) { }
	// RVA: 0x24c0894 VA: 0x7594ad8894
	public Boolean DeselectSubMat(Int32 index) { }
	// RVA: 0x24c0a5c VA: 0x7594ad8a5c
	public Void ClearMat() { }
	// RVA: 0x24bf5b4 VA: 0x7594ad75b4
	private Void _LoadMainMat(SandboxV2FoodMatData matData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24bf748 VA: 0x7594ad7748
	private Void _LoadSubMat(SandboxV2FoodMatData matData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24bf8e4 VA: 0x7594ad78e4
	private Void _InitDeckRelated() { }
	// RVA: 0x24bfe84 VA: 0x7594ad7e84
	private Void _RefreshFoodData() { }
	// RVA: 0x24c05c0 VA: 0x7594ad85c0
	private Void _RefreshFoodVariant() { }
	// RVA: 0x24c0cbc VA: 0x7594ad8cbc
	private static Int32 _ItemComparison(UIItemViewModel x, UIItemViewModel y) { }
	// RVA: 0x24c0de8 VA: 0x7594ad8de8
	public Void .ctor() { }
}
```