# VElevatorRoom

**Namespace:** `Torappu.Building.Vault`


## Fields

- `GameObject _elevatorObj`

- `GameObject _shellObj`

- `Material _topMaterial`

- `Material _normalMaterial`

- `LocationType m_locationType`

- `ElevatorObj m_elevatorObj`


## Properties

- `ElevatorObj elevatorObj`


## Methods

- `ElevatorObj get_elevatorObj()`

- `LocationType _GetElevatorType()`

- `Void _RefreshGraphic()`

- `Void <>xLuaBaseProxy_Init(VRoomSlot, RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VElevatorRoom : VRoom
{
	private ObjectShowOrNot[] _objectsShowOrNot; // 0x80
	private GameObject _elevatorObj; // 0x88
	private GameObject _shellObj; // 0x90
	private Material _topMaterial; // 0x98
	private Material _normalMaterial; // 0xa0
	private LocationType m_locationType; // 0xa8
	private ElevatorObj m_elevatorObj; // 0xb0
	private static DelegateBridge __Hotfix0_get_elevatorObj; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__GetElevatorType; // 0x10
	private static DelegateBridge __Hotfix0__RefreshGraphic; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public ElevatorObj elevatorObj { get; }

	// RVA: 0x3cefdd0 VA: 0x7596307dd0
	public ElevatorObj get_elevatorObj() { }
	// RVA: 0x3cefe34 VA: 0x7596307e34
	public override Void Init(VRoomSlot slot, RoomSlotModel model) { }
	// RVA: 0x3cf0074 VA: 0x7596308074
	private LocationType _GetElevatorType() { }
	// RVA: 0x3cf03e0 VA: 0x75963083e0
	private Void _RefreshGraphic() { }
	// RVA: 0x3cf05d4 VA: 0x75963085d4
	public override Void OnEnter() { }
	// RVA: 0x3cf07bc VA: 0x75963087bc
	public Void .ctor() { }
	// RVA: 0x3cf0a38 VA: 0x7596308a38
	private Void <>xLuaBaseProxy_Init(VRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3cf0a3c VA: 0x7596308a3c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```