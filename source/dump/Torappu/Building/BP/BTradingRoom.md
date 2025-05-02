# BTradingRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `GameObject _iconOrders`

- `TradingInfoViewStruct m_tradingInfo`

- `Boolean m_isDelivertable`


## Methods

- `Void _OnProcess(BuildingDeliveryBatchOrderResponse)`

- `Void _DoBatchOrderToast(ListDict`2)`

- `Void _SetIsDelivertable(Boolean)`

- `Void _OnPlayerDataChanged(Object)`

- `Void _UpdatePlayerStatus()`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Boolean <>xLuaBaseProxy_OnRoomClicked()`

- `Boolean <>xLuaBaseProxy_get_isHarvestable()`

- `GameObject <>xLuaBaseProxy_get_harvestIcon()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BTradingRoom : BOutputRoom
{
	private const Single NOTIFY_INTERVAL; // 0x0
	private GameObject _iconOrders; // 0xf8
	private TradingInfoViewStruct m_tradingInfo; // 0x100
	private Boolean m_isDelivertable; // 0x180
	private static DelegateBridge __Hotfix0_get_isWorking; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_ListenerToPlayerData; // 0x10
	private static DelegateBridge __Hotfix0_OnRoomClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnProcess; // 0x20
	private static DelegateBridge __Hotfix0__DoBatchOrderToast; // 0x28
	private static DelegateBridge __Hotfix0_get_isHarvestable; // 0x30
	private static DelegateBridge __Hotfix0_get_harvestIcon; // 0x38
	private static DelegateBridge __Hotfix0__SetIsDelivertable; // 0x40
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x48
	private static DelegateBridge __Hotfix0__UpdatePlayerStatus; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected override Boolean isWorking { get; }
	protected override Boolean isHarvestable { get; }
	protected override GameObject harvestIcon { get; }

	// RVA: 0x3d1f318 VA: 0x7596337318
	protected override Boolean get_isWorking() { }
	// RVA: 0x3d1f380 VA: 0x7596337380
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d1f700 VA: 0x7596337700
	public override Action`1 ListenerToPlayerData() { }
	// RVA: 0x3d1f7b4 VA: 0x75963377b4
	protected override Boolean OnRoomClicked() { }
	// RVA: 0x3d1f948 VA: 0x7596337948
	private Void _OnProcess(BuildingDeliveryBatchOrderResponse resp) { }
	// RVA: 0x3d1febc VA: 0x7596337ebc
	private Void _DoBatchOrderToast(ListDict`2 otherCountDict) { }
	// RVA: 0x3d200e8 VA: 0x75963380e8
	protected override Boolean get_isHarvestable() { }
	// RVA: 0x3d20150 VA: 0x7596338150
	protected override GameObject get_harvestIcon() { }
	// RVA: 0x3d201b8 VA: 0x75963381b8
	private Void _SetIsDelivertable(Boolean value) { }
	// RVA: 0x3d20254 VA: 0x7596338254
	private Void _OnPlayerDataChanged(Object arg) { }
	// RVA: 0x3d1f414 VA: 0x7596337414
	private Void _UpdatePlayerStatus() { }
	// RVA: 0x3d20314 VA: 0x7596338314
	public Void .ctor() { }
	// RVA: 0x3d203c8 VA: 0x75963383c8
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d203cc VA: 0x75963383cc
	private Action`1 <>xLuaBaseProxy_ListenerToPlayerData() { }
	// RVA: 0x3d203d4 VA: 0x75963383d4
	private Boolean <>xLuaBaseProxy_OnRoomClicked() { }
	// RVA: 0x3d203dc VA: 0x75963383dc
	private Boolean <>xLuaBaseProxy_get_isHarvestable() { }
	// RVA: 0x3d203e0 VA: 0x75963383e0
	private GameObject <>xLuaBaseProxy_get_harvestIcon() { }
}
```