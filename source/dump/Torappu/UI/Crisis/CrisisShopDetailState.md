# CrisisShopDetailState

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `TopMenuDynamicPrefabInstHolder _topmenuHolder`

- `CrisisShopDetailStateBean _stateBean`

- `CrisisShopLeftViewHolder _leftPart`

- `CrisisShopRightViewHolder _rightParts`

- `GameObject _crisisV2CoinTextHolder`

- `GameObject _crisisCoinTextHolder`

- `Text _crisisV2CoinText`


## Methods

- `Void SendBuy(Int32)`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void SendBuy()`

- `Void <OnEnter>b__8_0(GameObject)`

- `Void <OnEnter>b__8_1()`

- `Void <SendBuy>b__9_0(CrisisBuyShopResponse)`

- `Void <_ReceiveItemsCoroutine>b__10_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopDetailState : PopupFloatState
{
	private TopMenuDynamicPrefabInstHolder _topmenuHolder; // 0x70
	private CrisisShopDetailStateBean _stateBean; // 0x78
	private CrisisShopLeftViewHolder _leftPart; // 0x80
	private CrisisShopRightViewHolder _rightParts; // 0x88
	private GameObject _crisisV2CoinTextHolder; // 0x90
	private GameObject _crisisCoinTextHolder; // 0x98
	private Text _crisisV2CoinText; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_SendBuy; // 0x10
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x18
	private static DelegateBridge __Hotfix1_SendBuy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2c1b058 VA: 0x7595233058
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c1b0c0 VA: 0x75952330c0
	protected override Void OnEnter() { }
	// RVA: 0x2c1b25c VA: 0x759523325c
	public Void SendBuy(Int32 buyCount) { }
	// RVA: 0x2c1b640 VA: 0x7595233640
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x2c1b738 VA: 0x7595233738
	public Void SendBuy() { }
	// RVA: 0x2c1b7a4 VA: 0x75952337a4
	public Void .ctor() { }
	// RVA: 0x2c1b850 VA: 0x7595233850
	private Void <OnEnter>b__8_0(GameObject gameObj) { }
	// RVA: 0x2c1b94c VA: 0x759523394c
	private Void <OnEnter>b__8_1() { }
	// RVA: 0x2c1b9fc VA: 0x75952339fc
	private Void <SendBuy>b__9_0(CrisisBuyShopResponse response) { }
	// RVA: 0x2c1ba78 VA: 0x7595233a78
	private Void <_ReceiveItemsCoroutine>b__10_0() { }
	// RVA: 0x2c1ba88 VA: 0x7595233a88
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```