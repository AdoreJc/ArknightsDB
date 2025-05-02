# ShopGPTabItemModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `String tabId`

- `String tabName`

- `ShopGPTabType tabType`

- `String tabPicId`

- `String tabPicOnColor`

- `String tabPicOffColor`

- `Int32 sortId`

- `String markerPicId`


## Methods

- `Void RefreshData(ShopGPTabDisplayData)`

- `Int32 CompareTo(ShopGPTabItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPTabItemModel : IHotfixable, IComparable`1
{
	public String tabId; // 0x10
	public String tabName; // 0x18
	public ShopGPTabType tabType; // 0x20
	public String tabPicId; // 0x28
	public String tabPicOnColor; // 0x30
	public String tabPicOffColor; // 0x38
	public Int32 sortId; // 0x40
	public String markerPicId; // 0x48
	private static DelegateBridge __Hotfix0_RefreshData; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2449488 VA: 0x7594a61488
	public Void RefreshData(ShopGPTabDisplayData data) { }
	// RVA: 0x2449574 VA: 0x7594a61574
	public Int32 CompareTo(ShopGPTabItemModel other) { }
	// RVA: 0x2449628 VA: 0x7594a61628
	public Void .ctor() { }
}
```