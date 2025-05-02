# CharacterLvlupWheelViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `String <widgetID>k__BackingField`

- `Int64 <dragContextID>k__BackingField`

- `Int32 selectedItemIndex`

- `Int32 m_startNum`

- `Int32 m_maxAttainableIndex`


## Properties

- `String widgetID`

- `Int64 dragContextID`

- `Int32 pagerSelectedPage`

- `Int32 pagerMaxAttainablePage`


## Methods

- `String get_widgetID()`

- `Void set_widgetID(String)`

- `Int64 get_dragContextID()`

- `Void set_dragContextID(Int64)`

- `Int32 get_pagerSelectedPage()`

- `Int32 get_pagerMaxAttainablePage()`

- `Int32 ConvertItemIndexToPageNum(Int32)`

- `Void LoadData(Int32, Int32, Int32)`

- `Void UpdateSelectedItem(Int32)`

- `Void ForceUpdateDragContext()`

- `Boolean TryGetLevelNumFromPage(Int32, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupWheelViewModel : IHotfixable
{
	private String <widgetID>k__BackingField; // 0x10
	private Int64 <dragContextID>k__BackingField; // 0x18
	public List`1 items; // 0x20
	public Int32 selectedItemIndex; // 0x28
	private Int32 m_startNum; // 0x2c
	private Int32 m_maxAttainableIndex; // 0x30
	private static DelegateBridge __Hotfix0_get_widgetID; // 0x0
	private static DelegateBridge __Hotfix0_set_widgetID; // 0x8
	private static DelegateBridge __Hotfix0_get_dragContextID; // 0x10
	private static DelegateBridge __Hotfix0_set_dragContextID; // 0x18
	private static DelegateBridge __Hotfix0_get_pagerSelectedPage; // 0x20
	private static DelegateBridge __Hotfix0_get_pagerMaxAttainablePage; // 0x28
	private static DelegateBridge __Hotfix0_ConvertItemIndexToPageNum; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_UpdateSelectedItem; // 0x40
	private static DelegateBridge __Hotfix0_ForceUpdateDragContext; // 0x48
	private static DelegateBridge __Hotfix0_TryGetLevelNumFromPage; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String widgetID { get; set; }
	public Int64 dragContextID { get; set; }
	public Int32 pagerSelectedPage { get; }
	public Int32 pagerMaxAttainablePage { get; }

	// RVA: 0x2d63440 VA: 0x759537b440
	public String get_widgetID() { }
	// RVA: 0x2d634a8 VA: 0x759537b4a8
	private Void set_widgetID(String value) { }
	// RVA: 0x2d6352c VA: 0x759537b52c
	public Int64 get_dragContextID() { }
	// RVA: 0x2d63594 VA: 0x759537b594
	private Void set_dragContextID(Int64 value) { }
	// RVA: 0x2d5dd20 VA: 0x7595375d20
	public Int32 get_pagerSelectedPage() { }
	// RVA: 0x2d636b8 VA: 0x759537b6b8
	public Int32 get_pagerMaxAttainablePage() { }
	// RVA: 0x2d63610 VA: 0x759537b610
	public Int32 ConvertItemIndexToPageNum(Int32 index) { }
	// RVA: 0x2d60cc0 VA: 0x7595378cc0
	public Void LoadData(Int32 startNum, Int32 maxNum, Int32 lastAttainableNum) { }
	// RVA: 0x2d6208c VA: 0x759537a08c
	public Void UpdateSelectedItem(Int32 num) { }
	// RVA: 0x2d5dfe0 VA: 0x7595375fe0
	public Void ForceUpdateDragContext() { }
	// RVA: 0x2d61680 VA: 0x7595379680
	public Boolean TryGetLevelNumFromPage(Int32 page, out Int32 level) { }
	// RVA: 0x2d6264c VA: 0x759537a64c
	public Void .ctor() { }
}
```