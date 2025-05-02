# ActivityFirstShopComplexState

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `ActivityFirstStateBean _stateBean`

- `ActivityFirstShopDetailComplexView _detailView`


## Methods

- `Void SendBuyShopRequest()`

- `IEnumerator _ReceiveItemsCoroutine(RewardItemModel)`

- `Void <SendBuyShopRequest>b__4_0(ActivityFirstExchangeShopResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstShopComplexState : PopupFloatState
{
	private ActivityFirstStateBean _stateBean; // 0x70
	private ActivityFirstShopDetailComplexView _detailView; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_SendBuyShopRequest; // 0x10
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x348f634 VA: 0x7595aa7634
	public override IStateBean GetCacheBean() { }
	// RVA: 0x348f69c VA: 0x7595aa769c
	protected override Void OnEnter() { }
	// RVA: 0x348f734 VA: 0x7595aa7734
	public Void SendBuyShopRequest() { }
	// RVA: 0x348f980 VA: 0x7595aa7980
	private IEnumerator _ReceiveItemsCoroutine(RewardItemModel rewarditem) { }
	// RVA: 0x348fa8c VA: 0x7595aa7a8c
	public Void .ctor() { }
	// RVA: 0x348fafc VA: 0x7595aa7afc
	private Void <SendBuyShopRequest>b__4_0(ActivityFirstExchangeShopResponse response) { }
	// RVA: 0x348fb8c VA: 0x7595aa7b8c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```