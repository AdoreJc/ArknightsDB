# ArchiveChaosModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String m_selectedItemId`

- `ChaosItemModel m_selectedItem`

- `Boolean m_showSwitchTween`


## Properties

- `String selectedItemId`

- `ChaosItemModel selectedItem`

- `Boolean showSwitchTween`

- `Int32 newNum`


## Methods

- `String get_selectedItemId()`

- `ChaosItemModel get_selectedItem()`

- `Boolean get_showSwitchTween()`

- `Int32 get_newNum()`

- `Void LoadData(String, RoguelikeArchiveComponentData, ActArchiveInfo)`

- `Void SelectItem(String)`

- `String _GetDefaultItemId()`

- `Int32 _ItemComparison(KeyValuePair`2, KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChaosModel : IHotfixable
{
	private ListDict`2 m_items; // 0x10
	private List`1 m_itemList; // 0x18
	private Dictionary`2 m_childItems; // 0x20
	private String m_selectedItemId; // 0x28
	private ChaosItemModel m_selectedItem; // 0x30
	private Boolean m_showSwitchTween; // 0x38
	private static DelegateBridge __Hotfix0_get_items; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedItemId; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedItem; // 0x10
	private static DelegateBridge __Hotfix0_get_showSwitchTween; // 0x18
	private static DelegateBridge __Hotfix0_get_newNum; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_SelectItem; // 0x30
	private static DelegateBridge __Hotfix0__GetDefaultItemId; // 0x38
	private static DelegateBridge __Hotfix0__ItemComparison; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public List`1 items { get; }
	public String selectedItemId { get; }
	public ChaosItemModel selectedItem { get; }
	public Boolean showSwitchTween { get; }
	public Int32 newNum { get; }

	// RVA: 0x3040764 VA: 0x7595658764
	public List`1 get_items() { }
	// RVA: 0x30407cc VA: 0x75956587cc
	public String get_selectedItemId() { }
	// RVA: 0x3040834 VA: 0x7595658834
	public ChaosItemModel get_selectedItem() { }
	// RVA: 0x3040b0c VA: 0x7595658b0c
	public Boolean get_showSwitchTween() { }
	// RVA: 0x3041780 VA: 0x7595659780
	public Int32 get_newNum() { }
	// RVA: 0x3041b0c VA: 0x7595659b0c
	public Void LoadData(String archiveId, RoguelikeArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x304230c VA: 0x759565a30c
	public Void SelectItem(String id) { }
	// RVA: 0x304244c VA: 0x759565a44c
	private String _GetDefaultItemId() { }
	// RVA: 0x3042534 VA: 0x759565a534
	private Int32 _ItemComparison(KeyValuePair`2 x, KeyValuePair`2 y) { }
	// RVA: 0x30425f4 VA: 0x759565a5f4
	public Void .ctor() { }
}
```