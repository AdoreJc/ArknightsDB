# DIYRoomModifierMemento

**Namespace:** `Torappu.Building.DIY`


## Methods

- `Void BuildFromModifierManager(IDIYRoomModifierManager)`

- `Void SaveToModifierManager(IDIYRoomModifierManager)`

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`

- `Void RegisterListener(IDIYRoomModifierProviderListener)`

- `Void UnregisterListener(IDIYRoomModifierProviderListener)`

- `Void AddDIYRoomModifier(DIYRoomModifier)`

- `Void RemoveDIYRoomModifier(DIYRoomModifier)`

- `Void ClearDIYRoomModifier()`

- `Void <BuildFromModifierManager>b__2_1(DIYRoomModifier)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYRoomModifierMemento : IDIYRoomModifierManager, IDIYRoomModifierProvider
{
	private List`1 m_listeners; // 0x10
	private List`1 m_modifiers; // 0x18


	// RVA: 0x37c95a0 VA: 0x7595de15a0
	public Void BuildFromModifierManager(IDIYRoomModifierManager mgr) { }
	// RVA: 0x37c977c VA: 0x7595de177c
	public Void SaveToModifierManager(IDIYRoomModifierManager mgr) { }
	// RVA: 0x37c9958 VA: 0x7595de1958
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37c9a58 VA: 0x7595de1a58
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37c9b48 VA: 0x7595de1b48
	public Void RegisterListener(IDIYRoomModifierProviderListener listener) { }
	// RVA: 0x37c9c30 VA: 0x7595de1c30
	public Void UnregisterListener(IDIYRoomModifierProviderListener listener) { }
	// RVA: 0x37c9cc0 VA: 0x7595de1cc0
	public Void AddDIYRoomModifier(DIYRoomModifier modifier) { }
	// RVA: 0x37c9e94 VA: 0x7595de1e94
	public Void RemoveDIYRoomModifier(DIYRoomModifier modifier) { }
	// RVA: 0x37ca018 VA: 0x7595de2018
	public Void ClearDIYRoomModifier() { }
	// RVA: 0x37ca208 VA: 0x7595de2208
	public Void .ctor() { }
	// RVA: 0x37ca2e0 VA: 0x7595de22e0
	private Void <BuildFromModifierManager>b__2_1(DIYRoomModifier x) { }
}
```