# SandboxCatchedAnimalTileBuildableChecker

**Namespace:** ` `


## Fields

- `SandboxCatchedAnimalManager m_manager`


## Methods

- `Boolean CheckTileBuildable(Tile, BattleCharacterData)`

- `Boolean _IsValidSourceData(BattleCharacterData)`

- `Boolean _IsValidTile(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxCatchedAnimalTileBuildableChecker : ITileBuildableChecker, IHotfixable
{
	private SandboxCatchedAnimalManager m_manager; // 0x10
	private ListDict`2 m_animalCardInfos; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CheckTileBuildable; // 0x8
	private static DelegateBridge __Hotfix0__IsValidSourceData; // 0x10
	private static DelegateBridge __Hotfix0__IsValidTile; // 0x18


	// RVA: 0x1ddade4 VA: 0x75943f2de4
	public Void .ctor(SandboxCatchedAnimalManager manager) { }
	// RVA: 0x1de1e38 VA: 0x75943f9e38
	public Boolean CheckTileBuildable(Tile tile, BattleCharacterData sourceData) { }
	// RVA: 0x1de1fa8 VA: 0x75943f9fa8
	private Boolean _IsValidSourceData(BattleCharacterData sourceData) { }
	// RVA: 0x1de2044 VA: 0x75943fa044
	private Boolean _IsValidTile(Tile tile) { }
}
```