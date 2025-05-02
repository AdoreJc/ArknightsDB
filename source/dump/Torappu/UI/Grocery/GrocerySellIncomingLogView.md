# GrocerySellIncomingLogView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `RectTransform _backPressRect`

- `Text _totalPurchaseCostText`

- `Text _totalSellIncomeText`

- `Text _totalPrizeIncomeText`

- `GrocerySellSpacingTextItem _netIncomeText`

- `Text _lastDayFundText`

- `Text _thisDayFundText`

- `Text _dayNumText`

- `RectTransform _itemCardHolder`

- `Single _itemCardScale`

- `Boolean m_hasInited`

- `UIItemCard m_itemCard`

- `IncomingLogData m_incomingLogData`

- `GrocerySellResultTextTween m_purchaseCostTween`

- `GrocerySellResultTextTween m_sellIncomeTween`

- `GrocerySellResultTextTween m_prizeIncomeTween`

- `GrocerySellResultTextTween m_netIncomeTween`

- `GrocerySellResultTextTween m_thisDayFundTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void PlayTextIncreaseTweenWithDelay()`

- `Void OnBackGroundClicked()`

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__29_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellIncomingLogView : DataBinder`1, IHotfixable
{
	private const Single UPPER_TWEEN_DELAY; // 0x0
	private const Single UPPER_TWEEN_DURATION; // 0x0
	private const Single UPPER_TEXT_APPEAR_DELAY; // 0x0
	private const Single NET_INCOME_TWEEN_DELAY; // 0x0
	private const Single NET_INCOME_TWEEN_DURATION; // 0x0
	private const Single THIS_DAY_FUND_TWEEN_DELAY; // 0x0
	private const Single THIS_DAY_FUND_TWEEN_DURATION; // 0x0
	private RectTransform _backPressRect; // 0x20
	private Text _totalPurchaseCostText; // 0x28
	private Text _totalSellIncomeText; // 0x30
	private Text _totalPrizeIncomeText; // 0x38
	private GrocerySellSpacingTextItem _netIncomeText; // 0x40
	private Text _lastDayFundText; // 0x48
	private Text _thisDayFundText; // 0x50
	private Text _dayNumText; // 0x58
	private RectTransform _itemCardHolder; // 0x60
	private Single _itemCardScale; // 0x68
	private Boolean m_hasInited; // 0x6c
	private UIItemCard m_itemCard; // 0x70
	private IncomingLogData m_incomingLogData; // 0x78
	private GrocerySellResultTextTween m_purchaseCostTween; // 0x90
	private GrocerySellResultTextTween m_sellIncomeTween; // 0x98
	private GrocerySellResultTextTween m_prizeIncomeTween; // 0xa0
	private GrocerySellResultTextTween m_netIncomeTween; // 0xa8
	private GrocerySellResultTextTween m_thisDayFundTween; // 0xb0
	private UIStateFinder m_stateFinder; // 0xb8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_PlayTextIncreaseTweenWithDelay; // 0x8
	private static DelegateBridge __Hotfix0_OnBackGroundClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28a0934 VA: 0x7594eb8934
	public override Void OnValueChanged(GrocerySellResultProperty property) { }
	// RVA: 0x28a1094 VA: 0x7594eb9094
	public Void PlayTextIncreaseTweenWithDelay() { }
	// RVA: 0x28a1510 VA: 0x7594eb9510
	public Void OnBackGroundClicked() { }
	// RVA: 0x28a0a98 VA: 0x7594eb8a98
	private Void _InitIfNot() { }
	// RVA: 0x28a17ac VA: 0x7594eb97ac
	public Void .ctor() { }
	// RVA: 0x28a183c VA: 0x7594eb983c
	private Void <_InitIfNot>b__29_0(Int32 index) { }
}
```