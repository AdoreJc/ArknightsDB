# CommonBasicRoomViewModel

**Namespace:** `Torappu.Building.UI`


## Fields

- `BasicRoomInfoModel m_basicModel`


## Methods

- `BasicRoomInfoModel GetRoomInfo()`

- `Void LoadData(RoomSlotModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class CommonBasicRoomViewModel : IBasicRoomModel, IHotfixable
{
	private BasicRoomInfoModel m_basicModel; // 0x10
	private static DelegateBridge __Hotfix0_GetRoomInfo; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3d339c0 VA: 0x759634b9c0
	public BasicRoomInfoModel GetRoomInfo() { }
	// RVA: 0x3d36498 VA: 0x759634e498
	public Void LoadData(RoomSlotModel slotModel) { }
	// RVA: 0x3d3659c VA: 0x759634e59c
	public Void .ctor() { }
}
```