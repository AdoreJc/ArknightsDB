# BDormRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `SimpleLayoutContent _panelLevel`

- `Text _textCharNum`

- `Text _textCharLimit`

- `Text _textState`

- `BRoomLevelAdapter m_levelAdapter`


## Methods

- `Void _OnPlayerDataChanged(Object)`

- `Void _UpdateContent(RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnInit(BRoomSlot, RoomSlotModel)`

- `Void <>xLuaBaseProxy_OnContentChanged(RoomSlotModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BDormRoom : BCustomRoom
{
	private SimpleLayoutContent _panelLevel; // 0x58
	private Text _textCharNum; // 0x60
	private Text _textCharLimit; // 0x68
	private Text _textState; // 0x70
	private BRoomLevelAdapter m_levelAdapter; // 0x78
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_ListenerToPlayerData; // 0x8
	private static DelegateBridge __Hotfix0_OnContentChanged; // 0x10
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x18
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3d19c70 VA: 0x7596331c70
	protected override Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d19fa8 VA: 0x7596331fa8
	public override Action`1 ListenerToPlayerData() { }
	// RVA: 0x3d1a05c VA: 0x759633205c
	protected override Void OnContentChanged(RoomSlotModel slotModel) { }
	// RVA: 0x3d1a0e8 VA: 0x75963320e8
	private Void _OnPlayerDataChanged(Object _) { }
	// RVA: 0x3d19d60 VA: 0x7596331d60
	private Void _UpdateContent(RoomSlotModel slotModel) { }
	// RVA: 0x3d1a174 VA: 0x7596332174
	public Void .ctor() { }
	// RVA: 0x3d1a1e0 VA: 0x75963321e0
	private Void <>xLuaBaseProxy_OnInit(BRoomSlot P0, RoomSlotModel P1) { }
	// RVA: 0x3d1a1e4 VA: 0x75963321e4
	private Action`1 <>xLuaBaseProxy_ListenerToPlayerData() { }
	// RVA: 0x3d1a1e8 VA: 0x75963321e8
	private Void <>xLuaBaseProxy_OnContentChanged(RoomSlotModel P0) { }
}
```