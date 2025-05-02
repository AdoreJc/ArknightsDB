# Act12D6RelicHandBookStateBean

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Int32 m_gotCount`

- `Boolean m_inited`


## Properties

- `Int32 RelicCount`


## Methods

- `Int32 get_RelicCount()`

- `Void LoadData(Boolean)`

- `Void SortData(eRelicSortType)`

- `PlayerRelicHandBookData GetPlayerRelicData(String)`

- `Void SetRelicRead(String)`

- `Boolean _GenPlayerRelicGotStatus(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6RelicHandBookStateBean : IStateBean, IHotfixable
{
	public List`1 relicDataList; // 0x10
	private ListDict`2 m_relicDataDict; // 0x18
	private Dictionary`2 m_playerRelicDict; // 0x20
	public List`1 sortedRelicDataList; // 0x28
	private Int32 m_gotCount; // 0x30
	private Boolean m_inited; // 0x34
	private static DelegateBridge __Hotfix0_get_RelicCount; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SortData; // 0x10
	private static DelegateBridge __Hotfix0_GetPlayerRelicData; // 0x18
	private static DelegateBridge __Hotfix0_SetRelicRead; // 0x20
	private static DelegateBridge __Hotfix0__GenPlayerRelicGotStatus; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 RelicCount { get; }

	// RVA: 0x34788e4 VA: 0x7595a908e4
	public Int32 get_RelicCount() { }
	// RVA: 0x347de24 VA: 0x7595a95e24
	public Void LoadData(Boolean force) { }
	// RVA: 0x347e57c VA: 0x7595a9657c
	public Void SortData(eRelicSortType sortType) { }
	// RVA: 0x3478de8 VA: 0x7595a90de8
	public PlayerRelicHandBookData GetPlayerRelicData(String relicId) { }
	// RVA: 0x347e940 VA: 0x7595a96940
	public Void SetRelicRead(String relicId) { }
	// RVA: 0x347e470 VA: 0x7595a96470
	private Boolean _GenPlayerRelicGotStatus(String relicId) { }
	// RVA: 0x347ea8c VA: 0x7595a96a8c
	public Void .ctor() { }
}
```