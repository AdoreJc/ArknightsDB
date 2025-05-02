# BuildingPayloadGetMessageBoardContentResponse

**Namespace:** `Torappu`


## Fields

- `Int32 todayVisit`

- `Int32 weeklyVisit`

- `Int32 lastWeekVisit`

- `Int32 lastWeekSpReward`

- `Int64 lastShowTs`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuildingPayloadGetMessageBoardContentResponse : PlayerDeltaResponse
{
	public List`1 thisWeekVisitors; // 0x28
	public List`1 lastWeekVisitors; // 0x30
	public Int32 todayVisit; // 0x38
	public Int32 weeklyVisit; // 0x3c
	public Int32 lastWeekVisit; // 0x40
	public Int32 lastWeekSpReward; // 0x44
	public Int64 lastShowTs; // 0x48


	// RVA: 0x32c9e70 VA: 0x75958e1e70
	public Void .ctor() { }
}
```