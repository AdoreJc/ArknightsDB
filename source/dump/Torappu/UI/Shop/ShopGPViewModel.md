# ShopGPViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopGPCommonSortPanelModel panelAllModel`

- `Int32 m_enterSeqNum`

- `Int32 m_fastSeqNum`

- `String m_selectedTabId`


## Properties

- `String selectedTabId`

- `Int32 enterSeq`

- `Int32 fastSeq`


## Methods

- `String get_selectedTabId()`

- `Int32 get_enterSeq()`

- `Int32 get_fastSeq()`

- `Void RefreshData(List`1, List`1)`

- `Void SelectTab(String)`

- `Void TrySelectFirstNotAllTab()`

- `Void NotifyEnter()`

- `Void NotifyFast()`

- `Void _CollectValidTabSet(List`1, List`1, ref)`

- `Void _CollectTabGrp(List`1, Dictionary`2, Action`2)`

- `Boolean _IsTabTimeValid(ShopGPTabDisplayData, Int64)`

- `AbstractShopGPPanelModel _GetPanelModelByType(ShopGPTabType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPViewModel : IHotfixable
{
	public ShopGPCommonSortPanelModel panelAllModel; // 0x10
	public ListDict`2 tabDict; // 0x18
	public Dictionary`2 panelDict; // 0x20
	public Dictionary`2 viewModelDict; // 0x28
	private Int32 m_enterSeqNum; // 0x30
	private Int32 m_fastSeqNum; // 0x34
	private Dictionary`2 m_validTab; // 0x38
	private String m_selectedTabId; // 0x40
	private static DelegateBridge __Hotfix0_get_selectedTabId; // 0x0
	private static DelegateBridge __Hotfix0_get_enterSeq; // 0x8
	private static DelegateBridge __Hotfix0_get_fastSeq; // 0x10
	private static DelegateBridge __Hotfix0_RefreshData; // 0x18
	private static DelegateBridge __Hotfix0_SelectTab; // 0x20
	private static DelegateBridge __Hotfix0_TrySelectFirstNotAllTab; // 0x28
	private static DelegateBridge __Hotfix0_NotifyEnter; // 0x30
	private static DelegateBridge __Hotfix0_NotifyFast; // 0x38
	private static DelegateBridge __Hotfix0__CollectValidTabSet; // 0x40
	private static DelegateBridge __Hotfix0__CollectTabGrp; // 0x48
	private static DelegateBridge __Hotfix0__IsTabTimeValid; // 0x50
	private static DelegateBridge __Hotfix0__GetPanelModelByType; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String selectedTabId { get; }
	public Int32 enterSeq { get; }
	public Int32 fastSeq { get; }

	// RVA: 0x2441854 VA: 0x7594a59854
	public String get_selectedTabId() { }
	// RVA: 0x2444c68 VA: 0x7594a5cc68
	public Int32 get_enterSeq() { }
	// RVA: 0x24417ec VA: 0x7594a597ec
	public Int32 get_fastSeq() { }
	// RVA: 0x24455a8 VA: 0x7594a5d5a8
	public Void RefreshData(List`1 shopItemList, List`1 soldOutItemList) { }
	// RVA: 0x2445058 VA: 0x7594a5d058
	public Void SelectTab(String selectedTabId) { }
	// RVA: 0x2444d40 VA: 0x7594a5cd40
	public Void TrySelectFirstNotAllTab() { }
	// RVA: 0x2444a5c VA: 0x7594a5ca5c
	public Void NotifyEnter() { }
	// RVA: 0x2444cd0 VA: 0x7594a5ccd0
	public Void NotifyFast() { }
	// RVA: 0x2449e48 VA: 0x7594a61e48
	private Void _CollectValidTabSet(List`1 itemList, List`1 soldOutItemList, ref Dictionary`2 tabGroups) { }
	// RVA: 0x244a204 VA: 0x7594a62204
	private Void _CollectTabGrp(List`1 itemList, Dictionary`2 tabGroups, Action`2 actionOnGrp) { }
	// RVA: 0x244a044 VA: 0x7594a62044
	private Boolean _IsTabTimeValid(ShopGPTabDisplayData data, Int64 timeStampNow) { }
	// RVA: 0x244a0f4 VA: 0x7594a620f4
	private AbstractShopGPPanelModel _GetPanelModelByType(ShopGPTabType tabType) { }
	// RVA: 0x244a4c4 VA: 0x7594a624c4
	public Void .ctor() { }
}
```