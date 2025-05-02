# BuildingTradingDeliveryController

**Namespace:** `Torappu.Building.UI.Trading`


## Methods

- `Void _Clear()`

- `IEnumerator _DeliveryCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingDeliveryController : PageSingleComponent
{
	private const Single DELIVERY_EFFECT_DURATION; // 0x0
	private List`1 m_orderLogs; // 0x20
	private static DelegateBridge __Hotfix0_GetInstance; // 0x0
	private static DelegateBridge __Hotfix0_LogOrderForDelivery; // 0x8
	private static DelegateBridge __Hotfix0_TriggerDeliveryEffect; // 0x10
	private static DelegateBridge __Hotfix0_ClearLog; // 0x18
	private static DelegateBridge __Hotfix0__Clear; // 0x20
	private static DelegateBridge __Hotfix0__DeliveryCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__GetRewardItemType; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3d82e8c VA: 0x759639ae8c
	public static BuildingTradingDeliveryController GetInstance() { }
	// RVA: 0x3d82f0c VA: 0x759639af0c
	public static Void LogOrderForDelivery(BuildingTradingOrderView orderView, TradingOrderStruct orderStruct) { }
	// RVA: 0x3d80fd0 VA: 0x7596398fd0
	public static Coroutine TriggerDeliveryEffect() { }
	// RVA: 0x3d80e34 VA: 0x7596398e34
	public static Void ClearLog() { }
	// RVA: 0x3d831c8 VA: 0x759639b1c8
	private Void _Clear() { }
	// RVA: 0x3d8311c VA: 0x759639b11c
	private IEnumerator _DeliveryCoroutine() { }
	// RVA: 0x3d83298 VA: 0x759639b298
	private static ItemType _GetRewardItemType(TradingOrderReward rewardType) { }
	// RVA: 0x3d83318 VA: 0x759639b318
	public Void .ctor() { }
}
```