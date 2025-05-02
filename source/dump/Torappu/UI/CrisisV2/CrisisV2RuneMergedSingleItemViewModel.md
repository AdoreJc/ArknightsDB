# CrisisV2RuneMergedSingleItemViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2MapDetailData m_mapDetailData`

- `String m_groupId`

- `Int32 m_groupSortId`

- `Int32 m_mergedPoint`

- `String m_description`


## Methods

- `String GetDesc()`

- `Int32 GetPoint()`

- `String GetTutorialHighLightKey()`

- `Void LoadData(String, List`1, CrisisV2MapDetailData)`

- `Int32 CompareTo(CrisisV2RuneMergedSingleItemViewModel)`

- `CrisisV2RuneData _TryGetRuneData(String)`

- `Int32 _GetGroupSortId()`

- `String _GetGroupDescFormat()`

- `String _GetDescription()`

- `Void _ResetData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RuneMergedSingleItemViewModel : ICrisisV2RuneSingleItemInfo, IHotfixable, IComparable`1
{
	private CrisisV2MapDetailData m_mapDetailData; // 0x10
	private List`1 m_runeIdList; // 0x18
	private String m_groupId; // 0x20
	private Int32 m_groupSortId; // 0x28
	private Int32 m_mergedPoint; // 0x2c
	private String m_description; // 0x30
	private static DelegateBridge __Hotfix0_GetDesc; // 0x0
	private static DelegateBridge __Hotfix0_GetPoint; // 0x8
	private static DelegateBridge __Hotfix0_GetTutorialHighLightKey; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_CompareTo; // 0x20
	private static DelegateBridge __Hotfix0__TryGetRuneData; // 0x28
	private static DelegateBridge __Hotfix0__GetGroupSortId; // 0x30
	private static DelegateBridge __Hotfix0__GetGroupDescFormat; // 0x38
	private static DelegateBridge __Hotfix0__GetDescription; // 0x40
	private static DelegateBridge __Hotfix0__ResetData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2bf6428 VA: 0x759520e428
	public String GetDesc() { }
	// RVA: 0x2bf6490 VA: 0x759520e490
	public Int32 GetPoint() { }
	// RVA: 0x2bf64f8 VA: 0x759520e4f8
	public String GetTutorialHighLightKey() { }
	// RVA: 0x2bf657c VA: 0x759520e57c
	public Void LoadData(String runeGroupId, List`1 runesInGroupList, CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bf6f90 VA: 0x759520ef90
	public Int32 CompareTo(CrisisV2RuneMergedSingleItemViewModel other) { }
	// RVA: 0x2bf68a0 VA: 0x759520e8a0
	private CrisisV2RuneData _TryGetRuneData(String runeId) { }
	// RVA: 0x2bf69d0 VA: 0x759520e9d0
	private Int32 _GetGroupSortId() { }
	// RVA: 0x2bf7040 VA: 0x759520f040
	private String _GetGroupDescFormat() { }
	// RVA: 0x2bf6aa4 VA: 0x759520eaa4
	private String _GetDescription() { }
	// RVA: 0x2bf6798 VA: 0x759520e798
	private Void _ResetData() { }
	// RVA: 0x2bf7130 VA: 0x759520f130
	public Void .ctor() { }
}
```