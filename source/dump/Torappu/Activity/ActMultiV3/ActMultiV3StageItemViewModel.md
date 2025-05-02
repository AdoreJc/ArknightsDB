# ActMultiV3StageItemViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Boolean isRandom`

- `String stageId`

- `String stageCode`

- `Int32 star`

- `Int64 exScore`

- `Boolean isEmptyScore`

- `Int32 sortId`

- `ActMultiV3MapDiffType stageDiffType`

- `ActMultiV3MapModeType modeType`

- `String modeName`

- `Int32 modeSortId`

- `String modeId`

- `String actId`

- `String unlockModeId`

- `Int32 unlockModeStarRequirement`

- `Int64 modeOpenTs`

- `Int64 stageOpenTs`

- `String textOpenTime`

- `Boolean isLockedByMode`

- `Boolean isLockedByTime`

- `String lockedByModeToast`

- `Boolean hasTrackpoint`

- `String previewIconId`


## Methods

- `Void LoadRandomData(String, String, ActMultiV3MapModeType, ActMultiV3MapDiffType, ActMultiV3Data)`

- `Void LoadData(String, String, ActMultiV3MapData, ActMultiV3Data, StageInfo)`

- `Int32 CompareTo(ActMultiV3StageItemViewModel)`

- `Void ReloadTrackpointStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageItemViewModel : IHotfixable, IComparable`1
{
	public const String RANDOM_STAGE_ID; // 0x0
	public Boolean isRandom; // 0x10
	public String stageId; // 0x18
	public String stageCode; // 0x20
	public Int32 star; // 0x28
	public Int64 exScore; // 0x30
	public Boolean isEmptyScore; // 0x38
	public Int32 sortId; // 0x3c
	public ActMultiV3MapDiffType stageDiffType; // 0x40
	public ActMultiV3MapModeType modeType; // 0x44
	public String modeName; // 0x48
	public Int32 modeSortId; // 0x50
	public String modeId; // 0x58
	public String actId; // 0x60
	public String unlockModeId; // 0x68
	public Int32 unlockModeStarRequirement; // 0x70
	public Int64 modeOpenTs; // 0x78
	public Int64 stageOpenTs; // 0x80
	public String textOpenTime; // 0x88
	public Boolean isLockedByMode; // 0x90
	public Boolean isLockedByTime; // 0x91
	public String lockedByModeToast; // 0x98
	public Boolean hasTrackpoint; // 0xa0
	public String previewIconId; // 0xa8
	private static DelegateBridge __Hotfix0_LoadRandomData; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge __Hotfix0_ReloadTrackpointStatus; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31508b4 VA: 0x75957688b4
	public Void LoadRandomData(String actId, String modeId, ActMultiV3MapModeType modeType, ActMultiV3MapDiffType diffType, ActMultiV3Data actData) { }
	// RVA: 0x3150c38 VA: 0x7595768c38
	public Void LoadData(String actId, String stageId, ActMultiV3MapData stageData, ActMultiV3Data actData, StageInfo playerStageData) { }
	// RVA: 0x315112c VA: 0x759576912c
	public Int32 CompareTo(ActMultiV3StageItemViewModel other) { }
	// RVA: 0x3150bac VA: 0x7595768bac
	public Void ReloadTrackpointStatus() { }
	// RVA: 0x315122c VA: 0x759576922c
	public Void .ctor() { }
}
```