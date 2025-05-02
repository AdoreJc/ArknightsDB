# DIYRoomModifierManager

**Namespace:** `Torappu.Building.DIY`


## Fields

- `IDIYRoomModifierDataProvider m_dataProvider`

- `Boolean m_diyRoomModifierDataDirty`


## Methods

- `Void SetDataDirty()`

- `Void Setup(IDIYRoomModifierDataProvider, Boolean)`

- `Void Refresh(PlayerBuildingRoom)`

- `Void _Refresh(String, PlayerBuildingDIYSolution)`

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
// Namespace : Torappu.Building.DIY
public class DIYRoomModifierManager : IDIYRoomModifierManager, IDIYRoomModifierProvider
{
	private List`1 m_listeners; // 0x10
	private List`1 m_DIYRoomModifiers; // 0x18
	private IDIYRoomModifierDataProvider m_dataProvider; // 0x20
	private Boolean m_diyRoomModifierDataDirty; // 0x28


	// RVA: 0x37c7f8c VA: 0x7595ddff8c
	public Void SetDataDirty() { }
	// RVA: 0x37c7f98 VA: 0x7595ddff98
	public Void Setup(IDIYRoomModifierDataProvider db, Boolean ignoreRefresh) { }
	// RVA: 0x37c8038 VA: 0x7595de0038
	public Void Refresh(PlayerBuildingRoom playerBuildingRoom) { }
	// RVA: 0x37c85fc VA: 0x7595de05fc
	private Void _Refresh(String slotId, PlayerBuildingDIYSolution diySolution) { }
	// RVA: 0x37c8af8 VA: 0x7595de0af8
	public Void AddDIYRoomModifier(DIYRoomModifier modifier) { }
	// RVA: 0x37c8ccc VA: 0x7595de0ccc
	public Void RemoveDIYRoomModifier(DIYRoomModifier modifier) { }
	// RVA: 0x37c840c VA: 0x7595de040c
	public Void ClearDIYRoomModifier() { }
	// RVA: 0x37c8e50 VA: 0x7595de0e50
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37c8f98 VA: 0x7595de0f98
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37c90d0 VA: 0x7595de10d0
	public Void RegisterListener(IDIYRoomModifierProviderListener listener) { }
	// RVA: 0x37c91b8 VA: 0x7595de11b8
	public Void UnregisterListener(IDIYRoomModifierProviderListener listener) { }
	// RVA: 0x37c9248 VA: 0x7595de1248
	public Void .ctor() { }
}
```