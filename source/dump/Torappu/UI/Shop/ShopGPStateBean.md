# ShopGPStateBean

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopGPProperty tabProperty`


## Methods

- `Void InitData(GetGPGoodListResponse)`

- `Void SortItem()`

- `Void _TraceItemsSafe()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public List`1 shopItemList; // 0x18
	public List`1 soldOutItemList; // 0x20
	public ShopGPProperty tabProperty; // 0x28
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_SortItem; // 0x8
	private static DelegateBridge __Hotfix0__TraceItemsSafe; // 0x10
	private static DelegateBridge __Hotfix0__PopulateLevelGPs; // 0x18
	private static DelegateBridge __Hotfix0__PopulateMonthlyGroup; // 0x20
	private static DelegateBridge __Hotfix0__PopulateWeeklyGroup; // 0x28
	private static DelegateBridge __Hotfix0__PopulateMonthlySub; // 0x30
	private static DelegateBridge __Hotfix0__PopulateOneTimeGP; // 0x38
	private static DelegateBridge __Hotfix0__PopulateChooseGroup; // 0x40
	private static DelegateBridge __Hotfix0__PopulateCondTrigGroup; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x24453b8 VA: 0x7594a5d3b8
	public Void InitData(GetGPGoodListResponse response) { }
	// RVA: 0x244896c VA: 0x7594a6096c
	public Void SortItem() { }
	// RVA: 0x2448bfc VA: 0x7594a60bfc
	private Void _TraceItemsSafe() { }
	// RVA: 0x2446e08 VA: 0x7594a5ee08
	private static Void _PopulateLevelGPs(GetGPGoodListResponse response, List`1 shopItemList, List`1 soldOutItemList, PlayerGiftProgressData playerShop) { }
	// RVA: 0x2447118 VA: 0x7594a5f118
	private static Void _PopulateMonthlyGroup(GetGPGoodListResponse response, List`1 shopItemList, List`1 soldOutItemList, PlayerGiftProgressData playerShop) { }
	// RVA: 0x2447628 VA: 0x7594a5f628
	private static Void _PopulateWeeklyGroup(GetGPGoodListResponse response, List`1 shopItemList, List`1 soldOutItemList, PlayerGiftProgressData playerShop) { }
	// RVA: 0x2447b34 VA: 0x7594a5fb34
	private static Void _PopulateMonthlySub(GetGPGoodListResponse response, List`1 shopItemList, List`1 soldOutItemList, PlayerGiftProgressData playerShop) { }
	// RVA: 0x2447eec VA: 0x7594a5feec
	private static Void _PopulateOneTimeGP(GetGPGoodListResponse response, List`1 shopItemList, List`1 soldOutItemList, PlayerGiftProgressData playerShop) { }
	// RVA: 0x244829c VA: 0x7594a6029c
	private static Void _PopulateChooseGroup(GetGPGoodListResponse response, List`1 shopItemList, List`1 soldOutItemList, PlayerGiftProgressData playerShop) { }
	// RVA: 0x2448700 VA: 0x7594a60700
	private static Void _PopulateCondTrigGroup(GetGPGoodListResponse response, List`1 shopItemList, List`1 soldOutItemList, PlayerGiftProgressData playerShop) { }
	// RVA: 0x2448d70 VA: 0x7594a60d70
	public Void .ctor() { }
}
```