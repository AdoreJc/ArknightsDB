# PlayerStatus

**Namespace:** ` `


## Fields

- `PlayerRoguelikePlayerState state`

- `Properties property`

- `NodePosition cursor`

- `Status status`

- `String toEnding`

- `Boolean chgEnding`

- `NodeMission nodeMission`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlayerStatus
{
	public PlayerRoguelikePlayerState state; // 0x10
	public Properties property; // 0x18
	public NodePosition cursor; // 0x20
	public List`1 pending; // 0x28
	public List`1 trace; // 0x30
	public Status status; // 0x38
	public String toEnding; // 0x40
	public Boolean chgEnding; // 0x48
	public List`1 innerMission; // 0x50
	public NodeMission nodeMission; // 0x58
	public Dictionary`2 zoneReward; // 0x60
	public Dictionary`2 traderReturn; // 0x68


	// RVA: 0x32d9418 VA: 0x75958f1418
	public Void .ctor() { }
}
```