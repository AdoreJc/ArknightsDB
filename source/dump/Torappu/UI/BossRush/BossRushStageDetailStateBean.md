# BossRushStageDetailStateBean

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String stageGroupId`

- `BossRushStageDetailProperty viewProperty`


## Methods

- `Void LoadData(String, String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailStateBean : IStateBean, IHotfixable
{
	public String stageGroupId; // 0x10
	public BossRushStageDetailProperty viewProperty; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2e77edc VA: 0x759548fedc
	public Void LoadData(String actId, String selectStageId, String selectTeam) { }
	// RVA: 0x2e7822c VA: 0x759549022c
	public Void .ctor() { }
}
```