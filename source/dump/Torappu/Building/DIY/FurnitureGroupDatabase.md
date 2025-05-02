# FurnitureGroupDatabase

**Namespace:** `Torappu.Building.DIY`


## Methods

- `Void SetupGroup()`

- `Void SetupQuickSetup(IFurnitureDataProvider, IDIYRoomModifierDataProvider)`

- `IFurnitureGroupData GetGroupDataByFurniture(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class FurnitureGroupDatabase : IFurnitureGroupDataProvider, IHotfixable
{
	private List`1 m_dataList; // 0x10
	private Dictionary`2 m_furniIdToGroupData; // 0x18
	private Dictionary`2 m_quickSetup; // 0x20
	private static DelegateBridge __Hotfix0_SetupGroup; // 0x0
	private static DelegateBridge __Hotfix0_SetupQuickSetup; // 0x8
	private static DelegateBridge __Hotfix0_get_datas; // 0x10
	private static DelegateBridge __Hotfix0_GetFurnitureQuickSetup; // 0x18
	private static DelegateBridge __Hotfix0_GetGroupDataByFurniture; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public IEnumerable`1 datas { get; }

	// RVA: 0x37cf310 VA: 0x7595de7310
	public Void SetupGroup() { }
	// RVA: 0x37cf624 VA: 0x7595de7624
	public Void SetupQuickSetup(IFurnitureDataProvider furnitureDB, IDIYRoomModifierDataProvider modifierDB) { }
	// RVA: 0x37cfc74 VA: 0x7595de7c74
	public IEnumerable`1 get_datas() { }
	// RVA: 0x37cfd64 VA: 0x7595de7d64
	public IEnumerable`1 GetFurnitureQuickSetup(String themeId) { }
	// RVA: 0x37cfe78 VA: 0x7595de7e78
	public IFurnitureGroupData GetGroupDataByFurniture(String furnitureId) { }
	// RVA: 0x37cff28 VA: 0x7595de7f28
	public Void .ctor() { }
}
```