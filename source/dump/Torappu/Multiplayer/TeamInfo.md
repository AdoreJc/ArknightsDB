# TeamInfo

**Namespace:** `Torappu.Multiplayer`


## Fields

- `String teamID`

- `STTeamStatus teamStatus`

- `Boolean start`


## Properties

- `StageRandomType stageRandomType`

- `String stageID`

- `String ownerID`

- `Int64 endTs`

- `TeamState state`

- `Boolean isMatch`

- `Boolean valid`

- `Boolean isFlipMode`


## Methods

- `StageRandomType get_stageRandomType()`

- `String get_stageID()`

- `String get_ownerID()`

- `Int64 get_endTs()`

- `TeamState get_state()`

- `Boolean get_isMatch()`

- `Boolean get_valid()`

- `Boolean get_isFlipMode()`

- `Void CopyFrom(STTeamStatus)`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class TeamInfo
{
	public String teamID; // 0x10
	public STTeamStatus teamStatus; // 0x18
	public Boolean start; // 0x90
	private ListDict`2 m_cachedSquad; // 0x98

	public StageRandomType stageRandomType { get; }
	public String stageID { get; }
	public String ownerID { get; }
	public Int64 endTs { get; }
	public TeamState state { get; }
	public List`1 players { get; }
	public Boolean isMatch { get; }
	public Boolean valid { get; }
	public Boolean isFlipMode { get; }

	// RVA: 0x358b76c VA: 0x7595ba376c
	public StageRandomType get_stageRandomType() { }
	// RVA: 0x358b774 VA: 0x7595ba3774
	public String get_stageID() { }
	// RVA: 0x358b77c VA: 0x7595ba377c
	public String get_ownerID() { }
	// RVA: 0x358b784 VA: 0x7595ba3784
	public Int64 get_endTs() { }
	// RVA: 0x358b78c VA: 0x7595ba378c
	public TeamState get_state() { }
	// RVA: 0x358b794 VA: 0x7595ba3794
	public List`1 get_players() { }
	// RVA: 0x358b79c VA: 0x7595ba379c
	public Boolean get_isMatch() { }
	// RVA: 0x358b7a8 VA: 0x7595ba37a8
	public Boolean get_valid() { }
	// RVA: 0x358b7c8 VA: 0x7595ba37c8
	public Boolean get_isFlipMode() { }
	// RVA: 0x358b7d0 VA: 0x7595ba37d0
	public Void CopyFrom(STTeamStatus from) { }
	// RVA: 0x358ba54 VA: 0x7595ba3a54
	public Void Clear() { }
	// RVA: 0x358bb10 VA: 0x7595ba3b10
	public Void .ctor() { }
}
```