# FurnitureQuickSetupItemAdapter

**Namespace:** ` `


## Fields

- `ThemeQuickSetupItem m_item`

- `IDIYItem m_diyItem`


## Properties

- `IDIYItem diyItem`

- `Int32 posX`

- `Int32 posY`

- `Int32 dir`


## Methods

- `IDIYItem get_diyItem()`

- `Int32 get_posX()`

- `Int32 get_posY()`

- `Int32 get_dir()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FurnitureQuickSetupItemAdapter : IFurnitureQuickSetupItem
{
	private ThemeQuickSetupItem m_item; // 0x10
	private IDIYItem m_diyItem; // 0x18

	public IDIYItem diyItem { get; }
	public Int32 posX { get; }
	public Int32 posY { get; }
	public Int32 dir { get; }

	// RVA: 0x37cf918 VA: 0x7595de7918
	public Void .ctor(ThemeQuickSetupItem item, IFurnitureDataProvider furnitureDataProvider, IDIYRoomModifierDataProvider modifierDataProvider) { }
	// RVA: 0x37d03c0 VA: 0x7595de83c0
	public IDIYItem get_diyItem() { }
	// RVA: 0x37d03c8 VA: 0x7595de83c8
	public Int32 get_posX() { }
	// RVA: 0x37d03e4 VA: 0x7595de83e4
	public Int32 get_posY() { }
	// RVA: 0x37d0400 VA: 0x7595de8400
	public Int32 get_dir() { }
}
```