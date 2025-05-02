# MockDIYRoomModifierManager

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `MockDIYRoomModifierDB _DIYRoomModifierDB`

- `IDIYRoomModifierDataProvider m_dataProvider`


## Methods

- `Void Setup(IDIYRoomModifierDataProvider)`

- `Void AddDIYRoomModifier(DIYRoomModifier)`

- `Void RemoveDIYRoomModifier(DIYRoomModifier)`

- `Void ClearDIYRoomModifier()`

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`

- `Void RegisterListener(IDIYRoomModifierProviderListener)`

- `Void UnregisterListener(IDIYRoomModifierProviderListener)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockDIYRoomModifierManager : MonoBehaviour, IDIYRoomModifierManager, IDIYRoomModifierProvider
{
	private MockDIYRoomModifierConfig[] _DIYRoomModifierConfigs; // 0x18
	private MockDIYRoomModifierDB _DIYRoomModifierDB; // 0x20
	private List`1 m_listeners; // 0x28
	private List`1 m_DIYRoomModifiers; // 0x30
	private IDIYRoomModifierDataProvider m_dataProvider; // 0x38


	// RVA: 0x37edb60 VA: 0x7595e05b60
	public Void Setup(IDIYRoomModifierDataProvider db) { }
	// RVA: 0x37f5414 VA: 0x7595e0d414
	public Void AddDIYRoomModifier(DIYRoomModifier modifier) { }
	// RVA: 0x37f55e8 VA: 0x7595e0d5e8
	public Void RemoveDIYRoomModifier(DIYRoomModifier modifier) { }
	// RVA: 0x37f576c VA: 0x7595e0d76c
	public Void ClearDIYRoomModifier() { }
	// RVA: 0x37f595c VA: 0x7595e0d95c
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f080c VA: 0x7595e0880c
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f5a5c VA: 0x7595e0da5c
	public Void RegisterListener(IDIYRoomModifierProviderListener listener) { }
	// RVA: 0x37f5b44 VA: 0x7595e0db44
	public Void UnregisterListener(IDIYRoomModifierProviderListener listener) { }
	// RVA: 0x37f5bd4 VA: 0x7595e0dbd4
	public Void .ctor() { }
}
```