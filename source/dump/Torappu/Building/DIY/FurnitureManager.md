# FurnitureManager

**Namespace:** `Torappu.Building.DIY`


## Fields

- `IFurnitureDataProvider m_furnitureDB`

- `Boolean m_furnitureDataDirty`


## Methods

- `Void SetDataDirty()`

- `Void Setup(IFurnitureDataProvider, Boolean)`

- `Void Refresh(PlayerBuildingRoom)`

- `Void _Refresh(String, PlayerBuildingDIYSolution)`

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
// Namespace : Torappu.Building.DIY
public class FurnitureManager : IFurnitureManager, IFurnitureProvider
{
	private List`1 m_listeners; // 0x10
	private List`1 m_furnitures; // 0x18
	private IFurnitureDataProvider m_furnitureDB; // 0x20
	private Boolean m_furnitureDataDirty; // 0x28


	// RVA: 0x37d09f0 VA: 0x7595de89f0
	public Void SetDataDirty() { }
	// RVA: 0x37d09fc VA: 0x7595de89fc
	public Void Setup(IFurnitureDataProvider db, Boolean ignoreRefresh) { }
	// RVA: 0x37d0a9c VA: 0x7595de8a9c
	public Void Refresh(PlayerBuildingRoom playerBuildingRoom) { }
	// RVA: 0x37d103c VA: 0x7595de903c
	private Void _Refresh(String slotId, PlayerBuildingDIYSolution diySolution) { }
	// RVA: 0x37d1808 VA: 0x7595de9808
	public Void AddFurniture(Furniture furniture) { }
	// RVA: 0x37d19d4 VA: 0x7595de99d4
	public Void RemoveFurniture(Furniture furniture) { }
	// RVA: 0x37d0e70 VA: 0x7595de8e70
	public Void ClearFurniture() { }
	// RVA: 0x37d1b40 VA: 0x7595de9b40
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37d1c88 VA: 0x7595de9c88
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37d1dc0 VA: 0x7595de9dc0
	public Void RegisterListener(IFurnitureProviderListener listener) { }
	// RVA: 0x37d1ea8 VA: 0x7595de9ea8
	public Void UnregisterListener(IFurnitureProviderListener listener) { }
	// RVA: 0x37d1f38 VA: 0x7595de9f38
	public Void .ctor() { }
}
```