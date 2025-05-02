# FurnitureData

**Namespace:** ` `


## Fields

- `String _id`

- `String _displayName`

- `Boolean _validOnRotate`

- `Boolean _enableRotate`

- `Int32 _dimX`

- `Int32 _dimY`

- `Int32 _dimZ`

- `Int32 _comfort`

- `Int32 _rarity`

- `String _themeId`

- `String _groupId`

- `FurnitureLocationType _locationType`

- `FurnitureInteractType _interactType`

- `String _musicId`

- `GameObject _prefab`

- `Sprite _icon`

- `String _desc`

- `String _usage`

- `String _furnitureType`

- `String _furnitureSubType`


## Properties

- `String id`

- `String displayName`

- `Int32 dimX`

- `Int32 dimY`

- `Int32 dimZ`

- `Int32 comfort`

- `Int32 rarity`

- `Int32 sortId`

- `Int32 quantity`

- `Int32 enableRoomType`

- `String themeId`

- `String groupId`

- `FurnitureLocationType locationType`

- `FurnitureInteractType interactType`

- `String musicId`

- `GameObject prefab`

- `Boolean validOnRotate`

- `Boolean enableRotate`

- `Sprite icon`

- `String desc`

- `String usage`

- `FurnitureType furniType`

- `FurnitureSubType subType`


## Methods

- `String get_id()`

- `String get_displayName()`

- `Int32 get_dimX()`

- `Int32 get_dimY()`

- `Int32 get_dimZ()`

- `Int32 get_comfort()`

- `Int32 get_rarity()`

- `Int32 get_sortId()`

- `Int32 get_quantity()`

- `Int32 get_enableRoomType()`

- `String get_themeId()`

- `String get_groupId()`

- `FurnitureLocationType get_locationType()`

- `FurnitureInteractType get_interactType()`

- `String get_musicId()`

- `GameObject get_prefab()`

- `Boolean get_validOnRotate()`

- `Boolean get_enableRotate()`

- `Sprite get_icon()`

- `String get_desc()`

- `String get_usage()`

- `FurnitureType get_furniType()`

- `FurnitureSubType get_subType()`

- `IDynamicAssetHandler LoadAsset(IDynamicAssetWrapper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FurnitureData : IFurnitureData, IDIYItem, IHotfixable
{
	private String _id; // 0x10
	private String _displayName; // 0x18
	private Boolean _validOnRotate; // 0x20
	private Boolean _enableRotate; // 0x21
	private Int32 _dimX; // 0x24
	private Int32 _dimY; // 0x28
	private Int32 _dimZ; // 0x2c
	private Int32 _comfort; // 0x30
	private Int32 _rarity; // 0x34
	private String _themeId; // 0x38
	private String _groupId; // 0x40
	private FurnitureLocationType _locationType; // 0x48
	private FurnitureInteractType _interactType; // 0x4c
	private String _musicId; // 0x50
	public GameObject _prefab; // 0x58
	private Sprite _icon; // 0x60
	private String _desc; // 0x68
	private String _usage; // 0x70
	private String _furnitureType; // 0x78
	private String _furnitureSubType; // 0x80
	private static DelegateBridge __Hotfix0_get_id; // 0x0
	private static DelegateBridge __Hotfix0_get_displayName; // 0x8
	private static DelegateBridge __Hotfix0_get_dimX; // 0x10
	private static DelegateBridge __Hotfix0_get_dimY; // 0x18
	private static DelegateBridge __Hotfix0_get_dimZ; // 0x20
	private static DelegateBridge __Hotfix0_get_comfort; // 0x28
	private static DelegateBridge __Hotfix0_get_rarity; // 0x30
	private static DelegateBridge __Hotfix0_get_sortId; // 0x38
	private static DelegateBridge __Hotfix0_get_quantity; // 0x40
	private static DelegateBridge __Hotfix0_get_enableRoomType; // 0x48
	private static DelegateBridge __Hotfix0_get_themeId; // 0x50
	private static DelegateBridge __Hotfix0_get_groupId; // 0x58
	private static DelegateBridge __Hotfix0_get_locationType; // 0x60
	private static DelegateBridge __Hotfix0_get_interactType; // 0x68
	private static DelegateBridge __Hotfix0_get_musicId; // 0x70
	private static DelegateBridge __Hotfix0_get_prefab; // 0x78
	private static DelegateBridge __Hotfix0_get_validOnRotate; // 0x80
	private static DelegateBridge __Hotfix0_get_enableRotate; // 0x88
	private static DelegateBridge __Hotfix0_get_icon; // 0x90
	private static DelegateBridge __Hotfix0_get_desc; // 0x98
	private static DelegateBridge __Hotfix0_get_usage; // 0xa0
	private static DelegateBridge __Hotfix0_get_furniType; // 0xa8
	private static DelegateBridge __Hotfix0_get_subType; // 0xb0
	private static DelegateBridge __Hotfix0_LoadAsset; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public String id { get; }
	public String displayName { get; }
	public Int32 dimX { get; }
	public Int32 dimY { get; }
	public Int32 dimZ { get; }
	public Int32 comfort { get; }
	public Int32 rarity { get; }
	public Int32 sortId { get; }
	public Int32 quantity { get; }
	public Int32 enableRoomType { get; }
	public String themeId { get; }
	public String groupId { get; }
	public FurnitureLocationType locationType { get; }
	public FurnitureInteractType interactType { get; }
	public String musicId { get; }
	public GameObject prefab { get; }
	public Boolean validOnRotate { get; }
	public Boolean enableRotate { get; }
	public Sprite icon { get; }
	public String desc { get; }
	public String usage { get; }
	public FurnitureType furniType { get; }
	public FurnitureSubType subType { get; }

	// RVA: 0x37f79b4 VA: 0x7595e0f9b4
	public String get_id() { }
	// RVA: 0x37f7a1c VA: 0x7595e0fa1c
	public String get_displayName() { }
	// RVA: 0x37f7a84 VA: 0x7595e0fa84
	public Int32 get_dimX() { }
	// RVA: 0x37f7aec VA: 0x7595e0faec
	public Int32 get_dimY() { }
	// RVA: 0x37f7b54 VA: 0x7595e0fb54
	public Int32 get_dimZ() { }
	// RVA: 0x37f7bbc VA: 0x7595e0fbbc
	public Int32 get_comfort() { }
	// RVA: 0x37f7c24 VA: 0x7595e0fc24
	public Int32 get_rarity() { }
	// RVA: 0x37f7c8c VA: 0x7595e0fc8c
	public Int32 get_sortId() { }
	// RVA: 0x37f7cf0 VA: 0x7595e0fcf0
	public Int32 get_quantity() { }
	// RVA: 0x37f7d54 VA: 0x7595e0fd54
	public Int32 get_enableRoomType() { }
	// RVA: 0x37f7dbc VA: 0x7595e0fdbc
	public String get_themeId() { }
	// RVA: 0x37f7e24 VA: 0x7595e0fe24
	public String get_groupId() { }
	// RVA: 0x37f7e8c VA: 0x7595e0fe8c
	public FurnitureLocationType get_locationType() { }
	// RVA: 0x37f7ef4 VA: 0x7595e0fef4
	public FurnitureInteractType get_interactType() { }
	// RVA: 0x37f7f5c VA: 0x7595e0ff5c
	public String get_musicId() { }
	// RVA: 0x37f7fc4 VA: 0x7595e0ffc4
	public GameObject get_prefab() { }
	// RVA: 0x37f802c VA: 0x7595e1002c
	public Boolean get_validOnRotate() { }
	// RVA: 0x37f8094 VA: 0x7595e10094
	public Boolean get_enableRotate() { }
	// RVA: 0x37f80fc VA: 0x7595e100fc
	public Sprite get_icon() { }
	// RVA: 0x37f8164 VA: 0x7595e10164
	public String get_desc() { }
	// RVA: 0x37f81cc VA: 0x7595e101cc
	public String get_usage() { }
	// RVA: 0x37f8234 VA: 0x7595e10234
	public FurnitureType get_furniType() { }
	// RVA: 0x37f8360 VA: 0x7595e10360
	public FurnitureSubType get_subType() { }
	// RVA: 0x37f848c VA: 0x7595e1048c
	public IDynamicAssetHandler LoadAsset(IDynamicAssetWrapper assetWrapper) { }
	// RVA: 0x37f8504 VA: 0x7595e10504
	public Void .ctor() { }
}
```