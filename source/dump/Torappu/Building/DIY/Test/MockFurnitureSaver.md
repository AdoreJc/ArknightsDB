# MockFurnitureSaver

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `Single _fakeDelay`


## Methods

- `IEnumerator _ResultCoroutine(Action`1, Int32)`

- `Void SaveFurniture(Int32, IFurnitureProvider, IDIYRoomModifierProvider, IFurnitureManager, IDIYRoomModifierManager, Action`1)`

- `Void RefreshFurniture()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockFurnitureSaver : MonoBehaviour, IFurnitureSaver
{
	private Single _fakeDelay; // 0x18


	// RVA: 0x37fb5c0 VA: 0x7595e135c0
	private IEnumerator _ResultCoroutine(Action`1 resultHandler, Int32 result) { }
	// RVA: 0x37fb680 VA: 0x7595e13680
	public Void SaveFurniture(Int32 index, IFurnitureProvider furnitureSource, IDIYRoomModifierProvider modifierSource, IFurnitureManager furnitureTarget, IDIYRoomModifierManager modifierTarget, Action`1 resultHandler) { }
	// RVA: 0x37fbf18 VA: 0x7595e13f18
	public Void RefreshFurniture() { }
	// RVA: 0x37fbf1c VA: 0x7595e13f1c
	public Void .ctor() { }
}
```