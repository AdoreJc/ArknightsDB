# PlayerTroop

**Namespace:** `Torappu`


## Fields

- `Int32 troopCapacity`

- `Int32 curSquadCount`

- `Int32 curCharInstCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerTroop
{
	public Int32 troopCapacity; // 0x10
	public Int32 curSquadCount; // 0x14
	public Int32 curCharInstCount; // 0x18
	public Dictionary`2 squads; // 0x20
	public Dictionary`2 chars; // 0x28
	public Dictionary`2 addon; // 0x30
	public Dictionary`2 charMission; // 0x38


	// RVA: 0x32d5348 VA: 0x75958ed348
	public Void .ctor() { }
}
```