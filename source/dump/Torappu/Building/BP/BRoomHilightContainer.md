# BRoomHilightContainer

**Namespace:** `Torappu.Building.BP`


## Fields

- `RectTransform m_rectTrans`

- `WrapContext m_wrapContext`

- `String <slotId>k__BackingField`


## Properties

- `RectTransform rectTrans`

- `String slotId`


## Methods

- `RectTransform get_rectTrans()`

- `String get_slotId()`

- `Void set_slotId(String)`

- `Boolean UnwrapBRoomSlot(SafeParentComponent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BRoomHilightContainer : MonoBehaviour
{
	private RectTransform m_rectTrans; // 0x18
	private WrapContext m_wrapContext; // 0x20
	private String <slotId>k__BackingField; // 0x58

	protected RectTransform rectTrans { get; }
	public String slotId { get; set; }

	// RVA: 0x3d21630 VA: 0x7596339630
	protected RectTransform get_rectTrans() { }
	// RVA: 0x3d216d8 VA: 0x75963396d8
	public String get_slotId() { }
	// RVA: 0x3d216e0 VA: 0x75963396e0
	private Void set_slotId(String value) { }
	// RVA: 0x3d216e8 VA: 0x75963396e8
	public static BRoomHilightContainer WrapBRoomSlot(SafeParentComponent targetRoomContainer, BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d21c24 VA: 0x7596339c24
	protected virtual Void OnRoomSlotWrapped(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d21c28 VA: 0x7596339c28
	public Boolean UnwrapBRoomSlot(SafeParentComponent targetRoomContainer) { }
	// RVA: 0x3d21e00 VA: 0x7596339e00
	public Void .ctor() { }
}
```