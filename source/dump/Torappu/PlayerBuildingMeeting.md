# PlayerBuildingMeeting

**Namespace:** `Torappu`


## Fields

- `PlayerBuildingMeetingBuff buff`

- `Int32 state`

- `Int32 processPoint`

- `Single speed`

- `PlayerBuildingMeetingSocialReward socialReward`

- `Int32 received`

- `PlayerBuildingMeetingInfoShareState infoShare`

- `DateTime lastUpdateTime`

- `PlayerBuildingMeetingClue dailyReward`

- `PlayerBuildingMessageLeave messageLeave`

- `PlayerBuildingDIYSolution diySolution`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerBuildingMeeting
{
	public List`1 visitedUser; // 0x10
	public PlayerBuildingMeetingBuff buff; // 0x18
	public Int32 state; // 0x20
	public Int32 processPoint; // 0x24
	public Single speed; // 0x28
	public List`1 ownStock; // 0x30
	public List`1 receiveStock; // 0x38
	public Dictionary`2 board; // 0x40
	public PlayerBuildingMeetingSocialReward socialReward; // 0x48
	public Int32 received; // 0x50
	public PlayerBuildingMeetingInfoShareState infoShare; // 0x58
	public DateTime lastUpdateTime; // 0x60
	public PlayerBuildingMeetingClue dailyReward; // 0x68
	public List`1 presetQueue; // 0x70
	public PlayerBuildingMessageLeave messageLeave; // 0x78
	public PlayerBuildingDIYSolution diySolution; // 0x80


	// RVA: 0x32d7004 VA: 0x75958ef004
	public Void .ctor() { }
}
```