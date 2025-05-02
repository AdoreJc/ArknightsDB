# FurnitureMemento

**Namespace:** `Torappu.Building.DIY`


## Methods

- `Void BuildFromFurnitureManager(IFurnitureProvider)`

- `Void SaveToFurnitureManager(IFurnitureManager)`

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`

- `Void RegisterListener(IFurnitureProviderListener)`

- `Void UnregisterListener(IFurnitureProviderListener)`

- `Void AddFurniture(Furniture)`

- `Void RemoveFurniture(Furniture)`

- `Void ClearFurniture()`

- `Void <BuildFromFurnitureManager>b__2_1(Furniture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class FurnitureMemento : IFurnitureManager, IFurnitureProvider
{
	private List`1 m_listeners; // 0x10
	private List`1 m_furnitures; // 0x18


	// RVA: 0x37d2200 VA: 0x7595dea200
	public Void BuildFromFurnitureManager(IFurnitureProvider mgr) { }
	// RVA: 0x37d23dc VA: 0x7595dea3dc
	public Void SaveToFurnitureManager(IFurnitureManager mgr) { }
	// RVA: 0x37d2634 VA: 0x7595dea634
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37d2734 VA: 0x7595dea734
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37d2824 VA: 0x7595dea824
	public Void RegisterListener(IFurnitureProviderListener listener) { }
	// RVA: 0x37d290c VA: 0x7595dea90c
	public Void UnregisterListener(IFurnitureProviderListener listener) { }
	// RVA: 0x37d299c VA: 0x7595dea99c
	public Void AddFurniture(Furniture furniture) { }
	// RVA: 0x37d2b58 VA: 0x7595deab58
	public Void RemoveFurniture(Furniture furniture) { }
	// RVA: 0x37d2cc4 VA: 0x7595deacc4
	public Void ClearFurniture() { }
	// RVA: 0x37d2e90 VA: 0x7595deae90
	public Void .ctor() { }
	// RVA: 0x37d2f68 VA: 0x7595deaf68
	private Void <BuildFromFurnitureManager>b__2_1(Furniture x) { }
}
```