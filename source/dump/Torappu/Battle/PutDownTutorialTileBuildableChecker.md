# PutDownTutorialTileBuildableChecker

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_tileX`

- `Int32 m_tileY`


## Methods

- `Boolean CheckTileBuildable(Tile, BattleCharacterData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class PutDownTutorialTileBuildableChecker : ITileBuildableChecker
{
	private Int32 m_tileX; // 0x10
	private Int32 m_tileY; // 0x14


	// RVA: 0x3fd58b8 VA: 0x75965ed8b8
	public Void .ctor(Int32 x, Int32 y) { }
	// RVA: 0x3fd61ac VA: 0x75965ee1ac
	public Boolean CheckTileBuildable(Tile tile, BattleCharacterData sourceData) { }
	// RVA: 0x3fd62b0 VA: 0x75965ee2b0
	public override String ToString() { }
}
```