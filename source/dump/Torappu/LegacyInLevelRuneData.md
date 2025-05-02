# LegacyInLevelRuneData

**Namespace:** `Torappu`


## Fields

- `Difficulty difficultyMask`

- `String key`

- `ProfessionCategory professionMask`

- `BuildableType buildableMask`

- `Blackboard blackboard`


## Methods

- `Boolean CheckValidForDifficulty(Difficulty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class LegacyInLevelRuneData
{
	public Difficulty difficultyMask; // 0x10
	public static List`1 SIX_STAR_RUNE_NAMES; // 0x0
	public String key; // 0x18
	public ProfessionCategory professionMask; // 0x20
	public BuildableType buildableMask; // 0x24
	public Blackboard blackboard; // 0x28


	// RVA: 0x34b0d30 VA: 0x7595ac8d30
	public Boolean CheckValidForDifficulty(Difficulty difficulty) { }
	// RVA: 0x34b0d40 VA: 0x7595ac8d40
	public Void .ctor() { }
	// RVA: 0x34b0dc8 VA: 0x7595ac8dc8
	private static Void .cctor() { }
}
```