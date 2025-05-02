# ActMultiV3ManualMissionModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int32 completedMissionCount`

- `Boolean hasUnconfirmedMission`

- `Int32 loadSeqNum`


## Methods

- `Void InitData(String)`

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualMissionModel : IHotfixable
{
	public List`1 missionModelList; // 0x10
	public Int32 completedMissionCount; // 0x18
	public Boolean hasUnconfirmedMission; // 0x1c
	public Int32 loadSeqNum; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3121794 VA: 0x7595739794
	public Void InitData(String actId) { }
	// RVA: 0x3121f3c VA: 0x7595739f3c
	public Void LoadData(String actId) { }
	// RVA: 0x31226c0 VA: 0x759573a6c0
	public Void .ctor() { }
}
```