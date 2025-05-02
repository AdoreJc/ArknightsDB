# BManufactureRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `GameObject _iconProduct`

- `CountDownTask m_countDown`

- `ManufactInfoViewModel m_manufactModel`

- `Boolean m_isHarvestable`


## Methods

- `Void _SetIsHarvestable(Boolean)`

- `Void _OnPlayerDataChanged(Object)`

- `Void Update()`

- `Void _UpdatePlayerData()`

- `Void _UpdateManufactStatus()`

- `Void <_UpdateManufactStatus>b__18_0(Boolean, ManufactSnapshot)`

- `GameObject <>xLuaBaseProxy_get_harvestIcon()`

- `Void <>xLuaBaseProxy_TriggerSettleEffect(AsyncSettleInfo, Action`1)`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Boolean <>xLuaBaseProxy_OnRoomClicked()`

- `Boolean <>xLuaBaseProxy_get_isHarvestable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BManufactureRoom : BOutputRoom
{
	private GameObject _iconProduct; // 0xf8
	private CountDownTask m_countDown; // 0x100
	private ManufactInfoViewModel m_manufactModel; // 0x108
	private Boolean m_isHarvestable; // 0x110
	private static DelegateBridge __Hotfix0_get_harvestIcon; // 0x0
	private static DelegateBridge __Hotfix0_TriggerSettleEffect; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_ListenerToPlayerData; // 0x18
	private static DelegateBridge __Hotfix0_OnRoomClicked; // 0x20
	private static DelegateBridge __Hotfix0_get_isWorking; // 0x28
	private static DelegateBridge __Hotfix0_get_isHarvestable; // 0x30
	private static DelegateBridge __Hotfix0__SetIsHarvestable; // 0x38
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x50
	private static DelegateBridge __Hotfix0__UpdateManufactStatus; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	protected override GameObject harvestIcon { get; }
	protected override Boolean isWorking { get; }
	protected override Boolean isHarvestable { get; }

	// RVA: 0x3d1b330 VA: 0x7596333330
	protected override GameObject get_harvestIcon() { }
	// RVA: 0x3d1b398 VA: 0x7596333398
	protected override Void TriggerSettleEffect(AsyncSettleInfo settleInfo, Action`1 triggerFunc) { }
	// RVA: 0x3d1b4c0 VA: 0x75963334c0
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d1b6f4 VA: 0x75963336f4
	public override Action`1 ListenerToPlayerData() { }
	// RVA: 0x3d1b7a8 VA: 0x75963337a8
	protected override Boolean OnRoomClicked() { }
	// RVA: 0x3d1b8f4 VA: 0x75963338f4
	protected override Boolean get_isWorking() { }
	// RVA: 0x3d1b974 VA: 0x7596333974
	protected override Boolean get_isHarvestable() { }
	// RVA: 0x3d1b9dc VA: 0x75963339dc
	private Void _SetIsHarvestable(Boolean value) { }
	// RVA: 0x3d1ba7c VA: 0x7596333a7c
	private Void _OnPlayerDataChanged(Object _) { }
	// RVA: 0x3d1bb28 VA: 0x7596333b28
	private Void Update() { }
	// RVA: 0x3d1b558 VA: 0x7596333558
	private Void _UpdatePlayerData() { }
	// RVA: 0x3d1bba4 VA: 0x7596333ba4
	private Void _UpdateManufactStatus() { }
	// RVA: 0x3d1be40 VA: 0x7596333e40
	public Void .ctor() { }
	// RVA: 0x3d1bef0 VA: 0x7596333ef0
	private Void <_UpdateManufactStatus>b__18_0(Boolean shouldCountDown, ManufactSnapshot snapshotParam) { }
	// RVA: 0x3d1c000 VA: 0x7596334000
	private GameObject <>xLuaBaseProxy_get_harvestIcon() { }
	// RVA: 0x3d1c008 VA: 0x7596334008
	private Void <>xLuaBaseProxy_TriggerSettleEffect(AsyncSettleInfo P0, Action`1 P1) { }
	// RVA: 0x3d1c038 VA: 0x7596334038
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d1c040 VA: 0x7596334040
	private Action`1 <>xLuaBaseProxy_ListenerToPlayerData() { }
	// RVA: 0x3d1c044 VA: 0x7596334044
	private Boolean <>xLuaBaseProxy_OnRoomClicked() { }
	// RVA: 0x3d1c048 VA: 0x7596334048
	private Boolean <>xLuaBaseProxy_get_isHarvestable() { }
}
```