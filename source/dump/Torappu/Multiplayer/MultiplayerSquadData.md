# MultiplayerSquadData

**Namespace:** `Torappu.Multiplayer`


## Fields

- `PlayerSide playerSide`

- `String buffId`

- `String uid`

- `Squad squadRawData`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class MultiplayerSquadData
{
	public PlayerSide playerSide; // 0x10
	public List`1 squad; // 0x18
	public String buffId; // 0x20
	public String uid; // 0x28
	public Squad squadRawData; // 0x30


	// RVA: 0x358e02c VA: 0x7595ba602c
	public static MultiplayerSquadData op_Addition(MultiplayerSquadData a, MultiplayerSquadData b) { }
	// RVA: 0x3589ea4 VA: 0x7595ba1ea4
	public Void .ctor() { }
}
```