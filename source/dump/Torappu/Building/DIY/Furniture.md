# Furniture

**Namespace:** `Torappu.Building.DIY`


## Fields

- `IListener m_listener`

- `IFurnitureData m_data`

- `Int32 m_pos0`

- `Int32 m_pos1`

- `Int32 m_dir`

- `Int32 m_roomIndex`


## Properties

- `IListener listener`

- `IFurnitureData data`

- `Int32 pos0`

- `Int32 pos1`

- `Int32 dir`

- `Boolean swapXZ`

- `Int32 roomIndex`

- `Boolean isInteractive`

- `Boolean isMusicFurniture`


## Methods

- `IListener get_listener()`

- `Void SetListener(IListener)`

- `IFurnitureData get_data()`

- `Int32 get_pos0()`

- `Int32 get_pos1()`

- `Int32 get_dir()`

- `Boolean get_swapXZ()`

- `Int32 get_roomIndex()`

- `Boolean get_isInteractive()`

- `Boolean get_isMusicFurniture()`

- `Void SetPosition(Int32, Int32)`

- `Void SetRoomIndex(Int32)`

- `Void SetDirection(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class Furniture
{
	private IListener m_listener; // 0x10
	private IFurnitureData m_data; // 0x18
	private Int32 m_pos0; // 0x20
	private Int32 m_pos1; // 0x24
	private Int32 m_dir; // 0x28
	private Int32 m_roomIndex; // 0x2c

	public IListener listener { get; }
	public IFurnitureData data { get; }
	public Int32 pos0 { get; }
	public Int32 pos1 { get; }
	public Int32 dir { get; }
	public Boolean swapXZ { get; }
	public Int32 roomIndex { get; }
	public Boolean isInteractive { get; }
	public Boolean isMusicFurniture { get; }

	// RVA: 0x37cab94 VA: 0x7595de2b94
	public IListener get_listener() { }
	// RVA: 0x37cab9c VA: 0x7595de2b9c
	public Void SetListener(IListener listener) { }
	// RVA: 0x37caba4 VA: 0x7595de2ba4
	public IFurnitureData get_data() { }
	// RVA: 0x37cabac VA: 0x7595de2bac
	public Int32 get_pos0() { }
	// RVA: 0x37cabb4 VA: 0x7595de2bb4
	public Int32 get_pos1() { }
	// RVA: 0x37cabbc VA: 0x7595de2bbc
	public Int32 get_dir() { }
	// RVA: 0x37cabc4 VA: 0x7595de2bc4
	public Boolean get_swapXZ() { }
	// RVA: 0x37cabd8 VA: 0x7595de2bd8
	public Int32 get_roomIndex() { }
	// RVA: 0x37cabe0 VA: 0x7595de2be0
	public Boolean get_isInteractive() { }
	// RVA: 0x37cac90 VA: 0x7595de2c90
	public Boolean get_isMusicFurniture() { }
	// RVA: 0x37cad40 VA: 0x7595de2d40
	public Void .ctor(IFurnitureData data) { }
	// RVA: 0x37cad78 VA: 0x7595de2d78
	public Void SetPosition(Int32 pos0, Int32 pos1) { }
	// RVA: 0x37cae5c VA: 0x7595de2e5c
	public Void SetRoomIndex(Int32 index) { }
	// RVA: 0x37caf24 VA: 0x7595de2f24
	public Void SetDirection(Int32 dir) { }
}
```