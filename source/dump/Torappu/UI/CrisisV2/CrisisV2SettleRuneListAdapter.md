# CrisisV2SettleRuneListAdapter

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2SettleRuneItemView _itemViewPrefab`

- `ILoadAsset <loader>k__BackingField`

- `CrisisV2SettleViewType <type>k__BackingField`


## Properties

- `ILoadAsset loader`

- `CrisisV2SettleViewType type`


## Methods

- `ILoadAsset get_loader()`

- `Void set_loader(ILoadAsset)`

- `CrisisV2SettleViewType get_type()`

- `Void set_type(CrisisV2SettleViewType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SettleRuneListAdapter : LoopScrollAdapter`2
{
	private CrisisV2SettleRuneItemView _itemViewPrefab; // 0x58
	private ILoadAsset <loader>k__BackingField; // 0x60
	private CrisisV2SettleViewType <type>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_loader; // 0x0
	private static DelegateBridge __Hotfix0_set_loader; // 0x8
	private static DelegateBridge __Hotfix0_get_type; // 0x10
	private static DelegateBridge __Hotfix0_set_type; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_CreateView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private ILoadAsset loader { get; set; }
	private CrisisV2SettleViewType type { get; set; }

	// RVA: 0x2bd0cdc VA: 0x75951e8cdc
	private ILoadAsset get_loader() { }
	// RVA: 0x2bd0d44 VA: 0x75951e8d44
	public Void set_loader(ILoadAsset value) { }
	// RVA: 0x2bd0dc8 VA: 0x75951e8dc8
	private CrisisV2SettleViewType get_type() { }
	// RVA: 0x2bd0e30 VA: 0x75951e8e30
	public Void set_type(CrisisV2SettleViewType value) { }
	// RVA: 0x2bd0eac VA: 0x75951e8eac
	public override Void UpdateView(Int32 position, GameObject view, CrisisV2SettleRuneItemViewHolder holder, CrisisV2SettleRuneItemViewModel data) { }
	// RVA: 0x2bd0fec VA: 0x75951e8fec
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2bd10bc VA: 0x75951e90bc
	public Void .ctor() { }
}
```