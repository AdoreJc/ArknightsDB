# Act24sideMissionObjViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String actId`

- `String missionId`

- `String missionTitle`

- `String missionDesc`

- `String missionClient`

- `String missionClientDesc`

- `Int32 nowSchedule`

- `Int32 totalSchedule`

- `Int32 sortId`

- `MissionState missionState`

- `MissionType missionType`


## Methods

- `Void LoadData(MissionData, String)`

- `Void UpdateState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionObjViewModel : IHotfixable
{
	public String actId; // 0x10
	public String missionId; // 0x18
	public String missionTitle; // 0x20
	public String missionDesc; // 0x28
	public String missionClient; // 0x30
	public String missionClientDesc; // 0x38
	public Int32 nowSchedule; // 0x40
	public Int32 totalSchedule; // 0x44
	public Int32 sortId; // 0x48
	public MissionState missionState; // 0x4c
	public MissionType missionType; // 0x50
	public List`1 normalRewardList; // 0x58
	public List`1 actRewardList; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32bf520 VA: 0x75958d7520
	public Void LoadData(MissionData missionData, String actId) { }
	// RVA: 0x32bfdac VA: 0x75958d7dac
	public Void UpdateState() { }
	// RVA: 0x32bf40c VA: 0x75958d740c
	public Void .ctor() { }
}
```