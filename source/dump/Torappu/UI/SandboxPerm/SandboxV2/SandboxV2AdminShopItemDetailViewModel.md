# SandboxV2AdminShopItemDetailViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String topicId`

- `Int32 goodIndex`

- `String itemId`

- `String itemName`

- `Int32 itemCount`

- `String itemUsage`

- `String itemDesc`

- `Int32 ownCount`

- `SandboxV2CoinType coinType`

- `Int32 originPrice`

- `Int32 currPrice`

- `Boolean isDiscount`

- `Int32 stock`

- `Int32 buyCount`

- `Int32 currentCost`

- `Int32 goldCount`

- `String goldItemId`

- `Int32 dimensionCoinCount`

- `String dimensionCoinItemId`

- `Boolean showGold`

- `Boolean showDimensionCoin`

- `Int32 canCostCoinCount`

- `String m_goodId`

- `Int32 m_canBuyMaxCount`


## Properties

- `Boolean canBuy`


## Methods

- `Boolean get_canBuy()`

- `Void LoadData(String, Int32, Boolean, Boolean)`

- `Boolean TryIncreaseBuyCount()`

- `Boolean TryDecreaseBuyCount()`

- `Void _UpdateCurrentCost()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminShopItemDetailViewModel : IHotfixable
{
	private const Int32 MIN_BUY_COUNT; // 0x0
	public String topicId; // 0x10
	public Int32 goodIndex; // 0x18
	public String itemId; // 0x20
	public String itemName; // 0x28
	public Int32 itemCount; // 0x30
	public String itemUsage; // 0x38
	public String itemDesc; // 0x40
	public Int32 ownCount; // 0x48
	public SandboxV2CoinType coinType; // 0x4c
	public Int32 originPrice; // 0x50
	public Int32 currPrice; // 0x54
	public Boolean isDiscount; // 0x58
	public Int32 stock; // 0x5c
	public Int32 buyCount; // 0x60
	public Int32 currentCost; // 0x64
	public Int32 goldCount; // 0x68
	public String goldItemId; // 0x70
	public Int32 dimensionCoinCount; // 0x78
	public String dimensionCoinItemId; // 0x80
	public Boolean showGold; // 0x88
	public Boolean showDimensionCoin; // 0x89
	public Int32 canCostCoinCount; // 0x8c
	private String m_goodId; // 0x90
	private Int32 m_canBuyMaxCount; // 0x98
	private static DelegateBridge __Hotfix0_get_canBuy; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_TryIncreaseBuyCount; // 0x10
	private static DelegateBridge __Hotfix0_TryDecreaseBuyCount; // 0x18
	private static DelegateBridge __Hotfix0__UpdateCurrentCost; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean canBuy { get; }

	// RVA: 0x24f9928 VA: 0x7594b11928
	public Boolean get_canBuy() { }
	// RVA: 0x24f7920 VA: 0x7594b0f920
	public Void LoadData(String topicId, Int32 goodIndex, Boolean showGold, Boolean showDimensionCoin) { }
	// RVA: 0x24f8534 VA: 0x7594b10534
	public Boolean TryIncreaseBuyCount() { }
	// RVA: 0x24f85c4 VA: 0x7594b105c4
	public Boolean TryDecreaseBuyCount() { }
	// RVA: 0x24f9cf4 VA: 0x7594b11cf4
	private Void _UpdateCurrentCost() { }
	// RVA: 0x24f9d68 VA: 0x7594b11d68
	public Void .ctor() { }
}
```