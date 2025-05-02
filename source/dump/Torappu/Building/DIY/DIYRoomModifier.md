# DIYRoomModifier

**Namespace:** `Torappu.Building.DIY`


## Fields

- `IListener m_listener`

- `IDIYRoomModifierData m_data`

- `Int32 m_roomIndex`


## Properties

- `IDIYRoomModifierData data`

- `Int32 roomIndex`


## Methods

- `Void SetListener(IListener)`

- `IDIYRoomModifierData get_data()`

- `Int32 get_roomIndex()`

- `Void set_roomIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYRoomModifier
{
	private IListener m_listener; // 0x10
	private IDIYRoomModifierData m_data; // 0x18
	private Int32 m_roomIndex; // 0x20

	public IDIYRoomModifierData data { get; }
	public Int32 roomIndex { get; set; }

	// RVA: 0x37cab00 VA: 0x7595de2b00
	public Void SetListener(IListener listener) { }
	// RVA: 0x37cab08 VA: 0x7595de2b08
	public IDIYRoomModifierData get_data() { }
	// RVA: 0x37cab10 VA: 0x7595de2b10
	public Int32 get_roomIndex() { }
	// RVA: 0x37c8a28 VA: 0x7595de0a28
	public Void set_roomIndex(Int32 value) { }
	// RVA: 0x37c89f8 VA: 0x7595de09f8
	public Void .ctor(IDIYRoomModifierData data) { }
}
```