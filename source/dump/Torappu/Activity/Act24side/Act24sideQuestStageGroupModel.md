# Act24sideQuestStageGroupModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Int32 m_rank`

- `String m_actId`


## Properties

- `Int32 rank`


## Methods

- `Int32 get_rank()`

- `Void LoadData(String, Int32)`

- `Boolean IsUrgent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideQuestStageGroupModel : IHotfixable
{
	private Int32 m_rank; // 0x10
	private String m_actId; // 0x18
	private List`1 m_questItemList; // 0x20
	private static DelegateBridge __Hotfix0_get_rank; // 0x0
	private static DelegateBridge __Hotfix0_get_questItemList; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_IsUrgent; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Int32 rank { get; }
	public List`1 questItemList { get; }

	// RVA: 0x32df2b4 VA: 0x75958f72b4
	public Int32 get_rank() { }
	// RVA: 0x32df31c VA: 0x75958f731c
	public List`1 get_questItemList() { }
	// RVA: 0x32df384 VA: 0x75958f7384
	public Void LoadData(String actId, Int32 stageRank) { }
	// RVA: 0x32df460 VA: 0x75958f7460
	public Boolean IsUrgent() { }
	// RVA: 0x32df558 VA: 0x75958f7558
	public Void .ctor() { }
}
```