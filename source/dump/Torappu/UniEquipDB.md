# UniEquipDB

**Namespace:** `Torappu`


## Methods

- `UniEquipTimeInfo GetNearestStageTimeData(Int64)`

- `Boolean IsValidEquipForChar(String, String)`

- `SubProfessionData GetSubProfessionData(String)`

- `UniEquipMissionData GetEquipMissionData(String)`

- `Boolean HasAnyEquipInTable(CharQuery)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class UniEquipDB : ConstTable`2
{
	private static DelegateBridge __Hotfix0_GetNearestStageTimeData; // 0x0
	private static DelegateBridge __Hotfix0_LoadCharEquipViewModelList; // 0x8
	private static DelegateBridge __Hotfix0_LoadCharEquipTypeDataDict; // 0x10
	private static DelegateBridge __Hotfix0_GetCharEquipList; // 0x18
	private static DelegateBridge __Hotfix0_IsValidEquipForChar; // 0x20
	private static DelegateBridge __Hotfix0_GetSubProfessionData; // 0x28
	private static DelegateBridge __Hotfix0_GetEquipMissionData; // 0x30
	private static DelegateBridge __Hotfix0_HasAnyEquipInTable; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x32c62e8 VA: 0x75958de2e8
	public UniEquipTimeInfo GetNearestStageTimeData(Int64 timeStamp) { }
	// RVA: 0x32c6430 VA: 0x75958de430
	public List`1 LoadCharEquipViewModelList(CharQuery query) { }
	// RVA: 0x32c66cc VA: 0x75958de6cc
	public Dictionary`2 LoadCharEquipTypeDataDict(CharQuery query) { }
	// RVA: 0x32c695c VA: 0x75958de95c
	public List`1 GetCharEquipList(CharQuery query) { }
	// RVA: 0x32c6aa4 VA: 0x75958deaa4
	public Boolean IsValidEquipForChar(String uniEquipId, String charId) { }
	// RVA: 0x32c6bc0 VA: 0x75958debc0
	public SubProfessionData GetSubProfessionData(String id) { }
	// RVA: 0x32c6c90 VA: 0x75958dec90
	public UniEquipMissionData GetEquipMissionData(String missionId) { }
	// RVA: 0x32c6d60 VA: 0x75958ded60
	public Boolean HasAnyEquipInTable(CharQuery charQuery) { }
	// RVA: 0x32c6e24 VA: 0x75958dee24
	public Void .ctor() { }
}
```