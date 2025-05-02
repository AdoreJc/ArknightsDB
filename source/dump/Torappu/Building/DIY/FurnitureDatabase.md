# FurnitureDatabase

**Namespace:** `Torappu.Building.DIY`


## Fields

- `GameObjectSplitFrameLoadBalancer <loadBalancer>k__BackingField`

- `BuildingDB m_buildingDB`


## Properties

- `GameObjectSplitFrameLoadBalancer loadBalancer`


## Methods

- `GameObjectSplitFrameLoadBalancer get_loadBalancer()`

- `Void set_loadBalancer(GameObjectSplitFrameLoadBalancer)`

- `Void Setup(IFurnitureGroupDataProvider, AbstractAssetLoader)`

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`

- `IFurnitureData GetData(String)`

- `Void UpdateTime(Single)`

- `Void OnRelease()`

- `Void _SetupSearchTables()`

- `Void _AddToListInDict(KeyType, DataType, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class FurnitureDatabase : IFurnitureDataProvider, IHotfixable, ITimeWatcher
{
	private const String DEFAULT_FURNITURE_PREFAB_NAME; // 0x0
	private GameObjectSplitFrameLoadBalancer <loadBalancer>k__BackingField; // 0x10
	private List`1 m_adapters; // 0x18
	private BuildingDB m_buildingDB; // 0x20
	private Dictionary`2 m_furniIdToAdapter; // 0x28
	private Dictionary`2 m_themeIdToAdapters; // 0x30
	private Dictionary`2 m_typeToAdapters; // 0x38
	private Dictionary`2 m_subTypeToAdapters; // 0x40
	private static DelegateBridge __Hotfix0_get_loadBalancer; // 0x0
	private static DelegateBridge __Hotfix0_set_loadBalancer; // 0x8
	private static DelegateBridge __Hotfix0_Setup; // 0x10
	private static DelegateBridge __Hotfix0_QueryData; // 0x18
	private static DelegateBridge __Hotfix0_QueryDatas; // 0x20
	private static DelegateBridge __Hotfix0_GetData; // 0x28
	private static DelegateBridge __Hotfix0_GetDatasByType; // 0x30
	private static DelegateBridge __Hotfix0_GetDatasBySubType; // 0x38
	private static DelegateBridge __Hotfix0_GetDatasByThemeId; // 0x40
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x48
	private static DelegateBridge __Hotfix0_OnRelease; // 0x50
	private static DelegateBridge __Hotfix0__SetupSearchTables; // 0x58
	private static DelegateBridge __Hotfix0__AddToListInDict; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private GameObjectSplitFrameLoadBalancer loadBalancer { get; set; }

	// RVA: 0x37caff4 VA: 0x7595de2ff4
	private GameObjectSplitFrameLoadBalancer get_loadBalancer() { }
	// RVA: 0x37cb05c VA: 0x7595de305c
	private Void set_loadBalancer(GameObjectSplitFrameLoadBalancer value) { }
	// RVA: 0x37cb0e0 VA: 0x7595de30e0
	public Void Setup(IFurnitureGroupDataProvider groupDataProvider, AbstractAssetLoader assetLoader) { }
	// RVA: 0x37cb7b0 VA: 0x7595de37b0
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37cb954 VA: 0x7595de3954
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37cbae8 VA: 0x7595de3ae8
	public IFurnitureData GetData(String furnitureId) { }
	// RVA: 0x37cbb84 VA: 0x7595de3b84
	public IList`1 GetDatasByType(FurnitureType type) { }
	// RVA: 0x37cbc20 VA: 0x7595de3c20
	public IList`1 GetDatasBySubType(FurnitureSubType subType) { }
	// RVA: 0x37cbcbc VA: 0x7595de3cbc
	public IList`1 GetDatasByThemeId(String themeId) { }
	// RVA: 0x37cbd58 VA: 0x7595de3d58
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x37cbde4 VA: 0x7595de3de4
	public Void OnRelease() { }
	// RVA: 0x37cb534 VA: 0x7595de3534
	private Void _SetupSearchTables() { }
	// RVA: 0x VA: 0x0
	private Void _AddToListInDict(KeyType key, DataType value, Dictionary`2 dict) { }
	// RVA: 0x37cc0cc VA: 0x7595de40cc
	public Void .ctor() { }
}
```