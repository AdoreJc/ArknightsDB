# SandboxV2RacerInventoryListAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _itemPrefab`

- `String <selectedInstId>k__BackingField`


## Properties

- `String selectedInstId`


## Methods

- `String get_selectedInstId()`

- `Void set_selectedInstId(String)`

- `Void <>xLuaBaseProxy_OnNewItemAlloc(GameObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerInventoryListAdapter : LoopScrollAdapter`2
{
	private GameObject _itemPrefab; // 0x58
	private String <selectedInstId>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_selectedInstId; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedInstId; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_OnNewItemAlloc; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private String selectedInstId { get; set; }

	// RVA: 0x25e11b0 VA: 0x7594bf91b0
	private String get_selectedInstId() { }
	// RVA: 0x25e1218 VA: 0x7594bf9218
	public Void set_selectedInstId(String value) { }
	// RVA: 0x25e129c VA: 0x7594bf929c
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x25e135c VA: 0x7594bf935c
	protected override Void OnNewItemAlloc(GameObject newItem) { }
	// RVA: 0x25e1464 VA: 0x7594bf9464
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, KeyValuePair`2 pair) { }
	// RVA: 0x25e1610 VA: 0x7594bf9610
	public Void .ctor() { }
	// RVA: 0x25e16a0 VA: 0x7594bf96a0
	private Void <>xLuaBaseProxy_OnNewItemAlloc(GameObject P0) { }
}
```