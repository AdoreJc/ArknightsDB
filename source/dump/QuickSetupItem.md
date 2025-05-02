# QuickSetupItem

**Namespace:** ` `


## Fields

- `String _themeId`

- `String _furnitureId`

- `Int32 _posX`

- `Int32 _posY`

- `Int32 _dir`

- `IDIYItem m_diyItem`


## Properties

- `String themeId`

- `IDIYItem diyItem`

- `Int32 posX`

- `Int32 posY`

- `Int32 dir`


## Methods

- `Void Setup(IFurnitureDataProvider, IDIYRoomModifierDataProvider)`

- `String get_themeId()`

- `IDIYItem get_diyItem()`

- `Int32 get_posX()`

- `Int32 get_posY()`

- `Int32 get_dir()`

- `Boolean <Setup>b__6_0(IFurnitureData)`

- `Void <Setup>b__6_1(IFurnitureData)`

- `Boolean <Setup>b__6_2(IDIYRoomModifierData)`

- `Void <Setup>b__6_3(IDIYRoomModifierData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class QuickSetupItem : IFurnitureQuickSetupItem
{
	private String _themeId; // 0x10
	private String _furnitureId; // 0x18
	private Int32 _posX; // 0x20
	private Int32 _posY; // 0x24
	private Int32 _dir; // 0x28
	private IDIYItem m_diyItem; // 0x30

	public String themeId { get; }
	public IDIYItem diyItem { get; }
	public Int32 posX { get; }
	public Int32 posY { get; }
	public Int32 dir { get; }

	// RVA: 0x37f98a4 VA: 0x7595e118a4
	public Void Setup(IFurnitureDataProvider furnitureDB, IDIYRoomModifierDataProvider modifierDB) { }
	// RVA: 0x37fa578 VA: 0x7595e12578
	public String get_themeId() { }
	// RVA: 0x37fa580 VA: 0x7595e12580
	public IDIYItem get_diyItem() { }
	// RVA: 0x37fa588 VA: 0x7595e12588
	public Int32 get_posX() { }
	// RVA: 0x37fa590 VA: 0x7595e12590
	public Int32 get_posY() { }
	// RVA: 0x37fa598 VA: 0x7595e12598
	public Int32 get_dir() { }
	// RVA: 0x37fa5a0 VA: 0x7595e125a0
	public Void .ctor() { }
	// RVA: 0x37fa5a8 VA: 0x7595e125a8
	private Boolean <Setup>b__6_0(IFurnitureData x) { }
	// RVA: 0x37fa654 VA: 0x7595e12654
	private Void <Setup>b__6_1(IFurnitureData x) { }
	// RVA: 0x37fa65c VA: 0x7595e1265c
	private Boolean <Setup>b__6_2(IDIYRoomModifierData x) { }
	// RVA: 0x37fa708 VA: 0x7595e12708
	private Void <Setup>b__6_3(IDIYRoomModifierData x) { }
}
```