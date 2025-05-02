# RoomPanelInfo

**Namespace:** ` `


## Fields

- `RoomData roomData`

- `RoomLevelConditionCheckingResult checkingResult`

- `Int32 currentCount`


## Properties

- `Boolean isLevelCondSatisfied`

- `Boolean isCountCondSatisfied`


## Methods

- `Boolean get_isLevelCondSatisfied()`

- `Boolean get_isCountCondSatisfied()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoomPanelInfo
{
	public RoomData roomData; // 0x10
	public RoomLevelConditionCheckingResult checkingResult; // 0x18
	public Int32 currentCount; // 0x38

	public Boolean isLevelCondSatisfied { get; }
	public Boolean isCountCondSatisfied { get; }

	// RVA: 0x3d4807c VA: 0x759636007c
	public Boolean get_isLevelCondSatisfied() { }
	// RVA: 0x3d48084 VA: 0x7596360084
	public Boolean get_isCountCondSatisfied() { }
	// RVA: 0x3d480ac VA: 0x75963600ac
	public Void .ctor(RoomData roomData, RoomLevelConditionCheckingResult checkingResult, Int32 currentCount) { }
}
```