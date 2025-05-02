# SandboxV2AdminMainShopItemGroupView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainShopItemGroupAdapter _adapter`

- `Boolean m_hasInited`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void set_onItemClicked(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainShopItemGroupView : DataBinder`1, IHotfixable
{
	private SandboxV2AdminMainShopItemGroupAdapter _adapter; // 0x20
	private Boolean m_hasInited; // 0x28
	private UIPage <page>k__BackingField; // 0x30
	private Action`1 <onItemClicked>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private UIPage page { get; set; }
	private Action`1 onItemClicked { get; set; }

	// RVA: 0x24e9088 VA: 0x7594b01088
	private UIPage get_page() { }
	// RVA: 0x24e90f0 VA: 0x7594b010f0
	public Void set_page(UIPage value) { }
	// RVA: 0x24e9174 VA: 0x7594b01174
	private Action`1 get_onItemClicked() { }
	// RVA: 0x24e91dc VA: 0x7594b011dc
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x24e9260 VA: 0x7594b01260
	public override Void OnValueChanged(SandboxV2AdminMainShopProperty property) { }
	// RVA: 0x24e9330 VA: 0x7594b01330
	private Void _InitIfNot() { }
	// RVA: 0x24e93e8 VA: 0x7594b013e8
	public Void .ctor() { }
}
```