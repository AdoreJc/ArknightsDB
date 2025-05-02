# SandboxV2AdminMainShopItemGroupAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _prefabItem`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void set_onItemClicked(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainShopItemGroupAdapter : LoopScrollAdapter`2, IHotfixable
{
	private GameObject _prefabItem; // 0x58
	private UIPage <page>k__BackingField; // 0x60
	private Action`1 <onItemClicked>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_CreateView; // 0x20
	private static DelegateBridge __Hotfix0_UpdateView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private UIPage page { get; set; }
	private Action`1 onItemClicked { get; set; }

	// RVA: 0x24e8648 VA: 0x7594b00648
	private UIPage get_page() { }
	// RVA: 0x24e86b0 VA: 0x7594b006b0
	public Void set_page(UIPage value) { }
	// RVA: 0x24e8734 VA: 0x7594b00734
	private Action`1 get_onItemClicked() { }
	// RVA: 0x24e879c VA: 0x7594b0079c
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x24e8820 VA: 0x7594b00820
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x24e88e0 VA: 0x7594b008e0
	public override Void UpdateView(Int32 position, GameObject view, SandboxV2AdminMainShopItemHolder holder, SandboxV2AdminMainShopItemViewModel data) { }
	// RVA: 0x24e8ff8 VA: 0x7594b00ff8
	public Void .ctor() { }
}
```