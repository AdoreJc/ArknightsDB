# BuildingArchitecture

**Namespace:** `Torappu.Building.BP`


## Methods

- `Void OnAdded(BlueprintMode)`

- `Void OnRemoved(BlueprintMode)`

- `Void OnRoomSelect(RoomSlotModel)`

- `Void _RoomRequestClean(RoomSlotModel)`

- `Void _RoomRequestBuild(RoomSlotModel)`

- `Void _RoomRequestDetail(RoomSlotModel)`

- `Void _RoomRequestUpgradeComplete(RoomSlotModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BuildingArchitecture : MonoBehaviour, IPlugin
{


	// RVA: 0x3d11ca8 VA: 0x7596329ca8
	public Void OnAdded(BlueprintMode mode) { }
	// RVA: 0x3d11d80 VA: 0x7596329d80
	public Void OnRemoved(BlueprintMode mode) { }
	// RVA: 0x3d11e58 VA: 0x7596329e58
	public Void OnRoomSelect(RoomSlotModel room) { }
	// RVA: 0x3d11f50 VA: 0x7596329f50
	private Void _RoomRequestClean(RoomSlotModel room) { }
	// RVA: 0x3d122f4 VA: 0x759632a2f4
	private Void _RoomRequestBuild(RoomSlotModel room) { }
	// RVA: 0x3d123ac VA: 0x759632a3ac
	private Void _RoomRequestDetail(RoomSlotModel room) { }
	// RVA: 0x3d11ee0 VA: 0x7596329ee0
	private Void _RoomRequestUpgradeComplete(RoomSlotModel room) { }
	// RVA: 0x3d12468 VA: 0x759632a468
	public Void .ctor() { }
}
```