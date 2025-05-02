# ActMultiV3TrainingRoomViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String actId`

- `Int32 initSeqNum`

- `ActMultiV3MapModeType selectedModeType`


## Methods

- `ActMultiV3MapModeData _GetMapModeDataByModeType(ActMultiV3MapModeType, Dictionary`2)`

- `Void LoadData(String)`

- `Void SetSelectedMode(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3TrainingRoomViewModel : IHotfixable
{
	public String actId; // 0x10
	public Int32 initSeqNum; // 0x18
	public ListDict`2 modeList; // 0x20
	public Dictionary`2 modeStarCount; // 0x28
	public ActMultiV3MapModeType selectedModeType; // 0x30
	private static DelegateBridge __Hotfix0__GetMapModeDataByModeType; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedMode; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31551ac VA: 0x759576d1ac
	private ActMultiV3MapModeData _GetMapModeDataByModeType(ActMultiV3MapModeType modeType, Dictionary`2 mapModeData) { }
	// RVA: 0x315377c VA: 0x759576b77c
	public Void LoadData(String actId) { }
	// RVA: 0x3153eb4 VA: 0x759576beb4
	public Void SetSelectedMode(Int32 mode) { }
	// RVA: 0x315538c VA: 0x759576d38c
	public Void .ctor() { }
}
```