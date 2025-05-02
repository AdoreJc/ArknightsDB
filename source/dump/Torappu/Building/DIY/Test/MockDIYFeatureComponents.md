# MockDIYFeatureComponents

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `MockFurnitureFromTableManager _furnitureManager`

- `MockDIYRoomModifierManager _roomModifierManager`

- `MockDIYRoomInfoManager _roomInfoManager`

- `MockDIYPresetManager _presetManager`

- `MockDIYShop _diyShop`

- `MockFurnitureStorage _furnitureStorage`

- `MockFurnitureSaver _furnitureSaver`

- `MockFurnitureGroupDB _furnitureGroupDatabase`

- `FurnitureDatabase m_furnitureDatabase`

- `DIYRoomModifierDatabase m_modifierDatabase`

- `FurnitureTypeDatabase m_furnitureTypeDatabase`

- `CachedAssetLoader m_cachedResourceLoader`

- `Boolean m_inited`


## Properties

- `IFurnitureManager furnitureManager`

- `IDIYRoomModifierManager modifierManager`

- `IDIYRoomInfoProvider roomInfoManager`

- `IDIYPresetManager presetManager`

- `IDIYShop shop`

- `IFurnitureStorage storage`

- `IFurnitureSaver saver`

- `IFurnitureTypeDB furnitureTypeDB`

- `IFurnitureDataProvider furnitureDataProvider`

- `IDIYRoomModifierDataProvider modifierDataProvider`

- `IFurnitureGroupDataProvider furnitureGroupDatabase`


## Methods

- `Boolean Init()`

- `IFurnitureManager get_furnitureManager()`

- `IDIYRoomModifierManager get_modifierManager()`

- `IDIYRoomInfoProvider get_roomInfoManager()`

- `IDIYPresetManager get_presetManager()`

- `IDIYShop get_shop()`

- `IFurnitureStorage get_storage()`

- `IFurnitureSaver get_saver()`

- `IFurnitureTypeDB get_furnitureTypeDB()`

- `IFurnitureDataProvider get_furnitureDataProvider()`

- `IDIYRoomModifierDataProvider get_modifierDataProvider()`

- `IFurnitureGroupDataProvider get_furnitureGroupDatabase()`

- `Void ReleaseCachedResources()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockDIYFeatureComponents : MonoBehaviour, IDIYFeatureComponents
{
	private MockFurnitureFromTableManager _furnitureManager; // 0x18
	private MockDIYRoomModifierManager _roomModifierManager; // 0x20
	private MockDIYRoomInfoManager _roomInfoManager; // 0x28
	private MockDIYPresetManager _presetManager; // 0x30
	private MockDIYShop _diyShop; // 0x38
	private MockFurnitureStorage _furnitureStorage; // 0x40
	private MockFurnitureSaver _furnitureSaver; // 0x48
	private MockFurnitureGroupDB _furnitureGroupDatabase; // 0x50
	private FurnitureDatabase m_furnitureDatabase; // 0x58
	private DIYRoomModifierDatabase m_modifierDatabase; // 0x60
	private FurnitureTypeDatabase m_furnitureTypeDatabase; // 0x68
	private CachedAssetLoader m_cachedResourceLoader; // 0x70
	private Boolean m_inited; // 0x78

	public IFurnitureManager furnitureManager { get; }
	public IDIYRoomModifierManager modifierManager { get; }
	public IDIYRoomInfoProvider roomInfoManager { get; }
	public IDIYPresetManager presetManager { get; }
	public IDIYShop shop { get; }
	public IFurnitureStorage storage { get; }
	public IFurnitureSaver saver { get; }
	public IFurnitureTypeDB furnitureTypeDB { get; }
	public IFurnitureDataProvider furnitureDataProvider { get; }
	public IDIYRoomModifierDataProvider modifierDataProvider { get; }
	public IFurnitureGroupDataProvider furnitureGroupDatabase { get; }

	// RVA: 0x37f2c84 VA: 0x7595e0ac84
	public Boolean Init() { }
	// RVA: 0x37f30a4 VA: 0x7595e0b0a4
	public IFurnitureManager get_furnitureManager() { }
	// RVA: 0x37f30ac VA: 0x7595e0b0ac
	public IDIYRoomModifierManager get_modifierManager() { }
	// RVA: 0x37f30b4 VA: 0x7595e0b0b4
	public IDIYRoomInfoProvider get_roomInfoManager() { }
	// RVA: 0x37f30bc VA: 0x7595e0b0bc
	public IDIYPresetManager get_presetManager() { }
	// RVA: 0x37f30c4 VA: 0x7595e0b0c4
	public IDIYShop get_shop() { }
	// RVA: 0x37f30cc VA: 0x7595e0b0cc
	public IFurnitureStorage get_storage() { }
	// RVA: 0x37f30d4 VA: 0x7595e0b0d4
	public IFurnitureSaver get_saver() { }
	// RVA: 0x37f30dc VA: 0x7595e0b0dc
	public IFurnitureTypeDB get_furnitureTypeDB() { }
	// RVA: 0x37f30e4 VA: 0x7595e0b0e4
	public IFurnitureDataProvider get_furnitureDataProvider() { }
	// RVA: 0x37f30ec VA: 0x7595e0b0ec
	public IDIYRoomModifierDataProvider get_modifierDataProvider() { }
	// RVA: 0x37f30f4 VA: 0x7595e0b0f4
	public IFurnitureGroupDataProvider get_furnitureGroupDatabase() { }
	// RVA: 0x37f30fc VA: 0x7595e0b0fc
	public Void ReleaseCachedResources() { }
	// RVA: 0x37f3100 VA: 0x7595e0b100
	public Void .ctor() { }
}
```