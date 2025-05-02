# FurnitureSorter

**Namespace:** `Torappu.Building.DIY`


## Methods

- `Void CacheFurnitureStorage()`

- `Int32 _SortingKeyCount(IDIYItem)`

- `Int32 _ShopItemCompareFuncEndTime(IDIYShopItem, IDIYShopItem)`

- `Int32 _ShopItemCompareFuncDiscount(IDIYShopItem, IDIYShopItem)`

- `Int32 _ShopItemCompareFuncPriceAscent(IDIYShopItem, IDIYShopItem)`

- `Int32 _ShopItemCompareFuncPriceDescent(IDIYShopItem, IDIYShopItem)`

- `Int32 _ShopItemCompareFuncRarity(IDIYShopItem, IDIYShopItem)`

- `Int32 _ShopItemCompareFuncComfortAscent(IDIYShopItem, IDIYShopItem)`

- `Int32 _ShopItemCompareFuncComfortDescent(IDIYShopItem, IDIYShopItem)`

- `Int32 _ShopItemCompareFuncStorageCount(IDIYShopItem, IDIYShopItem)`

- `Void <CacheFurnitureStorage>b__3_1(FurnitureStorageItem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class FurnitureSorter
{
	private Dictionary`2 m_furnitureStorageItemCache; // 0x10
	private List`1 m_cacheList; // 0x18
	private List`1 m_shopCacheList; // 0x20


	// RVA: 0x37d572c VA: 0x7595ded72c
	public Void CacheFurnitureStorage() { }
	// RVA: 0x37d5920 VA: 0x7595ded920
	private static Int32 _SortingKeyComfort(IDIYItem diyItem) { }
	// RVA: 0x37d59c0 VA: 0x7595ded9c0
	private static Int32 _SortingKeyRarity(IDIYItem diyItem) { }
	// RVA: 0x37d5a60 VA: 0x7595deda60
	private Int32 _SortingKeyCount(IDIYItem diyItem) { }
	// RVA: 0x37d5b44 VA: 0x7595dedb44
	private static Int32 _ShopCompareAscent(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d60d4 VA: 0x7595dee0d4
	private static Int32 _ShopCompareDescent(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d6664 VA: 0x7595dee664
	private static Func`3 _GetSortingFunctionBySortingKeyFunction(SortingMethod method, Func`2[] keyFunctions) { }
	// RVA: 0x37d6738 VA: 0x7595dee738
	public Func`3 GetSortingFunction(FurnitureSortingOption option, SortingMethod method) { }
	// RVA: 0x37d6b0c VA: 0x7595deeb0c
	private Int32 _ShopItemCompareFuncEndTime(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d6e80 VA: 0x7595deee80
	private Int32 _ShopItemCompareFuncDiscount(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d6f90 VA: 0x7595deef90
	private Int32 _ShopItemCompareFuncPriceAscent(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d7204 VA: 0x7595def204
	private Int32 _ShopItemCompareFuncPriceDescent(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d7478 VA: 0x7595def478
	private Int32 _ShopItemCompareFuncRarity(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d766c VA: 0x7595def66c
	private Int32 _ShopItemCompareFuncComfortAscent(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d7860 VA: 0x7595def860
	private Int32 _ShopItemCompareFuncComfortDescent(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d7a54 VA: 0x7595defa54
	private Int32 _ShopItemCompareFuncStorageCount(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x37d7b88 VA: 0x7595defb88
	private Func`3 _ShopItemCompareFuncCombination(Func`3[] functions) { }
	// RVA: 0x37d7c48 VA: 0x7595defc48
	public Func`3 GetShopSortingFunction(FurnitureSortingOption option, SortingMethod method) { }
	// RVA: 0x37d8254 VA: 0x7595df0254
	public Void .ctor() { }
	// RVA: 0x37d8384 VA: 0x7595df0384
	private Void <CacheFurnitureStorage>b__3_1(FurnitureStorageItem x) { }
}
```