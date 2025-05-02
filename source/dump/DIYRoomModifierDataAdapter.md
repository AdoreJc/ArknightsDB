# DIYRoomModifierDataAdapter

**Namespace:** ` `


## Fields

- `FurnitureData m_buildingFurnitureData`

- `IFurnitureGroupData m_groupData`

- `CachedAssetLoader m_cachedAssetLoader`


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
private class DIYRoomModifierDataAdapter : IDIYRoomModifierData, IDIYItem, IHotfixable
{
	private FurnitureData m_buildingFurnitureData; // 0x10
	private IFurnitureGroupData m_groupData; // 0x18
	private CachedAssetLoader m_cachedAssetLoader; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_id; // 0x8
	private static DelegateBridge __Hotfix0_get_displayName; // 0x10
	private static DelegateBridge __Hotfix0_get_comfort; // 0x18
	private static DelegateBridge __Hotfix0_get_rarity; // 0x20
	private static DelegateBridge __Hotfix0_get_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_quantity; // 0x30
	private static DelegateBridge __Hotfix0_get_enableRoomType; // 0x38
	private static DelegateBridge __Hotfix0_get_themeId; // 0x40
	private static DelegateBridge __Hotfix0_get_groupId; // 0x48
	private static DelegateBridge __Hotfix0_get_part; // 0x50
	private static DelegateBridge __Hotfix0_get_mesh; // 0x58
	private static DelegateBridge __Hotfix0_get_material; // 0x60
	private static DelegateBridge __Hotfix0_get_icon; // 0x68
	private static DelegateBridge __Hotfix0_get_desc; // 0x70
	private static DelegateBridge __Hotfix0_get_usage; // 0x78
	private static DelegateBridge __Hotfix0_get_furniType; // 0x80
	private static DelegateBridge __Hotfix0_get_subType; // 0x88

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

	// RVA: 0x37c7454 VA: 0x7595ddf454
	public Void .ctor(FurnitureData furnitureData, CachedAssetLoader loader, IFurnitureGroupData groupData) { }
	// RVA: 0x37c7524 VA: 0x7595ddf524
	public String get_id() { }
	// RVA: 0x37c7598 VA: 0x7595ddf598
	public String get_displayName() { }
	// RVA: 0x37c760c VA: 0x7595ddf60c
	public Int32 get_comfort() { }
	// RVA: 0x37c7680 VA: 0x7595ddf680
	public Int32 get_rarity() { }
	// RVA: 0x37c76f4 VA: 0x7595ddf6f4
	public Int32 get_sortId() { }
	// RVA: 0x37c7768 VA: 0x7595ddf768
	public Int32 get_quantity() { }
	// RVA: 0x37c77dc VA: 0x7595ddf7dc
	public Int32 get_enableRoomType() { }
	// RVA: 0x37c7850 VA: 0x7595ddf850
	public String get_themeId() { }
	// RVA: 0x37c7954 VA: 0x7595ddf954
	public String get_groupId() { }
	// RVA: 0x37c7a54 VA: 0x7595ddfa54
	public DIYRoomPart get_part() { }
	// RVA: 0x37c7ad0 VA: 0x7595ddfad0
	public Mesh get_mesh() { }
	// RVA: 0x37c7b34 VA: 0x7595ddfb34
	public Material get_material() { }
	// RVA: 0x37c7d1c VA: 0x7595ddfd1c
	public Sprite get_icon() { }
	// RVA: 0x37c7dbc VA: 0x7595ddfdbc
	public String get_desc() { }
	// RVA: 0x37c7e30 VA: 0x7595ddfe30
	public String get_usage() { }
	// RVA: 0x37c7ea4 VA: 0x7595ddfea4
	public FurnitureType get_furniType() { }
	// RVA: 0x37c7f18 VA: 0x7595ddff18
	public FurnitureSubType get_subType() { }
}
```