# ActVecBreakOffenseBattleFinishViewModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `String actId`

- `SquadItemStruct assistSquadData`

- `CharUISkinStruct randomSkin`

- `ActVecBreakOffenseStageData offenseStageData`

- `StageData stageData`

- `VecBreakBattleFinishAnimationType animationType`

- `String playerName`

- `Int64 finishTs`

- `Boolean isUnlockDefense`

- `Boolean isPrevDefenseUnlock`

- `Int32 rewardTokenNum`

- `Boolean isPlayHighHardVoice`


## Properties

- `Boolean isFinalStage`


## Methods

- `Boolean get_isFinalStage()`

- `Void LoadData(Input)`

- `Void _UpdateBuffData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class ActVecBreakOffenseBattleFinishViewModel : IHotfixable
{
	public String actId; // 0x10
	public SquadItemStruct[] squadDatas; // 0x18
	public SquadItemStruct assistSquadData; // 0x20
	public CharUISkinStruct randomSkin; // 0x30
	public ActVecBreakOffenseStageData offenseStageData; // 0x40
	public StageData stageData; // 0x48
	public VecBreakBattleFinishAnimationType animationType; // 0x50
	public String playerName; // 0x58
	public Int64 finishTs; // 0x60
	public Boolean isUnlockDefense; // 0x68
	public Boolean isPrevDefenseUnlock; // 0x69
	public Int32 rewardTokenNum; // 0x6c
	public Boolean isPlayHighHardVoice; // 0x70
	private List`1 m_buffList; // 0x78
	private static DelegateBridge __Hotfix0_get_defenseBuffList; // 0x0
	private static DelegateBridge __Hotfix0_get_isFinalStage; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0__UpdateBuffData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public List`1 defenseBuffList { get; }
	public Boolean isFinalStage { get; }

	// RVA: 0x22a1ee8 VA: 0x75948b9ee8
	public List`1 get_defenseBuffList() { }
	// RVA: 0x22a1f50 VA: 0x75948b9f50
	public Boolean get_isFinalStage() { }
	// RVA: 0x22a1ffc VA: 0x75948b9ffc
	public Void LoadData(Input input) { }
	// RVA: 0x22a2960 VA: 0x75948ba960
	private Void _UpdateBuffData() { }
	// RVA: 0x22a2c40 VA: 0x75948bac40
	public Void .ctor() { }
}
```