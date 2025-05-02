# ActivityFirstShopSingleState

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `ActivityFirstStateBean _stateBean`

- `ActivityFirstShopDetailSingleView _detailView`


## Methods

- `Void SendBuyShopRequest()`

- `IEnumerator _ReceiveItemsCoroutine(RewardItemModel)`

- `Void <SendBuyShopRequest>b__4_0(ActivityFirstExchangeShopResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstShopSingleState : PopupFloatState
{
	private ActivityFirstStateBean _stateBean; // 0x70
	private ActivityFirstShopDetailSingleView _detailView; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_SendBuyShopRequest; // 0x10
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x348fde4 VA: 0x7595aa7de4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x348fe4c VA: 0x7595aa7e4c
	protected override Void OnEnter() { }
	// RVA: 0x348fee4 VA: 0x7595aa7ee4
	public Void SendBuyShopRequest() { }
	// RVA: 0x3490180 VA: 0x7595aa8180
	private IEnumerator _ReceiveItemsCoroutine(RewardItemModel rewarditem) { }
	// RVA: 0x349028c VA: 0x7595aa828c
	public Void .ctor() { }
	// RVA: 0x34902fc VA: 0x7595aa82fc
	private Void <SendBuyShopRequest>b__4_0(ActivityFirstExchangeShopResponse response) { }
	// RVA: 0x349038c VA: 0x7595aa838c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```