# RoguelikeGameBankViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Bank m_gameBankPlayerData`

- `Bank m_topicBankPlayerData`

- `Int32 m_gameGold`

- `String m_topicId`

- `String m_withdrawCostId`

- `Int32 m_withdrawTotalLimitCount`

- `Int32 m_singleWithdrawMaxCount`

- `BankWithdrawModelPlugin m_withdrawPlugin`


## Properties

- `Int32 current`

- `Int32 withdrawCost`

- `Int32 gold`

- `Boolean isFaulty`

- `Boolean canWithdrawViewShow`

- `Int32 hasWithdrawnCount`

- `String withdrawCostItemId`

- `BankWithdrawModelPlugin withdrawPlugin`

- `Int32 withdrawLimit`


## Methods

- `Int32 get_current()`

- `Int32 get_withdrawCost()`

- `Int32 get_gold()`

- `Boolean get_isFaulty()`

- `Boolean get_canWithdrawViewShow()`

- `Int32 get_hasWithdrawnCount()`

- `String get_withdrawCostItemId()`

- `BankWithdrawModelPlugin get_withdrawPlugin()`

- `Int32 get_withdrawLimit()`

- `Void LoadData(String, Bank)`

- `Void InjectPlugin(BankWithdrawModelPlugin)`

- `BankInvestStatus GetBankInvestStatus()`

- `Boolean CheckCanWithdraw()`

- `Boolean CheckWithdrawReachLimit(Int32)`

- `Void WithdrawIncrementCurrent()`

- `Void WithdrawDecrementCurrent()`

- `Void WithdrawMaxCurrent()`

- `Void WithdrawMinCurrent()`

- `Int32 GetWithdrawCount()`

- `Void _LoadConstData()`

- `Void _LoadPlugin()`

- `Boolean _HasNewBankReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameBankViewModel : IHotfixable
{
	private Bank m_gameBankPlayerData; // 0x10
	private Bank m_topicBankPlayerData; // 0x18
	private Int32 m_gameGold; // 0x20
	private String m_topicId; // 0x28
	private String m_withdrawCostId; // 0x30
	private Int32 m_withdrawTotalLimitCount; // 0x38
	private Int32 m_singleWithdrawMaxCount; // 0x3c
	private BankWithdrawModelPlugin m_withdrawPlugin; // 0x40
	private static DelegateBridge __Hotfix0_get_current; // 0x0
	private static DelegateBridge __Hotfix0_get_withdrawCost; // 0x8
	private static DelegateBridge __Hotfix0_get_gold; // 0x10
	private static DelegateBridge __Hotfix0_get_isFaulty; // 0x18
	private static DelegateBridge __Hotfix0_get_canWithdrawViewShow; // 0x20
	private static DelegateBridge __Hotfix0_get_hasWithdrawnCount; // 0x28
	private static DelegateBridge __Hotfix0_get_withdrawCostItemId; // 0x30
	private static DelegateBridge __Hotfix0_get_withdrawPlugin; // 0x38
	private static DelegateBridge __Hotfix0_get_withdrawLimit; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x50
	private static DelegateBridge __Hotfix0_GetBankInvestStatus; // 0x58
	private static DelegateBridge __Hotfix0_CheckCanWithdraw; // 0x60
	private static DelegateBridge __Hotfix0_CheckWithdrawReachLimit; // 0x68
	private static DelegateBridge __Hotfix0_WithdrawIncrementCurrent; // 0x70
	private static DelegateBridge __Hotfix0_WithdrawDecrementCurrent; // 0x78
	private static DelegateBridge __Hotfix0_WithdrawMaxCurrent; // 0x80
	private static DelegateBridge __Hotfix0_WithdrawMinCurrent; // 0x88
	private static DelegateBridge __Hotfix0_GetWithdrawCount; // 0x90
	private static DelegateBridge __Hotfix0__LoadConstData; // 0x98
	private static DelegateBridge __Hotfix0__LoadPlugin; // 0xa0
	private static DelegateBridge __Hotfix0__HasNewBankReward; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public Int32 current { get; }
	public Int32 withdrawCost { get; }
	public Int32 gold { get; }
	public Boolean isFaulty { get; }
	public Boolean canWithdrawViewShow { get; }
	public Int32 hasWithdrawnCount { get; }
	public String withdrawCostItemId { get; }
	public BankWithdrawModelPlugin withdrawPlugin { get; }
	public Int32 withdrawLimit { get; }

	// RVA: 0x2add2b4 VA: 0x75950f52b4
	public Int32 get_current() { }
	// RVA: 0x2adf58c VA: 0x75950f758c
	public Int32 get_withdrawCost() { }
	// RVA: 0x2ade900 VA: 0x75950f6900
	public Int32 get_gold() { }
	// RVA: 0x2ad8e10 VA: 0x75950f0e10
	public Boolean get_isFaulty() { }
	// RVA: 0x2addda8 VA: 0x75950f5da8
	public Boolean get_canWithdrawViewShow() { }
	// RVA: 0x2ad8fac VA: 0x75950f0fac
	public Int32 get_hasWithdrawnCount() { }
	// RVA: 0x2add414 VA: 0x75950f5414
	public String get_withdrawCostItemId() { }
	// RVA: 0x2add15c VA: 0x75950f515c
	public BankWithdrawModelPlugin get_withdrawPlugin() { }
	// RVA: 0x2adfa8c VA: 0x75950f7a8c
	public Int32 get_withdrawLimit() { }
	// RVA: 0x2adfb0c VA: 0x75950f7b0c
	public Void LoadData(String topicId, Bank bank) { }
	// RVA: 0x2adfd88 VA: 0x75950f7d88
	public Void InjectPlugin(BankWithdrawModelPlugin plugin) { }
	// RVA: 0x2adb194 VA: 0x75950f3194
	public BankInvestStatus GetBankInvestStatus() { }
	// RVA: 0x2adf41c VA: 0x75950f741c
	public Boolean CheckCanWithdraw() { }
	// RVA: 0x2adffb0 VA: 0x75950f7fb0
	public Boolean CheckWithdrawReachLimit(Int32 hasWithdrawnCount) { }
	// RVA: 0x2ae00b8 VA: 0x75950f80b8
	public Void WithdrawIncrementCurrent() { }
	// RVA: 0x2ae01a8 VA: 0x75950f81a8
	public Void WithdrawDecrementCurrent() { }
	// RVA: 0x2ae0298 VA: 0x75950f8298
	public Void WithdrawMaxCurrent() { }
	// RVA: 0x2ae0388 VA: 0x75950f8388
	public Void WithdrawMinCurrent() { }
	// RVA: 0x2ae0478 VA: 0x75950f8478
	public Int32 GetWithdrawCount() { }
	// RVA: 0x2adfc04 VA: 0x75950f7c04
	private Void _LoadConstData() { }
	// RVA: 0x2adfd0c VA: 0x75950f7d0c
	private Void _LoadPlugin() { }
	// RVA: 0x2adfe0c VA: 0x75950f7e0c
	private Boolean _HasNewBankReward() { }
	// RVA: 0x2ae05fc VA: 0x75950f85fc
	public Void .ctor() { }
}
```