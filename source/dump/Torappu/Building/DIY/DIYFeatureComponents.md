# DIYFeatureComponents

**Namespace:** `Torappu.Building.DIY`


## Fields

- `CachedAssetLoader m_cachedResourcesLoader`

- `FurnitureManager m_furnitureManager`

- `DIYRoomModifierManager m_modifierManager`

- `FurniturePresetManager m_presetManager`

- `FurnitureSaver m_furnitureSaver`

- `DIYRoomInfoManager m_diyRoomInfoManager`

- `DIYShop m_diyShop`

- `FurnitureDatabase m_furnitureDatabase`

- `DIYRoomModifierDatabase m_modifierDatabase`

- `FurnitureTypeDatabase m_furnitureTypeDatabase`

- `FurnitureStorage m_furnitureStorage`

- `DIYRoomTemplateDatabase m_diyRoomTemplateDatabase`

- `FurnitureGroupDatabase m_furnitureGroupDatabase`

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
// Namespace : Torappu.Building.DIY
public class DIYFeatureComponents : IDIYFeatureComponents
{
	private CachedAssetLoader m_cachedResourcesLoader; // 0x10
	private FurnitureManager m_furnitureManager; // 0x18
	private DIYRoomModifierManager m_modifierManager; // 0x20
	private FurniturePresetManager m_presetManager; // 0x28
	private FurnitureSaver m_furnitureSaver; // 0x30
	private DIYRoomInfoManager m_diyRoomInfoManager; // 0x38
	private DIYShop m_diyShop; // 0x40
	private FurnitureDatabase m_furnitureDatabase; // 0x48
	private DIYRoomModifierDatabase m_modifierDatabase; // 0x50
	private FurnitureTypeDatabase m_furnitureTypeDatabase; // 0x58
	private FurnitureStorage m_furnitureStorage; // 0x60
	private DIYRoomTemplateDatabase m_diyRoomTemplateDatabase; // 0x68
	private FurnitureGroupDatabase m_furnitureGroupDatabase; // 0x70
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

	// RVA: 0x37b2734 VA: 0x7595dca734
	public Boolean Init() { }
	// RVA: 0x37b2e48 VA: 0x7595dcae48
	public IFurnitureManager get_furnitureManager() { }
	// RVA: 0x37b2e50 VA: 0x7595dcae50
	public IDIYRoomModifierManager get_modifierManager() { }
	// RVA: 0x37b2e58 VA: 0x7595dcae58
	public IDIYRoomInfoProvider get_roomInfoManager() { }
	// RVA: 0x37b2e60 VA: 0x7595dcae60
	public IDIYPresetManager get_presetManager() { }
	// RVA: 0x37b2e68 VA: 0x7595dcae68
	public IDIYShop get_shop() { }
	// RVA: 0x37b2e70 VA: 0x7595dcae70
	public IFurnitureStorage get_storage() { }
	// RVA: 0x37b2e78 VA: 0x7595dcae78
	public IFurnitureSaver get_saver() { }
	// RVA: 0x37b2e80 VA: 0x7595dcae80
	public IFurnitureTypeDB get_furnitureTypeDB() { }
	// RVA: 0x37b2e88 VA: 0x7595dcae88
	public IFurnitureDataProvider get_furnitureDataProvider() { }
	// RVA: 0x37b2e90 VA: 0x7595dcae90
	public IDIYRoomModifierDataProvider get_modifierDataProvider() { }
	// RVA: 0x37b2e98 VA: 0x7595dcae98
	public IFurnitureGroupDataProvider get_furnitureGroupDatabase() { }
	// RVA: 0x37b2ea0 VA: 0x7595dcaea0
	public Void ReleaseCachedResources() { }
	// RVA: 0x37b2ed4 VA: 0x7595dcaed4
	public Void .ctor() { }
}
```