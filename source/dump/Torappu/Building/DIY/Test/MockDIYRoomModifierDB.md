# MockDIYRoomModifierDB

**Namespace:** `Torappu.Building.DIY.Test`


## Methods

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`

- `IDIYRoomModifierData GetData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockDIYRoomModifierDB : MonoBehaviour, IDIYRoomModifierDataProvider, IHotfixable
{
	private DIYRoomModifierData[] _DIYRoomModifierData; // 0x18
	private static DelegateBridge __Hotfix0_QueryData; // 0x0
	private static DelegateBridge __Hotfix0_QueryDatas; // 0x8
	private static DelegateBridge __Hotfix0_GetData; // 0x10
	private static DelegateBridge __Hotfix0_GetDatasByType; // 0x18
	private static DelegateBridge __Hotfix0_GetDatasBySubType; // 0x20
	private static DelegateBridge __Hotfix0_GetDatasByThemeId; // 0x28
	private static DelegateBridge __Hotfix0_GetDatasByRoomPart; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x37f3a2c VA: 0x7595e0ba2c
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f3b50 VA: 0x7595e0bb50
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f3c68 VA: 0x7595e0bc68
	public IDIYRoomModifierData GetData(String furnitureId) { }
	// RVA: 0x37f3ddc VA: 0x7595e0bddc
	public IList`1 GetDatasByType(FurnitureType type) { }
	// RVA: 0x37f3f84 VA: 0x7595e0bf84
	public IList`1 GetDatasBySubType(FurnitureSubType subType) { }
	// RVA: 0x37f412c VA: 0x7595e0c12c
	public IList`1 GetDatasByThemeId(String themeId) { }
	// RVA: 0x37f42e0 VA: 0x7595e0c2e0
	public IList`1 GetDatasByRoomPart(DIYRoomPart part) { }
	// RVA: 0x37f4488 VA: 0x7595e0c488
	public Void .ctor() { }
}
```