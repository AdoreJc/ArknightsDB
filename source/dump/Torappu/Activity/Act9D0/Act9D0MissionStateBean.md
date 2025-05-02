# Act9D0MissionStateBean

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Int32 <completedMissionCount>k__BackingField`

- `Boolean _hasMissionCanClaim`


## Properties

- `Int32 completedMissionCount`

- `Int32 missionCount`

- `Boolean hasMissionCanClaim`


## Methods

- `Int32 get_completedMissionCount()`

- `Void set_completedMissionCount(Int32)`

- `Int32 get_missionCount()`

- `Boolean get_hasMissionCanClaim()`

- `Void LoadData()`

- `Boolean _CheckHasMissionCanClaim()`

- `Int32 _CompareMission(MissionViewModel, MissionViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0MissionStateBean : IStateBean, IHotfixable
{
	public List`1 missionModelList; // 0x10
	private Int32 <completedMissionCount>k__BackingField; // 0x18
	private Boolean _hasMissionCanClaim; // 0x1c
	private static DelegateBridge __Hotfix0_get_subMissionList; // 0x0
	private static DelegateBridge __Hotfix0_get_notSubMissionList; // 0x8
	private static DelegateBridge __Hotfix0_get_completedMissionCount; // 0x10
	private static DelegateBridge __Hotfix0_set_completedMissionCount; // 0x18
	private static DelegateBridge __Hotfix0_get_missionCount; // 0x20
	private static DelegateBridge __Hotfix0_get_hasMissionCanClaim; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0__CheckHasMissionCanClaim; // 0x38
	private static DelegateBridge __Hotfix0__CompareMission; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public List`1 subMissionList { get; }
	public List`1 notSubMissionList { get; }
	public Int32 completedMissionCount { get; set; }
	public Int32 missionCount { get; }
	public Boolean hasMissionCanClaim { get; }

	// RVA: 0x31ac898 VA: 0x75957c4898
	public List`1 get_subMissionList() { }
	// RVA: 0x31acaec VA: 0x75957c4aec
	public List`1 get_notSubMissionList() { }
	// RVA: 0x31a8560 VA: 0x75957c0560
	public Int32 get_completedMissionCount() { }
	// RVA: 0x31acce0 VA: 0x75957c4ce0
	private Void set_completedMissionCount(Int32 value) { }
	// RVA: 0x31a85c8 VA: 0x75957c05c8
	public Int32 get_missionCount() { }
	// RVA: 0x31a8648 VA: 0x75957c0648
	public Boolean get_hasMissionCanClaim() { }
	// RVA: 0x31acd5c VA: 0x75957c4d5c
	public Void LoadData() { }
	// RVA: 0x31ad1a4 VA: 0x75957c51a4
	private Boolean _CheckHasMissionCanClaim() { }
	// RVA: 0x31ad298 VA: 0x75957c5298
	private Int32 _CompareMission(MissionViewModel lhs, MissionViewModel rhs) { }
	// RVA: 0x31ad394 VA: 0x75957c5394
	public Void .ctor() { }
}
```