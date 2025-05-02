# ActMultiV3ManualTitleListModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int32 selectedItemIdx`

- `Int32 loadSeqNum`

- `Int64 dragContextID`

- `Boolean isBack`

- `Boolean isValid`


## Properties

- `String selectedTitleId`

- `Int32 pagerSelectedPage`


## Methods

- `String get_selectedTitleId()`

- `Int32 get_pagerSelectedPage()`

- `Int32 SwitchPagerIndex(Int32)`

- `Void LoadData(String, Boolean)`

- `Void UpdateSelection(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualTitleListModel : IHotfixable
{
	public Int32 selectedItemIdx; // 0x10
	public List`1 titleList; // 0x18
	public Int32 loadSeqNum; // 0x20
	public Int64 dragContextID; // 0x28
	public Boolean isBack; // 0x30
	public Boolean isValid; // 0x31
	private static DelegateBridge __Hotfix0_get_selectedTitleId; // 0x0
	private static DelegateBridge __Hotfix0_get_pagerSelectedPage; // 0x8
	private static DelegateBridge __Hotfix0_SwitchPagerIndex; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_UpdateSelection; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String selectedTitleId { get; }
	public Int32 pagerSelectedPage { get; }

	// RVA: 0x31211a8 VA: 0x75957391a8
	public String get_selectedTitleId() { }
	// RVA: 0x311e5c0 VA: 0x75957365c0
	public Int32 get_pagerSelectedPage() { }
	// RVA: 0x311ed90 VA: 0x7595736d90
	public Int32 SwitchPagerIndex(Int32 index) { }
	// RVA: 0x3120b60 VA: 0x7595738b60
	public Void LoadData(String selectedTitleId, Boolean isBack) { }
	// RVA: 0x3120e98 VA: 0x7595738e98
	public Void UpdateSelection(Int32 pageIdx) { }
	// RVA: 0x31210e4 VA: 0x75957390e4
	public Void .ctor() { }
}
```