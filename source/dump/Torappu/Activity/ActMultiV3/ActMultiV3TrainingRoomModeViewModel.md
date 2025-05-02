# ActMultiV3TrainingRoomModeViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String modeId`

- `ActMultiV3MapModeType modeType`

- `String modeTypeName`

- `Int64 modeOpenTs`

- `String unlockModeId`

- `Int32 unlockModeStar`

- `Int32 sortId`

- `Boolean isNormalMode`

- `String modeColor`

- `Boolean lockedByTime`

- `Boolean lockedByStar`

- `String stageId`


## Properties

- `Boolean locked`


## Methods

- `Boolean get_locked()`

- `Int32 CompareTo(ActMultiV3TrainingRoomModeViewModel)`

- `Void LoadTrainingStageData(ActMultiV3Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3TrainingRoomModeViewModel : IHotfixable, IComparable`1
{
	public String modeId; // 0x10
	public ActMultiV3MapModeType modeType; // 0x18
	public String modeTypeName; // 0x20
	public Int64 modeOpenTs; // 0x28
	public String unlockModeId; // 0x30
	public Int32 unlockModeStar; // 0x38
	public Int32 sortId; // 0x3c
	public Boolean isNormalMode; // 0x40
	public String modeColor; // 0x48
	public Boolean lockedByTime; // 0x50
	public Boolean lockedByStar; // 0x51
	public String stageId; // 0x58
	private static DelegateBridge __Hotfix0_get_locked; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge __Hotfix0_LoadTrainingStageData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean locked { get; }

	// RVA: 0x3152cd0 VA: 0x759576acd0
	public Boolean get_locked() { }
	// RVA: 0x3154f34 VA: 0x759576cf34
	public Int32 CompareTo(ActMultiV3TrainingRoomModeViewModel other) { }
	// RVA: 0x3155020 VA: 0x759576d020
	public Void LoadTrainingStageData(ActMultiV3Data actData) { }
	// RVA: 0x315513c VA: 0x759576d13c
	public Void .ctor() { }
}
```