# DIYRoomModifierData

**Namespace:** ` `


## Fields

- `String _id`

- `String _displayName`

- `Int32 _comfort`

- `Int32 _rarity`

- `String _themeId`

- `String _groupId`

- `DIYRoomPart _part`

- `Mesh _mesh`

- `Material _material`

- `Sprite _icon`

- `String _desc`

- `String _usage`

- `String _furnitureType`

- `String _furnitureSubType`


## Properties

- `String id`

- `String displayName`

- `Int32 comfort`

- `Int32 rarity`

- `Int32 sortId`

- `Int32 quantity`

- `Int32 enableRoomType`

- `String themeId`

- `String groupId`

- `DIYRoomPart part`

- `Mesh mesh`

- `Material material`

- `Sprite icon`

- `String desc`

- `String usage`

- `FurnitureType furniType`

- `FurnitureSubType subType`


## Methods

- `String get_id()`

- `String get_displayName()`

- `Int32 get_comfort()`

- `Int32 get_rarity()`

- `Int32 get_sortId()`

- `Int32 get_quantity()`

- `Int32 get_enableRoomType()`

- `String get_themeId()`

- `String get_groupId()`

- `DIYRoomPart get_part()`

- `Mesh get_mesh()`

- `Material get_material()`

- `Sprite get_icon()`

- `String get_desc()`

- `String get_usage()`

- `FurnitureType get_furniType()`

- `FurnitureSubType get_subType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DIYRoomModifierData : IDIYRoomModifierData, IDIYItem, IHotfixable
{
	private String _id; // 0x10
	private String _displayName; // 0x18
	private Int32 _comfort; // 0x20
	private Int32 _rarity; // 0x24
	private String _themeId; // 0x28
	private String _groupId; // 0x30
	private DIYRoomPart _part; // 0x38
	private Mesh _mesh; // 0x40
	private Material _material; // 0x48
	private Sprite _icon; // 0x50
	private String _desc; // 0x58
	private String _usage; // 0x60
	private String _furnitureType; // 0x68
	private String _furnitureSubType; // 0x70
	private static DelegateBridge __Hotfix0_get_id; // 0x0
	private static DelegateBridge __Hotfix0_get_displayName; // 0x8
	private static DelegateBridge __Hotfix0_get_comfort; // 0x10
	private static DelegateBridge __Hotfix0_get_rarity; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_get_quantity; // 0x28
	private static DelegateBridge __Hotfix0_get_enableRoomType; // 0x30
	private static DelegateBridge __Hotfix0_get_themeId; // 0x38
	private static DelegateBridge __Hotfix0_get_groupId; // 0x40
	private static DelegateBridge __Hotfix0_get_part; // 0x48
	private static DelegateBridge __Hotfix0_get_mesh; // 0x50
	private static DelegateBridge __Hotfix0_get_material; // 0x58
	private static DelegateBridge __Hotfix0_get_icon; // 0x60
	private static DelegateBridge __Hotfix0_get_desc; // 0x68
	private static DelegateBridge __Hotfix0_get_usage; // 0x70
	private static DelegateBridge __Hotfix0_get_furniType; // 0x78
	private static DelegateBridge __Hotfix0_get_subType; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public String id { get; }
	public String displayName { get; }
	public Int32 comfort { get; }
	public Int32 rarity { get; }
	public Int32 sortId { get; }
	public Int32 quantity { get; }
	public Int32 enableRoomType { get; }
	public String themeId { get; }
	public String groupId { get; }
	public DIYRoomPart part { get; }
	public Mesh mesh { get; }
	public Material material { get; }
	public Sprite icon { get; }
	public String desc { get; }
	public String usage { get; }
	public FurnitureType furniType { get; }
	public FurnitureSubType subType { get; }

	// RVA: 0x37f44f8 VA: 0x7595e0c4f8
	public String get_id() { }
	// RVA: 0x37f4560 VA: 0x7595e0c560
	public String get_displayName() { }
	// RVA: 0x37f45c8 VA: 0x7595e0c5c8
	public Int32 get_comfort() { }
	// RVA: 0x37f4630 VA: 0x7595e0c630
	public Int32 get_rarity() { }
	// RVA: 0x37f4698 VA: 0x7595e0c698
	public Int32 get_sortId() { }
	// RVA: 0x37f46fc VA: 0x7595e0c6fc
	public Int32 get_quantity() { }
	// RVA: 0x37f4760 VA: 0x7595e0c760
	public Int32 get_enableRoomType() { }
	// RVA: 0x37f47c8 VA: 0x7595e0c7c8
	public String get_themeId() { }
	// RVA: 0x37f4830 VA: 0x7595e0c830
	public String get_groupId() { }
	// RVA: 0x37f4898 VA: 0x7595e0c898
	public DIYRoomPart get_part() { }
	// RVA: 0x37f4900 VA: 0x7595e0c900
	public Mesh get_mesh() { }
	// RVA: 0x37f4968 VA: 0x7595e0c968
	public Material get_material() { }
	// RVA: 0x37f49d0 VA: 0x7595e0c9d0
	public Sprite get_icon() { }
	// RVA: 0x37f4a38 VA: 0x7595e0ca38
	public String get_desc() { }
	// RVA: 0x37f4aa0 VA: 0x7595e0caa0
	public String get_usage() { }
	// RVA: 0x37f4b08 VA: 0x7595e0cb08
	public FurnitureType get_furniType() { }
	// RVA: 0x37f4c34 VA: 0x7595e0cc34
	public FurnitureSubType get_subType() { }
	// RVA: 0x37f4d60 VA: 0x7595e0cd60
	public Void .ctor() { }
}
```