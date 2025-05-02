# MockFurnitureManager

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `MockFurnitureDB _furnitureDB`

- `IFurnitureDataProvider m_furnitureDB`


## Methods

- `Void Setup(IFurnitureDataProvider)`

- `Void AddFurniture(Furniture)`

- `Void RemoveFurniture(Furniture)`

- `Void ClearFurniture()`

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`

- `Void RegisterListener(IFurnitureProviderListener)`

- `Void UnregisterListener(IFurnitureProviderListener)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockFurnitureManager : MonoBehaviour, IFurnitureManager, IFurnitureProvider
{
	private MockFurnitureConfig[] _furnitureConfigs; // 0x18
	private MockFurnitureDB _furnitureDB; // 0x20
	private List`1 m_listeners; // 0x28
	private List`1 m_furnitures; // 0x30
	private IFurnitureDataProvider m_furnitureDB; // 0x38


	// RVA: 0x37ed93c VA: 0x7595e0593c
	public Void Setup(IFurnitureDataProvider db) { }
	// RVA: 0x37fab18 VA: 0x7595e12b18
	public Void AddFurniture(Furniture furniture) { }
	// RVA: 0x37facd4 VA: 0x7595e12cd4
	public Void RemoveFurniture(Furniture furniture) { }
	// RVA: 0x37fae40 VA: 0x7595e12e40
	public Void ClearFurniture() { }
	// RVA: 0x37fb00c VA: 0x7595e1300c
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f8a90 VA: 0x7595e10a90
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37fb10c VA: 0x7595e1310c
	public Void RegisterListener(IFurnitureProviderListener listener) { }
	// RVA: 0x37fb1f4 VA: 0x7595e131f4
	public Void UnregisterListener(IFurnitureProviderListener listener) { }
	// RVA: 0x37fb284 VA: 0x7595e13284
	public Void .ctor() { }
}
```