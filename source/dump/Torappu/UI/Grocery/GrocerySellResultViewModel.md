# GrocerySellResultViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Int32 day`

- `ItemBundle dailyReward`

- `SellGoodState m_activeState`

- `Int32 m_lastDayFund`


## Properties

- `Boolean isLastSellState`

- `SellGoodState activeState`


## Methods

- `Boolean get_isLastSellState()`

- `SellGoodState get_activeState()`

- `Void LoadData(String, SellGoodState)`

- `Void UpdateDataByResponce(Int32, List`1)`

- `GrocerySellResultStateSellViewModel GetActiveStateSellModel()`

- `IncomingLogData GetIncomingLogDataNotNull()`

- `Boolean _TryGetGoodIdFromSellGoodState(String, String, SellGoodState, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultViewModel : IHotfixable
{
	public Dictionary`2 sellGoodViewModelDict; // 0x10
	public Int32 day; // 0x18
	public ItemBundle dailyReward; // 0x20
	private SellGoodState m_activeState; // 0x28
	private Int32 m_lastDayFund; // 0x2c
	private List`1 m_cachedRewards; // 0x30
	private static DelegateBridge __Hotfix0_get_isLastSellState; // 0x0
	private static DelegateBridge __Hotfix0_get_cachedRewards; // 0x8
	private static DelegateBridge __Hotfix0_get_activeState; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_UpdateDataByResponce; // 0x20
	private static DelegateBridge __Hotfix0_GetActiveStateSellModel; // 0x28
	private static DelegateBridge __Hotfix0_GetIncomingLogDataNotNull; // 0x30
	private static DelegateBridge __Hotfix0__TryGetGoodIdFromSellGoodState; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isLastSellState { get; }
	public List`1 cachedRewards { get; }
	public SellGoodState activeState { get; }

	// RVA: 0x28a0e10 VA: 0x7594eb8e10
	public Boolean get_isLastSellState() { }
	// RVA: 0x28a1e94 VA: 0x7594eb9e94
	public List`1 get_cachedRewards() { }
	// RVA: 0x28a1efc VA: 0x7594eb9efc
	public SellGoodState get_activeState() { }
	// RVA: 0x28a1f64 VA: 0x7594eb9f64
	public Void LoadData(String actId, SellGoodState activeState) { }
	// RVA: 0x28a2ba8 VA: 0x7594ebaba8
	public Void UpdateDataByResponce(Int32 lastFund, List`1 rewards) { }
	// RVA: 0x28a2c38 VA: 0x7594ebac38
	public GrocerySellResultStateSellViewModel GetActiveStateSellModel() { }
	// RVA: 0x28a0e80 VA: 0x7594eb8e80
	public IncomingLogData GetIncomingLogDataNotNull() { }
	// RVA: 0x28a2178 VA: 0x7594eba178
	private Boolean _TryGetGoodIdFromSellGoodState(String actId, String groupId, SellGoodState state, out String goodId) { }
	// RVA: 0x28a2df0 VA: 0x7594ebadf0
	public Void .ctor() { }
}
```