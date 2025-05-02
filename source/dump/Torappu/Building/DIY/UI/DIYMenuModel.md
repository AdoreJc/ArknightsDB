# DIYMenuModel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Int32 m_singleFurnitureCount`

- `Int32 m_themeCount`

- `Int32 m_themeTotalCount`

- `Int32 m_presetCount`

- `Int32 m_collectionCount`

- `Int32 <singleFurnitureNewCount>k__BackingField`

- `Int32 <themeNewCount>k__BackingField`

- `Int32 <recentThemeCount>k__BackingField`

- `Int32 <recentSingleCount>k__BackingField`

- `Int32 <recentThemeNewCount>k__BackingField`

- `Int32 <recentSingleNewCount>k__BackingField`


## Properties

- `Int32 singleFurnitureNewCount`

- `Int32 themeNewCount`

- `Int32 recentThemeCount`

- `Int32 recentSingleCount`

- `Int32 recentThemeNewCount`

- `Int32 recentSingleNewCount`

- `Int32 singleFurnitureCount`

- `Int32 themeCount`

- `Int32 themeTotalCount`

- `Int32 presetCount`

- `Int32 collectionCount`


## Methods

- `Int32 get_singleFurnitureNewCount()`

- `Void set_singleFurnitureNewCount(Int32)`

- `Int32 get_themeNewCount()`

- `Void set_themeNewCount(Int32)`

- `Int32 get_recentThemeCount()`

- `Void set_recentThemeCount(Int32)`

- `Int32 get_recentSingleCount()`

- `Void set_recentSingleCount(Int32)`

- `Int32 get_recentThemeNewCount()`

- `Void set_recentThemeNewCount(Int32)`

- `Int32 get_recentSingleNewCount()`

- `Void set_recentSingleNewCount(Int32)`

- `Int32 get_singleFurnitureCount()`

- `Void set_singleFurnitureCount(Int32)`

- `Int32 get_themeCount()`

- `Void set_themeCount(Int32)`

- `Int32 get_themeTotalCount()`

- `Void set_themeTotalCount(Int32)`

- `Int32 get_presetCount()`

- `Void set_presetCount(Int32)`

- `Int32 get_collectionCount()`

- `Void set_collectionCount(Int32)`

- `Void set_recentThemeDatas(List`1)`

- `Void set_recentSingleDatas(List`1)`

- `Int32 GetRecentThemeCount()`

- `Int32 GetRecentSingleCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYMenuModel : IHotfixable
{
	private Int32 m_singleFurnitureCount; // 0x10
	private Int32 m_themeCount; // 0x14
	private Int32 m_themeTotalCount; // 0x18
	private Int32 m_presetCount; // 0x1c
	private Int32 m_collectionCount; // 0x20
	private List`1 m_recentThemeDatas; // 0x28
	private List`1 m_recentSingleDatas; // 0x30
	private Int32 <singleFurnitureNewCount>k__BackingField; // 0x38
	private Int32 <themeNewCount>k__BackingField; // 0x3c
	private Int32 <recentThemeCount>k__BackingField; // 0x40
	private Int32 <recentSingleCount>k__BackingField; // 0x44
	private Int32 <recentThemeNewCount>k__BackingField; // 0x48
	private Int32 <recentSingleNewCount>k__BackingField; // 0x4c
	private static DelegateBridge __Hotfix0_get_singleFurnitureNewCount; // 0x0
	private static DelegateBridge __Hotfix0_set_singleFurnitureNewCount; // 0x8
	private static DelegateBridge __Hotfix0_get_themeNewCount; // 0x10
	private static DelegateBridge __Hotfix0_set_themeNewCount; // 0x18
	private static DelegateBridge __Hotfix0_get_recentThemeCount; // 0x20
	private static DelegateBridge __Hotfix0_set_recentThemeCount; // 0x28
	private static DelegateBridge __Hotfix0_get_recentSingleCount; // 0x30
	private static DelegateBridge __Hotfix0_set_recentSingleCount; // 0x38
	private static DelegateBridge __Hotfix0_get_recentThemeNewCount; // 0x40
	private static DelegateBridge __Hotfix0_set_recentThemeNewCount; // 0x48
	private static DelegateBridge __Hotfix0_get_recentSingleNewCount; // 0x50
	private static DelegateBridge __Hotfix0_set_recentSingleNewCount; // 0x58
	private static DelegateBridge __Hotfix0_get_singleFurnitureCount; // 0x60
	private static DelegateBridge __Hotfix0_set_singleFurnitureCount; // 0x68
	private static DelegateBridge __Hotfix0_get_themeCount; // 0x70
	private static DelegateBridge __Hotfix0_set_themeCount; // 0x78
	private static DelegateBridge __Hotfix0_get_themeTotalCount; // 0x80
	private static DelegateBridge __Hotfix0_set_themeTotalCount; // 0x88
	private static DelegateBridge __Hotfix0_get_presetCount; // 0x90
	private static DelegateBridge __Hotfix0_set_presetCount; // 0x98
	private static DelegateBridge __Hotfix0_get_collectionCount; // 0xa0
	private static DelegateBridge __Hotfix0_set_collectionCount; // 0xa8
	private static DelegateBridge __Hotfix0_get_recentThemeDatas; // 0xb0
	private static DelegateBridge __Hotfix0_set_recentThemeDatas; // 0xb8
	private static DelegateBridge __Hotfix0_get_recentSingleDatas; // 0xc0
	private static DelegateBridge __Hotfix0_set_recentSingleDatas; // 0xc8
	private static DelegateBridge __Hotfix0_GetRecentThemeCount; // 0xd0
	private static DelegateBridge __Hotfix0_GetRecentSingleCount; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0

	public Int32 singleFurnitureNewCount { get; set; }
	public Int32 themeNewCount { get; set; }
	public Int32 recentThemeCount { get; set; }
	public Int32 recentSingleCount { get; set; }
	public Int32 recentThemeNewCount { get; set; }
	public Int32 recentSingleNewCount { get; set; }
	public Int32 singleFurnitureCount { get; set; }
	public Int32 themeCount { get; set; }
	public Int32 themeTotalCount { get; set; }
	public Int32 presetCount { get; set; }
	public Int32 collectionCount { get; set; }
	public List`1 recentThemeDatas { get; set; }
	public List`1 recentSingleDatas { get; set; }

	// RVA: 0x383e480 VA: 0x7595e56480
	public Int32 get_singleFurnitureNewCount() { }
	// RVA: 0x3833ab4 VA: 0x7595e4bab4
	public Void set_singleFurnitureNewCount(Int32 value) { }
	// RVA: 0x383e4e8 VA: 0x7595e564e8
	public Int32 get_themeNewCount() { }
	// RVA: 0x3833c28 VA: 0x7595e4bc28
	public Void set_themeNewCount(Int32 value) { }
	// RVA: 0x383e550 VA: 0x7595e56550
	public Int32 get_recentThemeCount() { }
	// RVA: 0x3833d20 VA: 0x7595e4bd20
	public Void set_recentThemeCount(Int32 value) { }
	// RVA: 0x383e5b8 VA: 0x7595e565b8
	public Int32 get_recentSingleCount() { }
	// RVA: 0x3833e18 VA: 0x7595e4be18
	public Void set_recentSingleCount(Int32 value) { }
	// RVA: 0x383e620 VA: 0x7595e56620
	public Int32 get_recentThemeNewCount() { }
	// RVA: 0x3833d9c VA: 0x7595e4bd9c
	public Void set_recentThemeNewCount(Int32 value) { }
	// RVA: 0x383e688 VA: 0x7595e56688
	public Int32 get_recentSingleNewCount() { }
	// RVA: 0x3833e94 VA: 0x7595e4be94
	public Void set_recentSingleNewCount(Int32 value) { }
	// RVA: 0x383e6f0 VA: 0x7595e566f0
	public Int32 get_singleFurnitureCount() { }
	// RVA: 0x3833a38 VA: 0x7595e4ba38
	public Void set_singleFurnitureCount(Int32 value) { }
	// RVA: 0x383e758 VA: 0x7595e56758
	public Int32 get_themeCount() { }
	// RVA: 0x3833b30 VA: 0x7595e4bb30
	public Void set_themeCount(Int32 value) { }
	// RVA: 0x383e7c0 VA: 0x7595e567c0
	public Int32 get_themeTotalCount() { }
	// RVA: 0x3833bac VA: 0x7595e4bbac
	public Void set_themeTotalCount(Int32 value) { }
	// RVA: 0x383e828 VA: 0x7595e56828
	public Int32 get_presetCount() { }
	// RVA: 0x3833ca4 VA: 0x7595e4bca4
	public Void set_presetCount(Int32 value) { }
	// RVA: 0x383e890 VA: 0x7595e56890
	public Int32 get_collectionCount() { }
	// RVA: 0x383e8f8 VA: 0x7595e568f8
	public Void set_collectionCount(Int32 value) { }
	// RVA: 0x38341c4 VA: 0x7595e4c1c4
	public List`1 get_recentThemeDatas() { }
	// RVA: 0x383e974 VA: 0x7595e56974
	public Void set_recentThemeDatas(List`1 value) { }
	// RVA: 0x383422c VA: 0x7595e4c22c
	public List`1 get_recentSingleDatas() { }
	// RVA: 0x383e9f8 VA: 0x7595e569f8
	public Void set_recentSingleDatas(List`1 value) { }
	// RVA: 0x383ea7c VA: 0x7595e56a7c
	public Int32 GetRecentThemeCount() { }
	// RVA: 0x383eafc VA: 0x7595e56afc
	public Int32 GetRecentSingleCount() { }
	// RVA: 0x383eb7c VA: 0x7595e56b7c
	public Void .ctor() { }
}
```