# FurnitureTypeDatabase

**Namespace:** `Torappu.Building.DIY`


## Methods

- `Void Setup()`

- `Void QueryTypeFurnitures(FurnitureType, Action`1)`

- `String GetDisplayName(FurnitureType)`

- `String GetFilterName(DIYFilterType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class FurnitureTypeDatabase : IFurnitureTypeDB, IHotfixable
{
	private List`1 m_data; // 0x10
	private static DelegateBridge __Hotfix0_Setup; // 0x0
	private static DelegateBridge __Hotfix0_QueryTypeFurnitures; // 0x8
	private static DelegateBridge __Hotfix0_GetDisplayName; // 0x10
	private static DelegateBridge __Hotfix0_GetFilterName; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x37d8c8c VA: 0x7595df0c8c
	public Void Setup() { }
	// RVA: 0x37d9098 VA: 0x7595df1098
	public Void QueryTypeFurnitures(FurnitureType furnitureType, Action`1 action) { }
	// RVA: 0x37d9238 VA: 0x7595df1238
	public String GetDisplayName(FurnitureType type) { }
	// RVA: 0x37d92dc VA: 0x7595df12dc
	public String GetFilterName(DIYFilterType filterType) { }
	// RVA: 0x37d9380 VA: 0x7595df1380
	public Void .ctor() { }
}
```