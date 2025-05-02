# Act24sideMissionViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String m_actId`

- `Int32 completeMission`

- `Int32 totalMission`

- `Int32 pos`

- `Int32 sequenceNum`

- `Boolean haveMissionCanReceive`


## Methods

- `Void InitData(String, String)`

- `Void UpdateData(Boolean)`

- `Int32 _MissionComparer(Act24sideMissionObjViewModel, Act24sideMissionObjViewModel)`

- `Void _CalculateCompleteAndReceiveMissionNum()`

- `Int32 <InitData>b__8_0(Act24sideMissionObjViewModel, Act24sideMissionObjViewModel)`

- `Int32 <UpdateData>b__9_0(Act24sideMissionObjViewModel, Act24sideMissionObjViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionViewModel : IHotfixable
{
	private String m_actId; // 0x10
	private List`1 missionData; // 0x18
	public Int32 completeMission; // 0x20
	public Int32 totalMission; // 0x24
	public Int32 pos; // 0x28
	public Int32 sequenceNum; // 0x2c
	public Boolean haveMissionCanReceive; // 0x30
	public List`1 act24SideMissionObjViewModelList; // 0x38
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0__MissionComparer; // 0x10
	private static DelegateBridge __Hotfix0__CalculateCompleteAndReceiveMissionNum; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32b65bc VA: 0x75958ce5bc
	public Void InitData(String actId, String clickMissionId) { }
	// RVA: 0x32b69d4 VA: 0x75958ce9d4
	public Void UpdateData(Boolean ifSort) { }
	// RVA: 0x32bff14 VA: 0x75958d7f14
	private Int32 _MissionComparer(Act24sideMissionObjViewModel x, Act24sideMissionObjViewModel y) { }
	// RVA: 0x32bfbfc VA: 0x75958d7bfc
	private Void _CalculateCompleteAndReceiveMissionNum() { }
	// RVA: 0x32c0024 VA: 0x75958d8024
	public Void .ctor() { }
	// RVA: 0x32c00e8 VA: 0x75958d80e8
	private Int32 <InitData>b__8_0(Act24sideMissionObjViewModel x, Act24sideMissionObjViewModel y) { }
	// RVA: 0x32c00ec VA: 0x75958d80ec
	private Int32 <UpdateData>b__9_0(Act24sideMissionObjViewModel x, Act24sideMissionObjViewModel y) { }
}
```