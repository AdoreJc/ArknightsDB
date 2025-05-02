# StormManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _inStormKey`

- `String _notInStormKey`

- `TargetOptions _targetOption`

- `Direction m_stormDirection`


## Methods

- `Void _OnGameStart(Object)`

- `Void _OnUnitBorn(Object)`

- `Void _UpdateStormBlocker(IBuildable)`

- `Void _OnUnitFinish(Object)`

- `Boolean _CharacterValid(Character)`

- `Void _UpdateTileStatus()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class StormManager : EnvManager
{
	private String _inStormKey; // 0x28
	private String _notInStormKey; // 0x30
	private List`1 _trapTagWhiteList; // 0x38
	private TargetOptions _targetOption; // 0x40
	private List`1 _effectSettings; // 0xa0
	private Dictionary`2 m_tileContainStormBlocker; // 0xa8
	private Boolean[,] m_tileInStormBefore; // 0xb0
	private Boolean[,] m_tileInStorm; // 0xb8
	private Direction m_stormDirection; // 0xc0
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0__OnGameStart; // 0x8
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x10
	private static DelegateBridge __Hotfix0__UpdateStormBlocker; // 0x18
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x20
	private static DelegateBridge __Hotfix0__CharacterValid; // 0x28
	private static DelegateBridge __Hotfix0__UpdateTileStatus; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4066918 VA: 0x759667e918
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4066cb8 VA: 0x759667ecb8
	private Void _OnGameStart(Object arg) { }
	// RVA: 0x4067880 VA: 0x759667f880
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x4067a00 VA: 0x759667fa00
	private Void _UpdateStormBlocker(IBuildable unit) { }
	// RVA: 0x4067c58 VA: 0x759667fc58
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x40671ac VA: 0x759667f1ac
	private Boolean _CharacterValid(Character character) { }
	// RVA: 0x40672a4 VA: 0x759667f2a4
	private Void _UpdateTileStatus() { }
	// RVA: 0x4067d94 VA: 0x759667fd94
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x4067fa0 VA: 0x759667ffa0
	public Void .ctor() { }
	// RVA: 0x40680b8 VA: 0x75966800b8
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x40680c0 VA: 0x75966800c0
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```