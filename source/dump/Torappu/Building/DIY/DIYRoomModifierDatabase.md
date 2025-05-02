# DIYRoomModifierDatabase

**Namespace:** `Torappu.Building.DIY`


## Fields

- `CachedAssetLoader <cachedAssetLoader>k__BackingField`


## Properties

- `CachedAssetLoader cachedAssetLoader`


## Methods

- `CachedAssetLoader get_cachedAssetLoader()`

- `Void set_cachedAssetLoader(CachedAssetLoader)`

- `Void Setup(IFurnitureGroupDataProvider)`

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`

- `IDIYRoomModifierData GetData(String)`

- `Void _SetupSearchTables()`

- `Void _AddToListInDict(KeyType, DataType, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYRoomModifierDatabase : IDIYRoomModifierDataProvider, IHotfixable
{
	private const String DEFAULT_FURNITURE_PREFAB_NAME; // 0x0
	private CachedAssetLoader <cachedAssetLoader>k__BackingField; // 0x10
	private List`1 m_adapters; // 0x18
	private Dictionary`2 m_furniIdToAdapter; // 0x20
	private Dictionary`2 m_themeIdToAdapters; // 0x28
	private Dictionary`2 m_typeToAdapters; // 0x30
	private Dictionary`2 m_subTypeToAdapters; // 0x38
	private Dictionary`2 m_roomPartToAdapter; // 0x40
	private static DelegateBridge __Hotfix0_get_cachedAssetLoader; // 0x0
	private static DelegateBridge __Hotfix0_set_cachedAssetLoader; // 0x8
	private static DelegateBridge __Hotfix0_Setup; // 0x10
	private static DelegateBridge __Hotfix0_QueryData; // 0x18
	private static DelegateBridge __Hotfix0_QueryDatas; // 0x20
	private static DelegateBridge __Hotfix0_GetData; // 0x28
	private static DelegateBridge __Hotfix0_GetDatasByType; // 0x30
	private static DelegateBridge __Hotfix0_GetDatasBySubType; // 0x38
	private static DelegateBridge __Hotfix0_GetDatasByThemeId; // 0x40
	private static DelegateBridge __Hotfix0_GetDatasByRoomPart; // 0x48
	private static DelegateBridge __Hotfix0__SetupSearchTables; // 0x50
	private static DelegateBridge __Hotfix0__AddToListInDict; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public CachedAssetLoader cachedAssetLoader { get; set; }

	// RVA: 0x37c6ac0 VA: 0x7595ddeac0
	public CachedAssetLoader get_cachedAssetLoader() { }
	// RVA: 0x37b2abc VA: 0x7595dcaabc
	public Void set_cachedAssetLoader(CachedAssetLoader value) { }
	// RVA: 0x37b2b40 VA: 0x7595dcab40
	public Void Setup(IFurnitureGroupDataProvider groupDataProvider) { }
	// RVA: 0x37c6e10 VA: 0x7595ddee10
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37c6fb4 VA: 0x7595ddefb4
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37c7148 VA: 0x7595ddf148
	public IDIYRoomModifierData GetData(String furnitureId) { }
	// RVA: 0x37c71e4 VA: 0x7595ddf1e4
	public IList`1 GetDatasByType(FurnitureType type) { }
	// RVA: 0x37c7280 VA: 0x7595ddf280
	public IList`1 GetDatasBySubType(FurnitureSubType subType) { }
	// RVA: 0x37c731c VA: 0x7595ddf31c
	public IList`1 GetDatasByThemeId(String themeId) { }
	// RVA: 0x37c73b8 VA: 0x7595ddf3b8
	public IList`1 GetDatasByRoomPart(DIYRoomPart part) { }
	// RVA: 0x37c6b28 VA: 0x7595ddeb28
	private Void _SetupSearchTables() { }
	// RVA: 0x VA: 0x0
	private Void _AddToListInDict(KeyType key, DataType value, Dictionary`2 dict) { }
	// RVA: 0x37b28b8 VA: 0x7595dca8b8
	public Void .ctor() { }
}
```