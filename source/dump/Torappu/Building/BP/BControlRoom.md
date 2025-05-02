# BControlRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `Text _textLevel`

- `Text _textLevelShadow`

- `GameObject _panelFavorMax`


## Methods

- `Void _DoUpdateControlRoomContent(RoomSlotModel)`

- `Void _UpdateFavorMaxPanel(Object)`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnContentChanged(RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnRoomDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BControlRoom : BRoom
{
	private Text _textLevel; // 0x50
	private Text _textLevelShadow; // 0x58
	private GameObject _panelFavorMax; // 0x60
	private static DelegateBridge __Hotfix0__DoUpdateControlRoomContent; // 0x0
	private static DelegateBridge __Hotfix0__UpdateFavorMaxPanel; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnContentChanged; // 0x18
	private static DelegateBridge __Hotfix0_OnRoomDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3d194dc VA: 0x75963314dc
	private Void _DoUpdateControlRoomContent(RoomSlotModel slotModel) { }
	// RVA: 0x3d195f8 VA: 0x75963315f8
	private Void _UpdateFavorMaxPanel(Object arg) { }
	// RVA: 0x3d196c4 VA: 0x75963316c4
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d19854 VA: 0x7596331854
	protected override Void OnContentChanged(RoomSlotModel slotModel) { }
	// RVA: 0x3d198e0 VA: 0x75963318e0
	protected override Void OnRoomDestroy() { }
	// RVA: 0x3d19a40 VA: 0x7596331a40
	public Void .ctor() { }
	// RVA: 0x3d19aac VA: 0x7596331aac
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d19ab0 VA: 0x7596331ab0
	private Void <>xLuaBaseProxy_OnContentChanged(RoomSlotModel P0) { }
	// RVA: 0x3d19ab4 VA: 0x7596331ab4
	private Void <>xLuaBaseProxy_OnRoomDestroy() { }
}
```