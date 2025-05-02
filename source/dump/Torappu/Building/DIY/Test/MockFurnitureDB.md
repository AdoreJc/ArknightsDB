# MockFurnitureDB

**Namespace:** `Torappu.Building.DIY.Test`


## Methods

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`

- `IFurnitureData GetData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockFurnitureDB : MonoBehaviour, IFurnitureDataProvider, IHotfixable
{
	public FurnitureData[] _furnitureData; // 0x18
	private static DelegateBridge __Hotfix0_QueryData; // 0x0
	private static DelegateBridge __Hotfix0_QueryDatas; // 0x8
	private static DelegateBridge __Hotfix0_GetData; // 0x10
	private static DelegateBridge __Hotfix0_GetDatasByType; // 0x18
	private static DelegateBridge __Hotfix0_GetDatasBySubType; // 0x20
	private static DelegateBridge __Hotfix0_GetDatasByThemeId; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x37f7090 VA: 0x7595e0f090
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f71b4 VA: 0x7595e0f1b4
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f72cc VA: 0x7595e0f2cc
	public IFurnitureData GetData(String furnitureId) { }
	// RVA: 0x37f7440 VA: 0x7595e0f440
	public IList`1 GetDatasByType(FurnitureType type) { }
	// RVA: 0x37f75e8 VA: 0x7595e0f5e8
	public IList`1 GetDatasBySubType(FurnitureSubType subType) { }
	// RVA: 0x37f7790 VA: 0x7595e0f790
	public IList`1 GetDatasByThemeId(String themeId) { }
	// RVA: 0x37f7944 VA: 0x7595e0f944
	public Void .ctor() { }
}
```