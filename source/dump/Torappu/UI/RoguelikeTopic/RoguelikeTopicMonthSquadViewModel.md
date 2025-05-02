# RoguelikeTopicMonthSquadViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `String topicId`

- `String bpPointItemId`

- `ItemType bpPointItemType`

- `String bpPointItemName`

- `String tipButtonName`

- `String descSquadName`

- `Boolean isBpMax`

- `Boolean isFullStored`

- `MonthSquadCardSwitchDirection switchDirection`

- `String selectedMonthSquad`

- `String currUpdateSquad`

- `Int64 currUpdateSquadEndTime`

- `Boolean currUpdateSquadReceivedAward`


## Methods

- `Void LoadData(String, RoguelikeTopicModeViewModel)`

- `Void SetCurrentMonthSquadId(String)`

- `Void SwitchMonthSquadList(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthSquadViewModel : IHotfixable
{
	public String topicId; // 0x10
	public ListDict`2 monthSquadList; // 0x18
	public String bpPointItemId; // 0x20
	public ItemType bpPointItemType; // 0x28
	public String bpPointItemName; // 0x30
	public String tipButtonName; // 0x38
	public String descSquadName; // 0x40
	public Boolean isBpMax; // 0x48
	public Boolean isFullStored; // 0x49
	public MonthSquadCardSwitchDirection switchDirection; // 0x4c
	public String selectedMonthSquad; // 0x50
	public String currUpdateSquad; // 0x58
	public Int64 currUpdateSquadEndTime; // 0x60
	public Boolean currUpdateSquadReceivedAward; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetCurrentMonthSquadId; // 0x8
	private static DelegateBridge __Hotfix0_SwitchMonthSquadList; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2679dcc VA: 0x7594c91dcc
	public Void LoadData(String topic, RoguelikeTopicModeViewModel outerModel) { }
	// RVA: 0x267adcc VA: 0x7594c92dcc
	public Void SetCurrentMonthSquadId(String monthSquadId) { }
	// RVA: 0x267aec8 VA: 0x7594c92ec8
	public Void SwitchMonthSquadList(Int32 delta) { }
	// RVA: 0x267b360 VA: 0x7594c93360
	public Void .ctor() { }
}
```