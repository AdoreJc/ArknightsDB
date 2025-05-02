# VPUIWrapper

**Namespace:** ` `


## Fields

- `VUISystem m_closure`

- `RoomSlotModel m_slotModel`

- `VPUIPanel m_panel`


## Methods

- `Void OnRegister(RoomSlotModel)`

- `Void OnContentChange(RoomSlotModel)`

- `Void OnPostLayoutContentChanged()`

- `Void OnLayoutChange()`

- `Void Clear()`

- `Void _UpdateRoomUI()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class VPUIWrapper : IListener
{
	private VUISystem m_closure; // 0x10
	private RoomSlotModel m_slotModel; // 0x18
	private VPUIPanel m_panel; // 0x20


	// RVA: 0x3d0c900 VA: 0x7596324900
	public Void .ctor(RoomSlotModel slotModel, VUISystem closure) { }
	// RVA: 0x3d0d09c VA: 0x759632509c
	public Void OnRegister(RoomSlotModel model) { }
	// RVA: 0x3d0d20c VA: 0x759632520c
	public Void OnContentChange(RoomSlotModel model) { }
	// RVA: 0x3d0d210 VA: 0x7596325210
	public Void OnPostLayoutContentChanged() { }
	// RVA: 0x3d0c7d4 VA: 0x75963247d4
	public Void OnLayoutChange() { }
	// RVA: 0x3d0c85c VA: 0x759632485c
	public Void Clear() { }
	// RVA: 0x3d0d0a0 VA: 0x75963250a0
	private Void _UpdateRoomUI() { }
}
```