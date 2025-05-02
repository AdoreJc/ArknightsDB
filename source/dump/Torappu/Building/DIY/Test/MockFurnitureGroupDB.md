# MockFurnitureGroupDB

**Namespace:** `Torappu.Building.DIY.Test`


## Methods

- `Void Setup(IFurnitureDataProvider, IDIYRoomModifierDataProvider)`

- `IFurnitureGroupData GetGroupDataByFurniture(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockFurnitureGroupDB : MonoBehaviour, IFurnitureGroupDataProvider, IHotfixable
{
	private List`1 _entries; // 0x18
	private List`1 _quickSetupItem; // 0x20
	private static DelegateBridge __Hotfix0_Setup; // 0x0
	private static DelegateBridge __Hotfix0_get_datas; // 0x8
	private static DelegateBridge __Hotfix0_GetFurnitureQuickSetup; // 0x10
	private static DelegateBridge __Hotfix0_GetGroupDataByFurniture; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public IEnumerable`1 datas { get; }

	// RVA: 0x37f2de4 VA: 0x7595e0ade4
	public Void Setup(IFurnitureDataProvider furnitureDB, IDIYRoomModifierDataProvider modifierDB) { }
	// RVA: 0x37f9b08 VA: 0x7595e11b08
	public IEnumerable`1 get_datas() { }
	// RVA: 0x37f9bf8 VA: 0x7595e11bf8
	public IEnumerable`1 GetFurnitureQuickSetup(String themeId) { }
	// RVA: 0x37f9d0c VA: 0x7595e11d0c
	public IFurnitureGroupData GetGroupDataByFurniture(String furnitureId) { }
	// RVA: 0x37fa3d4 VA: 0x7595e123d4
	public Void .ctor() { }
}
```