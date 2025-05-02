# BattlePlayerData

**Namespace:** `Torappu.Battle`


## Fields

- `PlayerSide playerSide`


## Methods

- `Void Append(BattlePlayerData)`

- `Boolean ContainCharacters(String)`

- `Boolean ContainTokens(String)`

- `BattlePlayerData Duplicate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattlePlayerData
{
	public PlayerSide playerSide; // 0x10
	public BattleCharacterData[] characters; // 0x18
	public BattleCharacterData[] tokens; // 0x20


	// RVA: 0x1c42614 VA: 0x759425a614
	public Void Append(BattlePlayerData other) { }
	// RVA: 0x1c427c4 VA: 0x759425a7c4
	public Boolean ContainCharacters(String id) { }
	// RVA: 0x1c42840 VA: 0x759425a840
	public Boolean ContainTokens(String id) { }
	// RVA: 0x1c428bc VA: 0x759425a8bc
	public BattlePlayerData Duplicate() { }
	// RVA: 0x1c3e910 VA: 0x7594256910
	public Void .ctor() { }
}
```