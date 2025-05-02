# BPrivateRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `SimpleLayoutContent _panelLevel`

- `Text _textCharNum`

- `Image _imgChar`

- `GameObject _panelChar`

- `Text _textState`

- `BRoomLevelAdapter m_levelAdapter`


## Methods

- `Void _UpdateContent(RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnContentChanged(RoomSlotModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BPrivateRoom : BCustomRoom
{
	private SimpleLayoutContent _panelLevel; // 0x58
	private Text _textCharNum; // 0x60
	private Image _imgChar; // 0x68
	private GameObject _panelChar; // 0x70
	private Text _textState; // 0x78
	private BRoomLevelAdapter m_levelAdapter; // 0x80
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnContentChanged; // 0x8
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d1e0f0 VA: 0x75963360f0
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d1e464 VA: 0x7596336464
	protected override Void OnContentChanged(RoomSlotModel slotModel) { }
	// RVA: 0x3d1e1e0 VA: 0x75963361e0
	private Void _UpdateContent(RoomSlotModel slotModel) { }
	// RVA: 0x3d1e4f4 VA: 0x75963364f4
	public Void .ctor() { }
	// RVA: 0x3d1e564 VA: 0x7596336564
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d1e56c VA: 0x759633656c
	private Void <>xLuaBaseProxy_OnContentChanged(RoomSlotModel P0) { }
}
```