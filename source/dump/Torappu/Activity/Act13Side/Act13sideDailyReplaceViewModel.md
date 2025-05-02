# Act13sideDailyReplaceViewModel

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Act13sideDailyMissionItemViewModel m_candidateItemModel`

- `Int32 m_agenda`

- `Int32 m_candidatePoolIdx`


## Properties

- `Int32 candidatePoolIdx`

- `Act13sideDailyMissionItemViewModel candidateItemModel`

- `Int32 ownAgenda`

- `Int32 selectItemAgenda`

- `Int32 agendaAfterReplace`


## Methods

- `Int32 get_candidatePoolIdx()`

- `Act13sideDailyMissionItemViewModel get_candidateItemModel()`

- `Int32 get_ownAgenda()`

- `Int32 get_selectItemAgenda()`

- `Int32 get_agendaAfterReplace()`

- `Void SelectItem(Int32, Boolean)`

- `Boolean IsItemSelected(Int32)`

- `Void LoadData(String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyReplaceViewModel : IHotfixable
{
	private List`1 m_boardItemModelList; // 0x10
	private Act13sideDailyMissionItemViewModel m_candidateItemModel; // 0x18
	private HashSet`1 m_selectedIdxSet; // 0x20
	private Int32 m_agenda; // 0x28
	private Int32 m_candidatePoolIdx; // 0x2c
	private static DelegateBridge __Hotfix0_get_candidatePoolIdx; // 0x0
	private static DelegateBridge __Hotfix0_get_boardItemModelList; // 0x8
	private static DelegateBridge __Hotfix0_get_candidateItemModel; // 0x10
	private static DelegateBridge __Hotfix0_get_ownAgenda; // 0x18
	private static DelegateBridge __Hotfix0_get_selectItemAgenda; // 0x20
	private static DelegateBridge __Hotfix0_get_agendaAfterReplace; // 0x28
	private static DelegateBridge __Hotfix0_GetSelectIdxList; // 0x30
	private static DelegateBridge __Hotfix0_SelectItem; // 0x38
	private static DelegateBridge __Hotfix0_IsItemSelected; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 candidatePoolIdx { get; }
	public List`1 boardItemModelList { get; }
	public Act13sideDailyMissionItemViewModel candidateItemModel { get; }
	public Int32 ownAgenda { get; }
	public Int32 selectItemAgenda { get; }
	public Int32 agendaAfterReplace { get; }

	// RVA: 0x343885c VA: 0x7595a5085c
	public Int32 get_candidatePoolIdx() { }
	// RVA: 0x34388c4 VA: 0x7595a508c4
	public List`1 get_boardItemModelList() { }
	// RVA: 0x343892c VA: 0x7595a5092c
	public Act13sideDailyMissionItemViewModel get_candidateItemModel() { }
	// RVA: 0x3438994 VA: 0x7595a50994
	public Int32 get_ownAgenda() { }
	// RVA: 0x34389fc VA: 0x7595a509fc
	public Int32 get_selectItemAgenda() { }
	// RVA: 0x3438be0 VA: 0x7595a50be0
	public Int32 get_agendaAfterReplace() { }
	// RVA: 0x3438c80 VA: 0x7595a50c80
	public Int32[] GetSelectIdxList() { }
	// RVA: 0x3438d00 VA: 0x7595a50d00
	public Void SelectItem(Int32 itemIdx, Boolean isSelect) { }
	// RVA: 0x3438e10 VA: 0x7595a50e10
	public Boolean IsItemSelected(Int32 itemIdx) { }
	// RVA: 0x3438eb0 VA: 0x7595a50eb0
	public Void LoadData(String actId, Int32 candidatePoolIdx) { }
	// RVA: 0x34391d4 VA: 0x7595a511d4
	public Void .ctor() { }
}
```