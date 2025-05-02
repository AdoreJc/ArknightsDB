# CooperateFortressFixerBuildableChecker

**Namespace:** ` `


## Fields

- `CooperateGameMode m_mode`


## Methods

- `Void OnInit()`

- `Boolean CheckTileBuildable(Tile, BattleCharacterData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CooperateFortressFixerBuildableChecker : ITileBuildableChecker, IHotfixable
{
	private CooperateGameMode m_mode; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_CheckTileBuildable; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1cc95e8 VA: 0x75942e15e8
	public Void OnInit() { }
	// RVA: 0x1cc9ddc VA: 0x75942e1ddc
	public Boolean CheckTileBuildable(Tile tile, BattleCharacterData sourceData) { }
	// RVA: 0x1cc9578 VA: 0x75942e1578
	public Void .ctor() { }
}
```