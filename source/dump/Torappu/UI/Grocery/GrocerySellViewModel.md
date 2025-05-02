# GrocerySellViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Int32 <selectPrice>k__BackingField`

- `Int32 totalCustomer`

- `SellGoodState currentSellGood`

- `Int32 maxProgressCount`

- `String goodId`

- `String goodName`

- `String goodIconId`

- `String sellDesc`

- `Int32 goodStock`

- `String actId`

- `Int32 inquireCount`

- `Int32 inquireTotal`

- `Boolean hasSold`

- `Int32 <resetPriceSelection>k__BackingField`

- `GrocerySellCustomerModel currCustomerInfo`

- `String m_playerShopId`


## Properties

- `Int32 selectPrice`

- `Int32 resetPriceSelection`

- `InquireStatus inquireStatus`

- `Boolean needInquire`


## Methods

- `Int32 get_selectPrice()`

- `Void set_selectPrice(Int32)`

- `Int32 get_resetPriceSelection()`

- `Void set_resetPriceSelection(Int32)`

- `InquireStatus get_inquireStatus()`

- `Boolean get_needInquire()`

- `Void LoadData(String)`

- `Int32 GetDefaultPrice()`

- `Int32 FindSelectPriceIndex()`

- `Void UpdateSelectPrice(Int32, Boolean)`

- `Act27SideGoodData _LoadGoodData(Act27SideGoodLaunchData, Act27SideData, PlayerAct27SideActivity)`

- `Act27SideGoodLaunchData _LoadLaunchData(Act27SideData, PlayerAct27SideActivity)`

- `Void _LoadShopDataAndPriceData(Act27SideGoodData, Act27SideData, PlayerAct27SideActivity)`

- `PreSellInfo _FindPreSellInfo(Int32, PlayerAct27SideActivity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellViewModel : IHotfixable
{
	private Int32 <selectPrice>k__BackingField; // 0x10
	public Int32 totalCustomer; // 0x14
	public SellGoodState currentSellGood; // 0x18
	public Int32 maxProgressCount; // 0x1c
	public String goodId; // 0x20
	public String goodName; // 0x28
	public String goodIconId; // 0x30
	public String sellDesc; // 0x38
	public List`1 goodPriceList; // 0x40
	public Int32 goodStock; // 0x48
	public String actId; // 0x50
	public Int32 inquireCount; // 0x58
	public Int32 inquireTotal; // 0x5c
	public Boolean hasSold; // 0x60
	private Int32 <resetPriceSelection>k__BackingField; // 0x64
	public List`1 shopList; // 0x68
	public GrocerySellCustomerModel currCustomerInfo; // 0x70
	private String m_playerShopId; // 0x78
	private List`1 m_customerInfoList; // 0x80
	private static DelegateBridge __Hotfix0_get_selectPrice; // 0x0
	private static DelegateBridge __Hotfix0_set_selectPrice; // 0x8
	private static DelegateBridge __Hotfix0_get_resetPriceSelection; // 0x10
	private static DelegateBridge __Hotfix0_set_resetPriceSelection; // 0x18
	private static DelegateBridge __Hotfix0_get_inquireStatus; // 0x20
	private static DelegateBridge __Hotfix0_get_needInquire; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_GetDefaultPrice; // 0x38
	private static DelegateBridge __Hotfix0_FindSelectPriceIndex; // 0x40
	private static DelegateBridge __Hotfix0_UpdateSelectPrice; // 0x48
	private static DelegateBridge __Hotfix0__LoadGoodData; // 0x50
	private static DelegateBridge __Hotfix0__LoadLaunchData; // 0x58
	private static DelegateBridge __Hotfix0__LoadShopDataAndPriceData; // 0x60
	private static DelegateBridge __Hotfix0__FindPreSellInfo; // 0x68
	private static DelegateBridge __Hotfix0__GetCustomerCountArray; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Int32 selectPrice { get; set; }
	public Int32 resetPriceSelection { get; set; }
	public InquireStatus inquireStatus { get; }
	public Boolean needInquire { get; }

	// RVA: 0x289d1b4 VA: 0x7594eb51b4
	public Int32 get_selectPrice() { }
	// RVA: 0x289f394 VA: 0x7594eb7394
	private Void set_selectPrice(Int32 value) { }
	// RVA: 0x289f410 VA: 0x7594eb7410
	public Int32 get_resetPriceSelection() { }
	// RVA: 0x289f478 VA: 0x7594eb7478
	private Void set_resetPriceSelection(Int32 value) { }
	// RVA: 0x289e454 VA: 0x7594eb6454
	public InquireStatus get_inquireStatus() { }
	// RVA: 0x289d504 VA: 0x7594eb5504
	public Boolean get_needInquire() { }
	// RVA: 0x289cfc8 VA: 0x7594eb4fc8
	public Void LoadData(String actId) { }
	// RVA: 0x289d21c VA: 0x7594eb521c
	public Int32 GetDefaultPrice() { }
	// RVA: 0x289d9f8 VA: 0x7594eb59f8
	public Int32 FindSelectPriceIndex() { }
	// RVA: 0x289d2d4 VA: 0x7594eb52d4
	public Void UpdateSelectPrice(Int32 selectPrice, Boolean markForceResetPrice) { }
	// RVA: 0x289f720 VA: 0x7594eb7720
	private Act27SideGoodData _LoadGoodData(Act27SideGoodLaunchData launchData, Act27SideData gameData, PlayerAct27SideActivity playerData) { }
	// RVA: 0x289f5dc VA: 0x7594eb75dc
	private Act27SideGoodLaunchData _LoadLaunchData(Act27SideData gameData, PlayerAct27SideActivity playerData) { }
	// RVA: 0x289fb8c VA: 0x7594eb7b8c
	private Void _LoadShopDataAndPriceData(Act27SideGoodData goodData, Act27SideData gameData, PlayerAct27SideActivity playerData) { }
	// RVA: 0x28a02a4 VA: 0x7594eb82a4
	private PreSellInfo _FindPreSellInfo(Int32 price, PlayerAct27SideActivity playerData) { }
	// RVA: 0x28a0468 VA: 0x7594eb8468
	private Int32[] _GetCustomerCountArray(PreSellInfo sellInfo, String shopId) { }
	// RVA: 0x28a0674 VA: 0x7594eb8674
	public Void .ctor() { }
}
```