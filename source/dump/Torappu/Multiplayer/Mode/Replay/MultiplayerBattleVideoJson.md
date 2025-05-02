# MultiplayerBattleVideoJson

**Namespace:** `Torappu.Multiplayer.Mode.Replay`


## Fields

- `String stage_id`

- `Int32 stage_seed`

- `Int32 start_ts`

- `Int32 step_seq`


## Properties

- `Int32 stepCount`


## Methods

- `Int32 get_stepCount()`

- `StepData GetStep(UInt32)`

- `Void ReadBattleInfo(BattleInfo)`

- `Void ReadTeamInfo(TeamInfo)`

- `Int32 _GetCheckSeq(UInt32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer.Mode.Replay
public class MultiplayerBattleVideoJson : IMultiplayerBattleVideo
{
	public String stage_id; // 0x10
	public Int32 stage_seed; // 0x18
	public Int32 start_ts; // 0x1c
	public Dictionary`2 players; // 0x20
	public Int32 step_seq; // 0x28
	public JsonStep[] arr_step; // 0x30
	public UInt32[] arr_check_seq; // 0x38

	public Int32 stepCount { get; }

	// RVA: 0x35aaef0 VA: 0x7595bc2ef0
	public Int32 get_stepCount() { }
	// RVA: 0x35aaef8 VA: 0x7595bc2ef8
	public StepData GetStep(UInt32 stepSeq) { }
	// RVA: 0x35ab270 VA: 0x7595bc3270
	public Void ReadBattleInfo(BattleInfo bi) { }
	// RVA: 0x35ab6e4 VA: 0x7595bc36e4
	public Void ReadTeamInfo(TeamInfo ti) { }
	// RVA: 0x35ab21c VA: 0x7595bc321c
	private Int32 _GetCheckSeq(UInt32 stepSeq) { }
	// RVA: 0x35ab6e8 VA: 0x7595bc36e8
	public static MultiplayerBattleVideoJson CreateFromFile(String jsonPath) { }
	// RVA: 0x35aab0c VA: 0x7595bc2b0c
	public static MultiplayerBattleVideoJson CreateFromJsonStr(String jsonContent) { }
	// RVA: 0x35ab768 VA: 0x7595bc3768
	public Void .ctor() { }
}
```