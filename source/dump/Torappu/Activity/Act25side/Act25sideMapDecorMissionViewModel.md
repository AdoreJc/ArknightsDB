# Act25sideMapDecorMissionViewModel

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `String areaId`

- `String missionId`

- `String missionDesc`

- `Int32 totalProgress`

- `Int32 currProgress`

- `MissionState missionState`

- `String areaName`


## Properties

- `Boolean isCompleted`


## Methods

- `Boolean get_isCompleted()`

- `Void LoadData(String, String, Mission, Act25SideData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideMapDecorMissionViewModel : IHotfixable
{
	public String areaId; // 0x10
	public String missionId; // 0x18
	public String missionDesc; // 0x20
	public Int32 totalProgress; // 0x28
	public Int32 currProgress; // 0x2c
	public MissionState missionState; // 0x30
	public String areaName; // 0x38
	private static DelegateBridge __Hotfix0_get_isCompleted; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isCompleted { get; }

	// RVA: 0x3288e94 VA: 0x75958a0e94
	public Boolean get_isCompleted() { }
	// RVA: 0x3288f04 VA: 0x75958a0f04
	public Void LoadData(String areaId, String missionId, Mission playerMission, Act25SideData tableData) { }
	// RVA: 0x3289074 VA: 0x75958a1074
	public Void .ctor() { }
}
```