# MockFurnitureFromTableManager

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `MockFurnitureManager _additionalManager`

- `MockFurnitureGroupDB _furnitureGroupDB`

- `IFurnitureDataProvider m_furnitureDB`

- `DirectAssetLoader m_assetLoader`


## Methods

- `Void Setup(IFurnitureDataProvider)`

- `Void AddFurniture(Furniture)`

- `Void RemoveFurniture(Furniture)`

- `Void ClearFurniture()`

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`

- `Void RegisterListener(IFurnitureProviderListener)`

- `Void UnregisterListener(IFurnitureProviderListener)`

- `Void OnDestroy()`

- `Void <Setup>b__8_1(Furniture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockFurnitureFromTableManager : MonoBehaviour, IFurnitureManager, IFurnitureProvider
{
	private MockFurnitureConfig[] _furnitureConfigs; // 0x18
	private MockFurnitureManager _additionalManager; // 0x20
	private MockFurnitureGroupDB _furnitureGroupDB; // 0x28
	private List`1 m_listeners; // 0x30
	private List`1 m_furnitures; // 0x38
	private IFurnitureDataProvider m_furnitureDB; // 0x40
	private DirectAssetLoader m_assetLoader; // 0x48


	// RVA: 0x37ed5ac VA: 0x7595e055ac
	public Void Setup(IFurnitureDataProvider db) { }
	// RVA: 0x37f8b80 VA: 0x7595e10b80
	public Void AddFurniture(Furniture furniture) { }
	// RVA: 0x37f8d3c VA: 0x7595e10d3c
	public Void RemoveFurniture(Furniture furniture) { }
	// RVA: 0x37f8ea8 VA: 0x7595e10ea8
	public Void ClearFurniture() { }
	// RVA: 0x37f9074 VA: 0x7595e11074
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f9174 VA: 0x7595e11174
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f9264 VA: 0x7595e11264
	public Void RegisterListener(IFurnitureProviderListener listener) { }
	// RVA: 0x37f934c VA: 0x7595e1134c
	public Void UnregisterListener(IFurnitureProviderListener listener) { }
	// RVA: 0x37f93dc VA: 0x7595e113dc
	private Void OnDestroy() { }
	// RVA: 0x37f93fc VA: 0x7595e113fc
	public Void .ctor() { }
	// RVA: 0x37f9510 VA: 0x7595e11510
	private Void <Setup>b__8_1(Furniture x) { }
}
```