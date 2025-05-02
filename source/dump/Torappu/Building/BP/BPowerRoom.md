# BPowerRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `Tweener m_progressTween`


## Methods

- `Void OnEnable()`

- `Void OnDisable()`

- `Void <OnInit>b__2_1(Single)`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnRoomDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BPowerRoom : BOutputRoom
{
	private const Single TWEEN_DURATION; // 0x0
	private Tweener m_progressTween; // 0xf8
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRoomDestroy; // 0x8
	private static DelegateBridge __Hotfix0_get_isWorking; // 0x10
	private static DelegateBridge __Hotfix0_OnEnable; // 0x18
	private static DelegateBridge __Hotfix0_OnDisable; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override Boolean isWorking { get; }

	// RVA: 0x3d1daf4 VA: 0x7596335af4
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d1ddb0 VA: 0x7596335db0
	protected override Void OnRoomDestroy() { }
	// RVA: 0x3d1de50 VA: 0x7596335e50
	protected override Boolean get_isWorking() { }
	// RVA: 0x3d1deb8 VA: 0x7596335eb8
	private Void OnEnable() { }
	// RVA: 0x3d1df58 VA: 0x7596335f58
	private Void OnDisable() { }
	// RVA: 0x3d1dff8 VA: 0x7596335ff8
	public Void .ctor() { }
	// RVA: 0x3d1e064 VA: 0x7596336064
	private Void <OnInit>b__2_1(Single val) { }
	// RVA: 0x3d1e068 VA: 0x7596336068
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d1e06c VA: 0x759633606c
	private Void <>xLuaBaseProxy_OnRoomDestroy() { }
}
```