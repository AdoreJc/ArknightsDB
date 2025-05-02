# BHireRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `Text _textState`

- `PiecewiseProgressBar _progressBar`

- `PlayerBuildingHire m_hiringViewModel`

- `HiringSnapshot m_hireSnapshot`

- `CountDownTask m_countDown`


## Methods

- `Void _InitData(Object)`

- `Void Update()`

- `Void _OnCountDownTick(TickValue)`

- `Void _UpdateCountDownStatus()`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BHireRoom : BFunctionRoom
{
	private Text _textState; // 0x88
	private PiecewiseProgressBar _progressBar; // 0x90
	private PlayerBuildingHire m_hiringViewModel; // 0x98
	private HiringSnapshot m_hireSnapshot; // 0xa0
	private CountDownTask m_countDown; // 0xd0
	private static DelegateBridge __Hotfix0__InitData; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_ListenerToPlayerData; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__OnCountDownTick; // 0x20
	private static DelegateBridge __Hotfix0__UpdateCountDownStatus; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3d1ac20 VA: 0x7596332c20
	private Void _InitData(Object _object) { }
	// RVA: 0x3d1b034 VA: 0x7596333034
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d1b0cc VA: 0x75963330cc
	public override Action`1 ListenerToPlayerData() { }
	// RVA: 0x3d1b180 VA: 0x7596333180
	private Void Update() { }
	// RVA: 0x3d1b1fc VA: 0x75963331fc
	private Void _OnCountDownTick(TickValue tick) { }
	// RVA: 0x3d1adfc VA: 0x7596332dfc
	private Void _UpdateCountDownStatus() { }
	// RVA: 0x3d1b2bc VA: 0x75963332bc
	public Void .ctor() { }
	// RVA: 0x3d1b328 VA: 0x7596333328
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d1b32c VA: 0x759633332c
	private Action`1 <>xLuaBaseProxy_ListenerToPlayerData() { }
}
```