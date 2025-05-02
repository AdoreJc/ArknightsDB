# FurnitureDataAdapter

**Namespace:** ` `


## Fields

- `FurnitureData m_buildingFurnitureData`

- `IFurnitureGroupData m_groupData`

- `GameObjectSplitFrameLoadBalancer m_loadBalancer`


## Properties

- `AbstractAssetLoader assetLoader`

- `String id`

- `String displayName`

- `Int32 dimX`

- `Int32 dimY`

- `Int32 dimZ`

- `Boolean validOnRotate`

- `Boolean enableRotate`

- `Int32 comfort`

- `Int32 rarity`

- `Int32 sortId`

- `Int32 quantity`

- `Int32 enableRoomType`

- `String themeId`

- `String groupId`

- `FurnitureInteractType interactType`

- `FurnitureLocationType locationType`

- `GameObject prefab`

- `Sprite icon`

- `String desc`

- `String usage`

- `FurnitureType furniType`

- `FurnitureSubType subType`

- `String musicId`


## Methods

- `AbstractAssetLoader get_assetLoader()`

- `String get_id()`

- `String get_displayName()`

- `Int32 get_dimX()`

- `Int32 get_dimY()`

- `Int32 get_dimZ()`

- `Boolean get_validOnRotate()`

- `Boolean get_enableRotate()`

- `Int32 get_comfort()`

- `Int32 get_rarity()`

- `Int32 get_sortId()`

- `Int32 get_quantity()`

- `Int32 get_enableRoomType()`

- `String get_themeId()`

- `String get_groupId()`

- `FurnitureInteractType get_interactType()`

- `FurnitureLocationType get_locationType()`

- `GameObject get_prefab()`

- `Sprite get_icon()`

- `String get_desc()`

- `String get_usage()`

- `FurnitureType get_furniType()`

- `FurnitureSubType get_subType()`

- `String get_musicId()`

- `IDynamicAssetHandler LoadAsset(IDynamicAssetWrapper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FurnitureDataAdapter : IFurnitureData, IDIYItem, IHotfixable
{
	private FurnitureData m_buildingFurnitureData; // 0x10
	private IFurnitureGroupData m_groupData; // 0x18
	private GameObjectSplitFrameLoadBalancer m_loadBalancer; // 0x20
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_get_id; // 0x10
	private static DelegateBridge __Hotfix0_get_displayName; // 0x18
	private static DelegateBridge __Hotfix0_get_dimX; // 0x20
	private static DelegateBridge __Hotfix0_get_dimY; // 0x28
	private static DelegateBridge __Hotfix0_get_dimZ; // 0x30
	private static DelegateBridge __Hotfix0_get_validOnRotate; // 0x38
	private static DelegateBridge __Hotfix0_get_enableRotate; // 0x40
	private static DelegateBridge __Hotfix0_get_comfort; // 0x48
	private static DelegateBridge __Hotfix0_get_rarity; // 0x50
	private static DelegateBridge __Hotfix0_get_sortId; // 0x58
	private static DelegateBridge __Hotfix0_get_quantity; // 0x60
	private static DelegateBridge __Hotfix0_get_enableRoomType; // 0x68
	private static DelegateBridge __Hotfix0_get_themeId; // 0x70
	private static DelegateBridge __Hotfix0_get_groupId; // 0x78
	private static DelegateBridge __Hotfix0_get_interactType; // 0x80
	private static DelegateBridge __Hotfix0_get_locationType; // 0x88
	private static DelegateBridge __Hotfix0_get_prefab; // 0x90
	private static DelegateBridge __Hotfix0_get_icon; // 0x98
	private static DelegateBridge __Hotfix0_get_desc; // 0xa0
	private static DelegateBridge __Hotfix0_get_usage; // 0xa8
	private static DelegateBridge __Hotfix0_get_furniType; // 0xb0
	private static DelegateBridge __Hotfix0_get_subType; // 0xb8
	private static DelegateBridge __Hotfix0_get_musicId; // 0xc0
	private static DelegateBridge __Hotfix0_LoadAsset; // 0xc8

	private AbstractAssetLoader assetLoader { get; }
	public String id { get; }
	public String displayName { get; }
	public Int32 dimX { get; }
	public Int32 dimY { get; }
	public Int32 dimZ { get; }
	public Boolean validOnRotate { get; }
	public Boolean enableRotate { get; }
	public Int32 comfort { get; }
	public Int32 rarity { get; }
	public Int32 sortId { get; }
	public Int32 quantity { get; }
	public Int32 enableRoomType { get; }
	public String themeId { get; }
	public String groupId { get; }
	public FurnitureInteractType interactType { get; }
	public FurnitureLocationType locationType { get; }
	public GameObject prefab { get; }
	public Sprite icon { get; }
	public String desc { get; }
	public String usage { get; }
	public FurnitureType furniType { get; }
	public FurnitureSubType subType { get; }
	public String musicId { get; }

	// RVA: 0x37cc280 VA: 0x7595de4280
	private AbstractAssetLoader get_assetLoader() { }
	// RVA: 0x37cb464 VA: 0x7595de3464
	public Void .ctor(FurnitureData data, IFurnitureGroupData groupData, GameObjectSplitFrameLoadBalancer loadBalancer) { }
	// RVA: 0x37cbe6c VA: 0x7595de3e6c
	public String get_id() { }
	// RVA: 0x37cc2f4 VA: 0x7595de42f4
	public String get_displayName() { }
	// RVA: 0x37cc368 VA: 0x7595de4368
	public Int32 get_dimX() { }
	// RVA: 0x37cc3dc VA: 0x7595de43dc
	public Int32 get_dimY() { }
	// RVA: 0x37cc450 VA: 0x7595de4450
	public Int32 get_dimZ() { }
	// RVA: 0x37cc4c4 VA: 0x7595de44c4
	public Boolean get_validOnRotate() { }
	// RVA: 0x37cc538 VA: 0x7595de4538
	public Boolean get_enableRotate() { }
	// RVA: 0x37cc5ac VA: 0x7595de45ac
	public Int32 get_comfort() { }
	// RVA: 0x37cc620 VA: 0x7595de4620
	public Int32 get_rarity() { }
	// RVA: 0x37cc694 VA: 0x7595de4694
	public Int32 get_sortId() { }
	// RVA: 0x37cc708 VA: 0x7595de4708
	public Int32 get_quantity() { }
	// RVA: 0x37cc77c VA: 0x7595de477c
	public Int32 get_enableRoomType() { }
	// RVA: 0x37cbee0 VA: 0x7595de3ee0
	public String get_themeId() { }
	// RVA: 0x37cc7f0 VA: 0x7595de47f0
	public String get_groupId() { }
	// RVA: 0x37cc8f0 VA: 0x7595de48f0
	public FurnitureInteractType get_interactType() { }
	// RVA: 0x37cc964 VA: 0x7595de4964
	public FurnitureLocationType get_locationType() { }
	// RVA: 0x37cca00 VA: 0x7595de4a00
	public GameObject get_prefab() { }
	// RVA: 0x37ccbac VA: 0x7595de4bac
	public Sprite get_icon() { }
	// RVA: 0x37ccc4c VA: 0x7595de4c4c
	public String get_desc() { }
	// RVA: 0x37cccc0 VA: 0x7595de4cc0
	public String get_usage() { }
	// RVA: 0x37cbfe4 VA: 0x7595de3fe4
	public FurnitureType get_furniType() { }
	// RVA: 0x37cc058 VA: 0x7595de4058
	public FurnitureSubType get_subType() { }
	// RVA: 0x37ccd34 VA: 0x7595de4d34
	public String get_musicId() { }
	// RVA: 0x37ccda8 VA: 0x7595de4da8
	public IDynamicAssetHandler LoadAsset(IDynamicAssetWrapper assetWrapper) { }
}
```