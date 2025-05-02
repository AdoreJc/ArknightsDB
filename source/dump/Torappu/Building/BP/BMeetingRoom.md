# BMeetingRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `GameObject _clueHintMark`

- `GameObject _messageBoardMark`

- `BuildingMeetingSession m_session`


## Methods

- `Void _UpdateClueHintMark(Boolean)`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnActiveArchitecture(Boolean, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BMeetingRoom : BFunctionRoom
{
	private GameObject _clueHintMark; // 0x88
	private GameObject _messageBoardMark; // 0x90
	private BuildingMeetingSession m_session; // 0x98
	private static DelegateBridge __Hotfix0__UpdateClueHintMark; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnActiveArchitecture; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d1c050 VA: 0x7596334050
	private Void _UpdateClueHintMark(Boolean architecture) { }
	// RVA: 0x3d1c17c VA: 0x759633417c
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d1c218 VA: 0x7596334218
	protected override Void OnActiveArchitecture(Boolean active, Func`2 validPred) { }
	// RVA: 0x3d1c2b8 VA: 0x75963342b8
	public Void .ctor() { }
	// RVA: 0x3d1c328 VA: 0x7596334328
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d1c330 VA: 0x7596334330
	private Void <>xLuaBaseProxy_OnActiveArchitecture(Boolean P0, Func`2 P1) { }
}
```