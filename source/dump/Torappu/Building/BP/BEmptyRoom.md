# BEmptyRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `GameObject _infoPanel`

- `Text _categoryLabel`


## Methods

- `String <>xLuaBaseProxy_get_roomName()`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnActiveArchitecture(Boolean, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BEmptyRoom : BRoom
{
	private GameObject _infoPanel; // 0x50
	private Text _categoryLabel; // 0x58
	private CategoryLabelMapEntry[] _categoryLabelMap; // 0x60
	private static DelegateBridge __Hotfix0_get_roomName; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnActiveArchitecture; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override String roomName { get; }

	// RVA: 0x3d1a478 VA: 0x7596332478
	protected override String get_roomName() { }
	// RVA: 0x3d1a504 VA: 0x7596332504
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d1a6b0 VA: 0x75963326b0
	protected override Void OnActiveArchitecture(Boolean active, Func`2 validPred) { }
	// RVA: 0x3d1a7dc VA: 0x75963327dc
	public Void .ctor() { }
	// RVA: 0x3d1a848 VA: 0x7596332848
	private String <>xLuaBaseProxy_get_roomName() { }
	// RVA: 0x3d1a84c VA: 0x759633284c
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d1a850 VA: 0x7596332850
	private Void <>xLuaBaseProxy_OnActiveArchitecture(Boolean P0, Func`2 P1) { }
}
```