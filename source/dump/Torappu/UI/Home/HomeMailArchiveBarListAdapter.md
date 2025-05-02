# HomeMailArchiveBarListAdapter

**Namespace:** `Torappu.UI.Home`


## Fields

- `GameObject _itemPrefab`

- `Int32 <focusYear>k__BackingField`


## Properties

- `Int32 focusYear`


## Methods

- `Int32 get_focusYear()`

- `Void set_focusYear(Int32)`

- `Void <>xLuaBaseProxy_OnNewItemAlloc(GameObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveBarListAdapter : LoopScrollAdapter`2, IHotfixable
{
	private GameObject _itemPrefab; // 0x58
	private Int32 <focusYear>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_focusYear; // 0x0
	private static DelegateBridge __Hotfix0_set_focusYear; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge __Hotfix0_OnNewItemAlloc; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Int32 focusYear { get; set; }

	// RVA: 0x2845244 VA: 0x7594e5d244
	private Int32 get_focusYear() { }
	// RVA: 0x28452ac VA: 0x7594e5d2ac
	public Void set_focusYear(Int32 value) { }
	// RVA: 0x2845328 VA: 0x7594e5d328
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x28453e8 VA: 0x7594e5d3e8
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, HomeMailArchiveItemViewModel data) { }
	// RVA: 0x2845560 VA: 0x7594e5d560
	protected override Void OnNewItemAlloc(GameObject newItem) { }
	// RVA: 0x2845668 VA: 0x7594e5d668
	public Void .ctor() { }
	// RVA: 0x28456f8 VA: 0x7594e5d6f8
	private Void <>xLuaBaseProxy_OnNewItemAlloc(GameObject P0) { }
}
```