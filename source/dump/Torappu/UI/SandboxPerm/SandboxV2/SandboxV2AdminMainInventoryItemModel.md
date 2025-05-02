# SandboxV2AdminMainInventoryItemModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxPermItemData <itemData>k__BackingField`

- `UIItemViewModel <viewModel>k__BackingField`


## Properties

- `SandboxPermItemData itemData`

- `UIItemViewModel viewModel`


## Methods

- `SandboxPermItemData get_itemData()`

- `Void set_itemData(SandboxPermItemData)`

- `UIItemViewModel get_viewModel()`

- `Void set_viewModel(UIItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainInventoryItemModel : IHotfixable
{
	private SandboxPermItemData <itemData>k__BackingField; // 0x10
	private UIItemViewModel <viewModel>k__BackingField; // 0x18
	public Nullable`1 foodVariantInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_itemData; // 0x8
	private static DelegateBridge __Hotfix0_set_itemData; // 0x10
	private static DelegateBridge __Hotfix0_get_viewModel; // 0x18
	private static DelegateBridge __Hotfix0_set_viewModel; // 0x20

	public SandboxPermItemData itemData { get; set; }
	public UIItemViewModel viewModel { get; set; }

	// RVA: 0x24d68dc VA: 0x7594aee8dc
	public Void .ctor(SandboxPermItemData item, UIItemViewModel vm) { }
	// RVA: 0x24d6a88 VA: 0x7594aeea88
	public SandboxPermItemData get_itemData() { }
	// RVA: 0x24d6980 VA: 0x7594aee980
	private Void set_itemData(SandboxPermItemData value) { }
	// RVA: 0x24d6af0 VA: 0x7594aeeaf0
	public UIItemViewModel get_viewModel() { }
	// RVA: 0x24d6a04 VA: 0x7594aeea04
	private Void set_viewModel(UIItemViewModel value) { }
}
```