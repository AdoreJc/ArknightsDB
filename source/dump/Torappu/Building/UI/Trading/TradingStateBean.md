# TradingStateBean

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `TRoomGroupViewProperty roomsProp`

- `TRoomViewProperty selectedRoomProp`

- `TOrderSlotGroupViewProperty orderSlotProp`


## Methods

- `Void SetSelectedRoom(String, Boolean)`

- `Void InitData()`

- `Boolean IsValidNextOrder(Int64)`

- `Void UpdateData()`

- `Boolean _CheckTabTrackPoint(TradingInfoViewStruct)`

- `Void _UpdateOrderGroupProperty(TRoomViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class TradingStateBean : IStateBean, IHotfixable
{
	public TRoomGroupViewProperty roomsProp; // 0x10
	public TRoomViewProperty selectedRoomProp; // 0x18
	public TOrderSlotGroupViewProperty orderSlotProp; // 0x20
	private static DelegateBridge __Hotfix0_SetSelectedRoom; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_IsValidNextOrder; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18
	private static DelegateBridge __Hotfix0__CheckTabTrackPoint; // 0x20
	private static DelegateBridge __Hotfix0__UpdateOrderGroupProperty; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3d7ebe8 VA: 0x7596396be8
	public Void SetSelectedRoom(String slotId, Boolean forceUpdate) { }
	// RVA: 0x3d7e6e0 VA: 0x75963966e0
	public Void InitData() { }
	// RVA: 0x3d80c20 VA: 0x7596398c20
	public Boolean IsValidNextOrder(Int64 orderInstId) { }
	// RVA: 0x3d7ee68 VA: 0x7596396e68
	public Void UpdateData() { }
	// RVA: 0x3d81d90 VA: 0x7596399d90
	private Boolean _CheckTabTrackPoint(TradingInfoViewStruct tradingInfo) { }
	// RVA: 0x3d81b00 VA: 0x7596399b00
	private Void _UpdateOrderGroupProperty(TRoomViewModel selectedRoom) { }
	// RVA: 0x3d8050c VA: 0x759639850c
	public Void .ctor() { }
}
```