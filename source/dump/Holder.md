# Holder

**Namespace:** ` `


## Fields

- `ShopGPRcmdSortPanel m_closure`


## Methods

- `ShopGPCommonItemView GetCommonItemViewPrefab()`

- `ShopGPMonthlySubItem GetMonthlySubItemViewPrefab()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Holder : IShopGPSimplePanelHolder, IHotfixable
{
	private ShopGPRcmdSortPanel m_closure; // 0x10
	private List`1 m_showItems; // 0x18
	private List`1 m_soldOutItems; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetCommonItemViewPrefab; // 0x8
	private static DelegateBridge __Hotfix0_GetMonthlySubItemViewPrefab; // 0x10
	private static DelegateBridge __Hotfix0_GetItemList; // 0x18
	private static DelegateBridge __Hotfix0_GetSoldOutList; // 0x20


	// RVA: 0x24407ec VA: 0x7594a587ec
	public Void .ctor(ShopGPRcmdSortPanel closure) { }
	// RVA: 0x2440b20 VA: 0x7594a58b20
	public ShopGPCommonItemView GetCommonItemViewPrefab() { }
	// RVA: 0x2440b94 VA: 0x7594a58b94
	public ShopGPMonthlySubItem GetMonthlySubItemViewPrefab() { }
	// RVA: 0x2440c08 VA: 0x7594a58c08
	public IList`1 GetItemList() { }
	// RVA: 0x2440e88 VA: 0x7594a58e88
	public IList`1 GetSoldOutList() { }
}
```