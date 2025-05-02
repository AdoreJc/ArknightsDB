# BShopRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `GameObject _iconProduct`

- `ShopInfoViewModel m_shopModel`

- `Boolean m_isHarvestable`


## Methods

- `Void _SetIsHarvestable(Boolean)`

- `Void _OnPlayerDataChanged(Object)`

- `Void Update()`

- `Void _UpdatePlayerData()`

- `Void _UpdateShopStatus()`

- `GameObject <>xLuaBaseProxy_get_harvestIcon()`

- `Void <>xLuaBaseProxy_TriggerSettleEffect(AsyncSettleInfo, Action`1)`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Boolean <>xLuaBaseProxy_OnRoomClicked()`

- `Boolean <>xLuaBaseProxy_get_isHarvestable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BShopRoom : BOutputRoom
{
	private GameObject _iconProduct; // 0xf8
	private CountDownTask[] m_countDowns; // 0x100
	private ShopStockSnapshot[] m_snapshots; // 0x108
	private ShopInfoViewModel m_shopModel; // 0x110
	private Boolean m_isHarvestable; // 0x118
	private static DelegateBridge __Hotfix0_get_harvestIcon; // 0x0
	private static DelegateBridge __Hotfix0_TriggerSettleEffect; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_ListenerToPlayerData; // 0x18
	private static DelegateBridge __Hotfix0_get_isWorking; // 0x20
	private static DelegateBridge __Hotfix0_OnRoomClicked; // 0x28
	private static DelegateBridge __Hotfix0_get_isHarvestable; // 0x30
	private static DelegateBridge __Hotfix0__SetIsHarvestable; // 0x38
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x50
	private static DelegateBridge __Hotfix0__UpdateShopStatus; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	protected override GameObject harvestIcon { get; }
	protected override Boolean isWorking { get; }
	protected override Boolean isHarvestable { get; }

	// RVA: 0x3d1e574 VA: 0x7596336574
	protected override GameObject get_harvestIcon() { }
	// RVA: 0x3d1e5dc VA: 0x75963365dc
	protected override Void TriggerSettleEffect(AsyncSettleInfo settleInfo, Action`1 triggerFunc) { }
	// RVA: 0x3d1e764 VA: 0x7596336764
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d1e99c VA: 0x759633699c
	public override Action`1 ListenerToPlayerData() { }
	// RVA: 0x3d1ea50 VA: 0x7596336a50
	protected override Boolean get_isWorking() { }
	// RVA: 0x3d1eb54 VA: 0x7596336b54
	protected override Boolean OnRoomClicked() { }
	// RVA: 0x3d1eca4 VA: 0x7596336ca4
	protected override Boolean get_isHarvestable() { }
	// RVA: 0x3d1ed0c VA: 0x7596336d0c
	private Void _SetIsHarvestable(Boolean value) { }
	// RVA: 0x3d1eda8 VA: 0x7596336da8
	private Void _OnPlayerDataChanged(Object _) { }
	// RVA: 0x3d1ee58 VA: 0x7596336e58
	private Void Update() { }
	// RVA: 0x3d1e7f8 VA: 0x75963367f8
	private Void _UpdatePlayerData() { }
	// RVA: 0x3d1ef28 VA: 0x7596336f28
	private Void _UpdateShopStatus() { }
	// RVA: 0x3d1f1b8 VA: 0x75963371b8
	public Void .ctor() { }
	// RVA: 0x3d1f2d0 VA: 0x75963372d0
	private GameObject <>xLuaBaseProxy_get_harvestIcon() { }
	// RVA: 0x3d1f2d4 VA: 0x75963372d4
	private Void <>xLuaBaseProxy_TriggerSettleEffect(AsyncSettleInfo P0, Action`1 P1) { }
	// RVA: 0x3d1f300 VA: 0x7596337300
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d1f304 VA: 0x7596337304
	private Action`1 <>xLuaBaseProxy_ListenerToPlayerData() { }
	// RVA: 0x3d1f30c VA: 0x759633730c
	private Boolean <>xLuaBaseProxy_OnRoomClicked() { }
	// RVA: 0x3d1f314 VA: 0x7596337314
	private Boolean <>xLuaBaseProxy_get_isHarvestable() { }
}
```