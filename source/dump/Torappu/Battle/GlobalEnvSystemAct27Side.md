# GlobalEnvSystemAct27Side

**Namespace:** `Torappu.Battle`


## Fields

- `Act27SideBattleManager _manager`


## Properties

- `Act27SideBattleManager manager`


## Methods

- `Act27SideBattleManager get_manager()`

- `Void ModifyTileCachedSideType(Tile, MechanismSideType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GlobalEnvSystemAct27Side : GlobalEnvSystem
{
	private Act27SideBattleManager _manager; // 0x50
	private static DelegateBridge __Hotfix0_get_manager; // 0x0
	private static DelegateBridge __Hotfix0_ModifyTileCachedSideType; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Act27SideBattleManager manager { get; }

	// RVA: 0x402a40c VA: 0x759664240c
	public Act27SideBattleManager get_manager() { }
	// RVA: 0x402a474 VA: 0x7596642474
	public Void ModifyTileCachedSideType(Tile tile, MechanismSideType mechanismSideType) { }
	// RVA: 0x402a678 VA: 0x7596642678
	public Void .ctor() { }
}
```