# GrocerySellResultShopModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String shopId`

- `Int32 sortId`

- `String iconId`

- `Int32 price`

- `GrocerySellCustomerModel currCustomerInfo`


## Properties

- `InquireStatus inquireStatus`


## Methods

- `InquireStatus get_inquireStatus()`

- `Void UpdateSelectPrice(Int32)`

- `Void LoadCustomerInfo(Int32, Int32[])`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultShopModel : IHotfixable, IComparable
{
	public String shopId; // 0x10
	public Int32 sortId; // 0x18
	public String iconId; // 0x20
	public Int32 price; // 0x28
	public GrocerySellCustomerModel currCustomerInfo; // 0x30
	private List`1 m_customerInfoList; // 0x38
	private static DelegateBridge __Hotfix0_get_inquireStatus; // 0x0
	private static DelegateBridge __Hotfix0_UpdateSelectPrice; // 0x8
	private static DelegateBridge __Hotfix0_LoadCustomerInfo; // 0x10
	private static DelegateBridge __Hotfix0_CompareTo; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public InquireStatus inquireStatus { get; }

	// RVA: 0x28a0788 VA: 0x7594eb8788
	public InquireStatus get_inquireStatus() { }
	// RVA: 0x28a009c VA: 0x7594eb809c
	public Void UpdateSelectPrice(Int32 selectPrice) { }
	// RVA: 0x28a0534 VA: 0x7594eb8534
	public Void LoadCustomerInfo(Int32 price, Int32[] customerCount) { }
	// RVA: 0x28a0838 VA: 0x7594eb8838
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x28a01e0 VA: 0x7594eb81e0
	public Void .ctor() { }
}
```