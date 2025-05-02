# SandboxV2DineModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CharFood m_statusFood`

- `SandboxV2FoodVariantShowType m_statusFoodVariantShowType`

- `Int32 m_statusFoodFullDuration`

- `String <topicId>k__BackingField`

- `Int32 <charInstId>k__BackingField`

- `Boolean <initRender>k__BackingField`

- `String <charId>k__BackingField`

- `String <statusFoodName>k__BackingField`

- `Int32 <statusFoodRestDuration>k__BackingField`

- `String <statusFoodUsage>k__BackingField`

- `UIItemViewModel <statusFoodItem>k__BackingField`

- `Int32 tutorialOnlyFirstFoodIndex`

- `SandboxV2DineItemModel <selectedItem>k__BackingField`


## Properties

- `String topicId`

- `Int32 charInstId`

- `Boolean initRender`

- `String charId`

- `String statusFoodName`

- `Int32 statusFoodRestDuration`

- `String statusFoodUsage`

- `UIItemViewModel statusFoodItem`

- `SandboxV2DineItemModel selectedItem`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Int32 get_charInstId()`

- `Void set_charInstId(Int32)`

- `Boolean get_initRender()`

- `Void set_initRender(Boolean)`

- `String get_charId()`

- `Void set_charId(String)`

- `String get_statusFoodName()`

- `Void set_statusFoodName(String)`

- `Int32 get_statusFoodRestDuration()`

- `Void set_statusFoodRestDuration(Int32)`

- `String get_statusFoodUsage()`

- `Void set_statusFoodUsage(String)`

- `UIItemViewModel get_statusFoodItem()`

- `Void set_statusFoodItem(UIItemViewModel)`

- `SandboxV2DineItemModel get_selectedItem()`

- `Void set_selectedItem(SandboxV2DineItemModel)`

- `Void LoadData(String, Int32)`

- `SandboxV2DineItemModel SelectItem(Int32, out, out)`

- `Void _LoadStatusFood(SandboxV2Data, PlayerSandboxV2)`

- `Void _LoadBagItemIfNeed(SandboxV2Data, String, Food, out)`

- `Void _LoadStatusItem(SandboxV2Data, PlayerSandboxV2)`

- `Void _ScanSubMat(SandboxV2Data, String, List`1, out, out, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DineModel : IHotfixable
{
	private readonly List`1 m_items; // 0x10
	private readonly Dictionary`2 m_subVariantTempDict; // 0x18
	private CharFood m_statusFood; // 0x20
	private SandboxV2FoodVariantShowType m_statusFoodVariantShowType; // 0x28
	private Int32 m_statusFoodFullDuration; // 0x2c
	private List`1 m_statusFoodAttributes; // 0x30
	private String <topicId>k__BackingField; // 0x38
	private Int32 <charInstId>k__BackingField; // 0x40
	private Boolean <initRender>k__BackingField; // 0x44
	private String <charId>k__BackingField; // 0x48
	private String <statusFoodName>k__BackingField; // 0x50
	private Int32 <statusFoodRestDuration>k__BackingField; // 0x58
	private String <statusFoodUsage>k__BackingField; // 0x60
	private UIItemViewModel <statusFoodItem>k__BackingField; // 0x68
	public Int32 tutorialOnlyFirstFoodIndex; // 0x70
	private SandboxV2DineItemModel <selectedItem>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_charInstId; // 0x10
	private static DelegateBridge __Hotfix0_set_charInstId; // 0x18
	private static DelegateBridge __Hotfix0_get_initRender; // 0x20
	private static DelegateBridge __Hotfix0_set_initRender; // 0x28
	private static DelegateBridge __Hotfix0_get_charId; // 0x30
	private static DelegateBridge __Hotfix0_set_charId; // 0x38
	private static DelegateBridge __Hotfix0_get_statusFoodName; // 0x40
	private static DelegateBridge __Hotfix0_set_statusFoodName; // 0x48
	private static DelegateBridge __Hotfix0_get_statusFoodRestDuration; // 0x50
	private static DelegateBridge __Hotfix0_set_statusFoodRestDuration; // 0x58
	private static DelegateBridge __Hotfix0_get_statusFoodUsage; // 0x60
	private static DelegateBridge __Hotfix0_set_statusFoodUsage; // 0x68
	private static DelegateBridge __Hotfix0_get_statusFoodItem; // 0x70
	private static DelegateBridge __Hotfix0_set_statusFoodItem; // 0x78
	private static DelegateBridge __Hotfix0_get_items; // 0x80
	private static DelegateBridge __Hotfix0_get_selectedItem; // 0x88
	private static DelegateBridge __Hotfix0_set_selectedItem; // 0x90
	private static DelegateBridge __Hotfix0_LoadData; // 0x98
	private static DelegateBridge __Hotfix0_SelectItem; // 0xa0
	private static DelegateBridge __Hotfix0__LoadStatusFood; // 0xa8
	private static DelegateBridge __Hotfix0__LoadBagItemIfNeed; // 0xb0
	private static DelegateBridge __Hotfix0__LoadStatusItem; // 0xb8
	private static DelegateBridge __Hotfix0__PackAttributes; // 0xc0
	private static DelegateBridge __Hotfix0__ScanSubMat; // 0xc8
	private static DelegateBridge __Hotfix0__SubMatComparison; // 0xd0
	private static DelegateBridge __Hotfix0__ItemComparison; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0

	public String topicId { get; set; }
	public Int32 charInstId { get; set; }
	public Boolean initRender { get; set; }
	public String charId { get; set; }
	public String statusFoodName { get; set; }
	public Int32 statusFoodRestDuration { get; set; }
	public String statusFoodUsage { get; set; }
	public UIItemViewModel statusFoodItem { get; set; }
	public List`1 items { get; }
	public SandboxV2DineItemModel selectedItem { get; set; }

	// RVA: 0x2505ff8 VA: 0x7594b1dff8
	public String get_topicId() { }
	// RVA: 0x2506060 VA: 0x7594b1e060
	private Void set_topicId(String value) { }
	// RVA: 0x25060e4 VA: 0x7594b1e0e4
	public Int32 get_charInstId() { }
	// RVA: 0x250614c VA: 0x7594b1e14c
	private Void set_charInstId(Int32 value) { }
	// RVA: 0x25061c8 VA: 0x7594b1e1c8
	public Boolean get_initRender() { }
	// RVA: 0x2506230 VA: 0x7594b1e230
	private Void set_initRender(Boolean value) { }
	// RVA: 0x25062b0 VA: 0x7594b1e2b0
	public String get_charId() { }
	// RVA: 0x2506318 VA: 0x7594b1e318
	private Void set_charId(String value) { }
	// RVA: 0x250639c VA: 0x7594b1e39c
	public String get_statusFoodName() { }
	// RVA: 0x2506404 VA: 0x7594b1e404
	private Void set_statusFoodName(String value) { }
	// RVA: 0x2506488 VA: 0x7594b1e488
	public Int32 get_statusFoodRestDuration() { }
	// RVA: 0x25064f0 VA: 0x7594b1e4f0
	private Void set_statusFoodRestDuration(Int32 value) { }
	// RVA: 0x250656c VA: 0x7594b1e56c
	public String get_statusFoodUsage() { }
	// RVA: 0x25065d4 VA: 0x7594b1e5d4
	private Void set_statusFoodUsage(String value) { }
	// RVA: 0x2506658 VA: 0x7594b1e658
	public UIItemViewModel get_statusFoodItem() { }
	// RVA: 0x25066c0 VA: 0x7594b1e6c0
	private Void set_statusFoodItem(UIItemViewModel value) { }
	// RVA: 0x2506744 VA: 0x7594b1e744
	public List`1 get_items() { }
	// RVA: 0x25067ac VA: 0x7594b1e7ac
	public SandboxV2DineItemModel get_selectedItem() { }
	// RVA: 0x2506814 VA: 0x7594b1e814
	private Void set_selectedItem(SandboxV2DineItemModel value) { }
	// RVA: 0x2506898 VA: 0x7594b1e898
	public Void LoadData(String topicId, Int32 charInstId) { }
	// RVA: 0x2507688 VA: 0x7594b1f688
	public SandboxV2DineItemModel SelectItem(Int32 index, out Boolean hasStock, out Boolean hasRecipe) { }
	// RVA: 0x2506d88 VA: 0x7594b1ed88
	private Void _LoadStatusFood(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x2507004 VA: 0x7594b1f004
	private Void _LoadBagItemIfNeed(SandboxV2Data gameData, String instId, Food food, out Boolean isLastDined) { }
	// RVA: 0x2507358 VA: 0x7594b1f358
	private Void _LoadStatusItem(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x25077e4 VA: 0x7594b1f7e4
	private static List`1 _PackAttributes(List`1 main, List`1 sub) { }
	// RVA: 0x2507a24 VA: 0x7594b1fa24
	private Void _ScanSubMat(SandboxV2Data gameData, String foodId, List`1 subMatIds, out List`1 subMatItems, out SandboxV2FoodVariantType variantType, out Boolean isLastDined) { }
	// RVA: 0x2507f10 VA: 0x7594b1ff10
	private static Int32 _SubMatComparison(UIItemViewModel x, UIItemViewModel y) { }
	// RVA: 0x250801c VA: 0x7594b2001c
	private static Int32 _ItemComparison(SandboxV2DineItemModel x, SandboxV2DineItemModel y) { }
	// RVA: 0x250832c VA: 0x7594b2032c
	public Void .ctor() { }
}
```