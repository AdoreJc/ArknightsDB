# FireworkCraftModel

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `Int32 enterSeqNum`

- `EditStatus status`

- `String selectedStageId`

- `String selectedZoneId`

- `String currentAnimalId`

- `String currentAnimalIconId`

- `String currentAnimalNameId`

- `String currentAnimalBuffDesc`

- `Boolean hasNewAnimalMark`

- `FireworkPlateGroupModel plateGroupViewModel`


## Properties

- `CraftStageInfoModel selectedStageModel`


## Methods

- `CraftStageInfoModel get_selectedStageModel()`

- `Void _LoadFireworkData(FireworkData)`

- `Boolean _CheckIfHaveAnimalNewTrack(List`1)`

- `Void LoadData(Input)`

- `Void RefreshData()`

- `Void SetEditStatus(EditStatus)`

- `Void SelectStage(String)`

- `Void SelectZone(String, Boolean)`

- `Boolean IsZoneLocked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftModel : IHotfixable
{
	public Int32 enterSeqNum; // 0x10
	public EditStatus status; // 0x14
	public ListDict`2 zoneDict; // 0x18
	public String selectedStageId; // 0x20
	public String selectedZoneId; // 0x28
	public String currentAnimalId; // 0x30
	public String currentAnimalIconId; // 0x38
	public String currentAnimalNameId; // 0x40
	public String currentAnimalBuffDesc; // 0x48
	public Boolean hasNewAnimalMark; // 0x50
	public List`1 platePieceList; // 0x58
	public FireworkPlateGroupModel plateGroupViewModel; // 0x60
	private Dictionary`2 m_stageDict; // 0x68
	private static DelegateBridge __Hotfix0_get_selectedStageModel; // 0x0
	private static DelegateBridge __Hotfix0__LoadFireworkData; // 0x8
	private static DelegateBridge __Hotfix0__CheckIfHaveAnimalNewTrack; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_RefreshData; // 0x20
	private static DelegateBridge __Hotfix0_SetEditStatus; // 0x28
	private static DelegateBridge __Hotfix0_SelectStage; // 0x30
	private static DelegateBridge __Hotfix0_SelectZone; // 0x38
	private static DelegateBridge __Hotfix0_IsZoneLocked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public CraftStageInfoModel selectedStageModel { get; }

	// RVA: 0x2903f14 VA: 0x7594f1bf14
	public CraftStageInfoModel get_selectedStageModel() { }
	// RVA: 0x2903fbc VA: 0x7594f1bfbc
	private Void _LoadFireworkData(FireworkData fireworkData) { }
	// RVA: 0x290439c VA: 0x7594f1c39c
	private Boolean _CheckIfHaveAnimalNewTrack(List`1 animalIdList) { }
	// RVA: 0x29044e4 VA: 0x7594f1c4e4
	public Void LoadData(Input input) { }
	// RVA: 0x29053b8 VA: 0x7594f1d3b8
	public Void RefreshData() { }
	// RVA: 0x290533c VA: 0x7594f1d33c
	public Void SetEditStatus(EditStatus status) { }
	// RVA: 0x2905268 VA: 0x7594f1d268
	public Void SelectStage(String stageId) { }
	// RVA: 0x2905178 VA: 0x7594f1d178
	public Void SelectZone(String zoneId, Boolean useFirstLockedStage) { }
	// RVA: 0x29055a8 VA: 0x7594f1d5a8
	public Boolean IsZoneLocked(String zoneId) { }
	// RVA: 0x29056a0 VA: 0x7594f1d6a0
	public Void .ctor() { }
}
```