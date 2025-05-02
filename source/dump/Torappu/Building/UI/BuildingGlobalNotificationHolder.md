# BuildingGlobalNotificationHolder

**Namespace:** `Torappu.Building.UI`


## Fields

- `BuildingManufactGainNotify _manufactNotify`

- `BuildingWorkshopBySideNotify _workshopBySideNotify`

- `BuildingLeveldownReturnNotify _leveldownReturnNotify`

- `BuildingFavorNotifyView _favorNotify`

- `BuildingTradingDeliveryNotify _tradingNotify`

- `BuildingManufactSupplementNotify _supplementNotify`

- `BuildingBatchToastView _batchToast`


## Properties

- `BuildingManufactGainNotify manufactNotifyView`

- `BuildingWorkshopBySideNotify workshopBySideNotify`

- `BuildingLeveldownReturnNotify leveldownReturnNotify`

- `BuildingFavorNotifyView favorNotify`

- `BuildingTradingDeliveryNotify tradingNotifyView`

- `BuildingManufactSupplementNotify manufatcSuppleView`

- `BuildingBatchToastView batchToastView`


## Methods

- `BuildingManufactGainNotify get_manufactNotifyView()`

- `BuildingWorkshopBySideNotify get_workshopBySideNotify()`

- `BuildingLeveldownReturnNotify get_leveldownReturnNotify()`

- `BuildingFavorNotifyView get_favorNotify()`

- `BuildingTradingDeliveryNotify get_tradingNotifyView()`

- `BuildingManufactSupplementNotify get_manufatcSuppleView()`

- `BuildingBatchToastView get_batchToastView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingGlobalNotificationHolder : MonoBehaviour, IHotfixable
{
	private BuildingManufactGainNotify _manufactNotify; // 0x18
	private BuildingWorkshopBySideNotify _workshopBySideNotify; // 0x20
	private BuildingLeveldownReturnNotify _leveldownReturnNotify; // 0x28
	private BuildingFavorNotifyView _favorNotify; // 0x30
	private BuildingTradingDeliveryNotify _tradingNotify; // 0x38
	private BuildingManufactSupplementNotify _supplementNotify; // 0x40
	private BuildingBatchToastView _batchToast; // 0x48
	private static DelegateBridge __Hotfix0_get_manufactNotifyView; // 0x0
	private static DelegateBridge __Hotfix0_get_workshopBySideNotify; // 0x8
	private static DelegateBridge __Hotfix0_get_leveldownReturnNotify; // 0x10
	private static DelegateBridge __Hotfix0_get_favorNotify; // 0x18
	private static DelegateBridge __Hotfix0_get_tradingNotifyView; // 0x20
	private static DelegateBridge __Hotfix0_get_manufatcSuppleView; // 0x28
	private static DelegateBridge __Hotfix0_get_batchToastView; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public BuildingManufactGainNotify manufactNotifyView { get; }
	public BuildingWorkshopBySideNotify workshopBySideNotify { get; }
	public BuildingLeveldownReturnNotify leveldownReturnNotify { get; }
	public BuildingFavorNotifyView favorNotify { get; }
	public BuildingTradingDeliveryNotify tradingNotifyView { get; }
	public BuildingManufactSupplementNotify manufatcSuppleView { get; }
	public BuildingBatchToastView batchToastView { get; }

	// RVA: 0x3d38958 VA: 0x7596350958
	public BuildingManufactGainNotify get_manufactNotifyView() { }
	// RVA: 0x3d389c0 VA: 0x75963509c0
	public BuildingWorkshopBySideNotify get_workshopBySideNotify() { }
	// RVA: 0x3d38a28 VA: 0x7596350a28
	public BuildingLeveldownReturnNotify get_leveldownReturnNotify() { }
	// RVA: 0x3d38a90 VA: 0x7596350a90
	public BuildingFavorNotifyView get_favorNotify() { }
	// RVA: 0x3d38af8 VA: 0x7596350af8
	public BuildingTradingDeliveryNotify get_tradingNotifyView() { }
	// RVA: 0x3d38b60 VA: 0x7596350b60
	public BuildingManufactSupplementNotify get_manufatcSuppleView() { }
	// RVA: 0x3d38bc8 VA: 0x7596350bc8
	public BuildingBatchToastView get_batchToastView() { }
	// RVA: 0x3d38c30 VA: 0x7596350c30
	public Void .ctor() { }
}
```