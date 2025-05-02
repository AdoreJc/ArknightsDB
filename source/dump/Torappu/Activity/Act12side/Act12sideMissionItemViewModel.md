# Act12sideMissionItemViewModel

**Namespace:** `Torappu.Activity.Act12side`


## Fields

- `MissionDescInfo missionDescInfo`

- `MissionData missionData`

- `String activityId`

- `MissionHoldingState m_missionState`

- `Int32 m_target`

- `Int32 m_progress`


## Properties

- `Int32 target`

- `Int32 progress`

- `Single normalizeProgress`

- `ActZoneClass zoneClass`

- `Boolean isCompleted`


## Methods

- `Int32 get_target()`

- `Int32 get_progress()`

- `Single get_normalizeProgress()`

- `ActZoneClass get_zoneClass()`

- `Boolean get_isCompleted()`

- `Boolean NeedLock()`

- `Boolean IsUnlock()`

- `Void ResetStatus()`

- `Void RefreshStatus(MissionHoldingState, Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side
public class Act12sideMissionItemViewModel : IHotfixable
{
	public MissionDescInfo missionDescInfo; // 0x10
	public MissionData missionData; // 0x18
	public String activityId; // 0x20
	private MissionHoldingState m_missionState; // 0x28
	private Int32 m_target; // 0x2c
	private Int32 m_progress; // 0x30
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_get_progress; // 0x8
	private static DelegateBridge __Hotfix0_get_normalizeProgress; // 0x10
	private static DelegateBridge __Hotfix0_get_zoneClass; // 0x18
	private static DelegateBridge __Hotfix0_get_isCompleted; // 0x20
	private static DelegateBridge __Hotfix0_NeedLock; // 0x28
	private static DelegateBridge __Hotfix0_IsUnlock; // 0x30
	private static DelegateBridge __Hotfix0_ResetStatus; // 0x38
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 target { get; }
	public Int32 progress { get; }
	public Single normalizeProgress { get; }
	public ActZoneClass zoneClass { get; }
	public Boolean isCompleted { get; }

	// RVA: 0x344ab5c VA: 0x7595a62b5c
	public Int32 get_target() { }
	// RVA: 0x344abc4 VA: 0x7595a62bc4
	public Int32 get_progress() { }
	// RVA: 0x344ac2c VA: 0x7595a62c2c
	public Single get_normalizeProgress() { }
	// RVA: 0x344aca0 VA: 0x7595a62ca0
	public ActZoneClass get_zoneClass() { }
	// RVA: 0x344ad14 VA: 0x7595a62d14
	public Boolean get_isCompleted() { }
	// RVA: 0x344ad84 VA: 0x7595a62d84
	public Boolean NeedLock() { }
	// RVA: 0x344ae24 VA: 0x7595a62e24
	public Boolean IsUnlock() { }
	// RVA: 0x344aeb4 VA: 0x7595a62eb4
	public Void ResetStatus() { }
	// RVA: 0x344af28 VA: 0x7595a62f28
	public Void RefreshStatus(MissionHoldingState state, Int32 target, Int32 progress) { }
	// RVA: 0x344afc4 VA: 0x7595a62fc4
	public Void .ctor() { }
}
```