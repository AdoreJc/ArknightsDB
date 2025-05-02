# MockFurnitureStorage

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `Boolean _each99`


## Methods

- `Void QueryDatas(Predicate`1, Action`1)`

- `FurnitureStorageItem QueryData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockFurnitureStorage : MonoBehaviour, IFurnitureStorage
{
	public Item[] _items; // 0x18
	public Boolean _each99; // 0x20


	// RVA: 0x37fc5e8 VA: 0x7595e145e8
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37fcb20 VA: 0x7595e14b20
	public FurnitureStorageItem QueryData(String furnitureId) { }
	// RVA: 0x37fcc4c VA: 0x7595e14c4c
	public Void .ctor() { }
}
```