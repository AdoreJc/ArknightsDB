# SandboxV2DungeonCrossDayReportItemModel

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
public class SandboxV2DungeonCrossDayReportItemModel : IHotfixable
{
	private SandboxPermItemData <itemData>k__BackingField; // 0x10
	private UIItemViewModel <viewModel>k__BackingField; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_itemData; // 0x8
	private static DelegateBridge __Hotfix0_set_itemData; // 0x10
	private static DelegateBridge __Hotfix0_get_viewModel; // 0x18
	private static DelegateBridge __Hotfix0_set_viewModel; // 0x20

	public SandboxPermItemData itemData { get; set; }
	public UIItemViewModel viewModel { get; set; }

	// RVA: 0x2524d68 VA: 0x7594b3cd68
	public Void .ctor(SandboxPermItemData item, UIItemViewModel vm) { }
	// RVA: 0x2524f14 VA: 0x7594b3cf14
	public SandboxPermItemData get_itemData() { }
	// RVA: 0x2524e0c VA: 0x7594b3ce0c
	private Void set_itemData(SandboxPermItemData value) { }
	// RVA: 0x2524f7c VA: 0x7594b3cf7c
	public UIItemViewModel get_viewModel() { }
	// RVA: 0x2524e90 VA: 0x7594b3ce90
	private Void set_viewModel(UIItemViewModel value) { }
}
```