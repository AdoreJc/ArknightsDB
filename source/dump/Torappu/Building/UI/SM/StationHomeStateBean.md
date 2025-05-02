# StationHomeStateBean

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `StationManageViewProp stationManageProp`

- `StationRoomStructModel m_selectedRoom`


## Methods

- `Void InitData(BuildingModel)`

- `Void UpdateData(BuildingModel)`

- `Void UpdateSelectedRoom(BuildingModel, StationRoomStructModel)`

- `Void UpdateAnimRoom(String)`

- `Void SwitchWorkDormMode()`

- `Int32 UpdateEditLockStatus(BuildingModel, String, Int32)`

- `Void SwitchEditLockMode(BuildingModel, Boolean)`

- `Void ClearAllEditLockModeSelected(BuildingModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class StationHomeStateBean : IStateBean, IHotfixable
{
	public StationManageViewProp stationManageProp; // 0x10
	private StationRoomStructModel m_selectedRoom; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateSelectedRoom; // 0x10
	private static DelegateBridge __Hotfix0_UpdateAnimRoom; // 0x18
	private static DelegateBridge __Hotfix0_SwitchWorkDormMode; // 0x20
	private static DelegateBridge __Hotfix0_UpdateEditLockStatus; // 0x28
	private static DelegateBridge __Hotfix0_SwitchEditLockMode; // 0x30
	private static DelegateBridge __Hotfix0_ClearAllEditLockModeSelected; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3da221c VA: 0x75963ba21c
	public Void InitData(BuildingModel model) { }
	// RVA: 0x3da2458 VA: 0x75963ba458
	public Void UpdateData(BuildingModel model) { }
	// RVA: 0x3da26ac VA: 0x75963ba6ac
	public Void UpdateSelectedRoom(BuildingModel model, StationRoomStructModel room) { }
	// RVA: 0x3da28bc VA: 0x75963ba8bc
	public Void UpdateAnimRoom(String slotId) { }
	// RVA: 0x3da2ad8 VA: 0x75963baad8
	public Void SwitchWorkDormMode() { }
	// RVA: 0x3da2c0c VA: 0x75963bac0c
	public Int32 UpdateEditLockStatus(BuildingModel model, String slotId, Int32 index) { }
	// RVA: 0x3da2e40 VA: 0x75963bae40
	public Void SwitchEditLockMode(BuildingModel model, Boolean isEnter) { }
	// RVA: 0x3da3334 VA: 0x75963bb334
	public Void ClearAllEditLockModeSelected(BuildingModel model) { }
	// RVA: 0x3da35f4 VA: 0x75963bb5f4
	public Void .ctor() { }
}
```