# DIYRoomInfo

**Namespace:** `Torappu.Building.DIY`


## Fields

- `IDIYRoomTemplate m_data`

- `Int32 m_index`


## Properties

- `IDIYRoomTemplate data`

- `Int32 index`


## Methods

- `IDIYRoomTemplate get_data()`

- `Int32 get_index()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYRoomInfo
{
	private IDIYRoomTemplate m_data; // 0x10
	private Int32 m_index; // 0x18

	public IDIYRoomTemplate data { get; }
	public Int32 index { get; }

	// RVA: 0x37cab48 VA: 0x7595de2b48
	public IDIYRoomTemplate get_data() { }
	// RVA: 0x37cab50 VA: 0x7595de2b50
	public Int32 get_index() { }
	// RVA: 0x37cab58 VA: 0x7595de2b58
	public Void .ctor(IDIYRoomTemplate template, Int32 index) { }
}
```