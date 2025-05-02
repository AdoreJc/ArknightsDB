# Act27SideBattleManager

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 tickPeriodic`

- `String _tileEffectKey`

- `String _tileEffectNightKey`

- `Card m_stmbotCard`

- `Boolean m_isNightMap`


## Methods

- `Void _InitTileData()`

- `Boolean _IsEntityValid(Entity)`

- `Boolean _IsSwitchable(Tile)`

- `Boolean _CheckTileInBlackList(Tile)`

- `Void _DoRemoveEntities()`

- `Void OnGameStart(Object)`

- `Void OnUnitBorn(Object)`

- `Void OnUnitFinish(Object)`

- `Void OnUnitSwitchSide(Object)`

- `Void RefreshEntityBuffs(Entity, MechanismSideType, Boolean)`

- `Void ToggleTileSideType(Tile, MechanismSideType)`

- `Void DoToggleTileSideType(Tile, MechanismSideType)`

- `Boolean CheckEntityRootTileSideType(Entity, MechanismSideType)`

- `Boolean TryGetTileSideType(Tile, out)`

- `Void AddTileBlackList(Tile)`

- `Int32 CalculateScore(Int32, Int32, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act27SideBattleManager : EnvManager
{
	private Act27SideMechanismConfig[] _configs; // 0x28
	private Int32 tickPeriodic; // 0x30
	private String[] _tileBlackList; // 0x38
	private String _tileEffectKey; // 0x40
	private String _tileEffectNightKey; // 0x48
	private Dictionary`2 m_tileStatesMap; // 0x50
	private List`1 m_tileStatesList; // 0x58
	private Dictionary`2 m_entities; // 0x60
	private List`1 m_removedEntities; // 0x68
	private Card m_stmbotCard; // 0x70
	private HashSet`1 m_additionalTileBlackList; // 0x78
	private Boolean m_isNightMap; // 0x80
	public static readonly String EVENT_SYSTEM_KEY; // 0x0
	public static readonly String STMBOT_KEY; // 0x8
	public static readonly String NIGHT_MAP_KEY; // 0x10

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x402b6cc VA: 0x75966436cc
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x402b830 VA: 0x7596643830
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x402bc24 VA: 0x7596643c24
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x402bd00 VA: 0x7596643d00
	private Void _InitTileData() { }
	// RVA: 0x402c170 VA: 0x7596644170
	private Boolean _IsEntityValid(Entity entity) { }
	// RVA: 0x402c264 VA: 0x7596644264
	private Boolean _IsSwitchable(Tile tile) { }
	// RVA: 0x402bf8c VA: 0x7596643f8c
	private Boolean _CheckTileInBlackList(Tile tile) { }
	// RVA: 0x402c2e0 VA: 0x75966442e0
	private Void _DoRemoveEntities() { }
	// RVA: 0x402c3dc VA: 0x75966443dc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x402cb38 VA: 0x7596644b38
	public override Void OnTrigger(Object param) { }
	// RVA: 0x402d2c8 VA: 0x75966452c8
	public Void OnGameStart(Object args) { }
	// RVA: 0x402d414 VA: 0x7596645414
	public Void OnUnitBorn(Object args) { }
	// RVA: 0x402d79c VA: 0x759664579c
	public Void OnUnitFinish(Object args) { }
	// RVA: 0x402d9c0 VA: 0x75966459c0
	public Void OnUnitSwitchSide(Object args) { }
	// RVA: 0x402ccb4 VA: 0x7596644cb4
	public Void RefreshEntityBuffs(Entity entity, MechanismSideType mechanismSideType, Boolean onToggle) { }
	// RVA: 0x402a550 VA: 0x7596642550
	public Void ToggleTileSideType(Tile tile, MechanismSideType mechanismSideType) { }
	// RVA: 0x402c53c VA: 0x759664453c
	public Void DoToggleTileSideType(Tile tile, MechanismSideType mechanismSideType) { }
	// RVA: 0x402dc0c VA: 0x7596645c0c
	public Boolean CheckEntityRootTileSideType(Entity entity, MechanismSideType sideType) { }
	// RVA: 0x402dd04 VA: 0x7596645d04
	public Boolean TryGetTileSideType(Tile tile, out MechanismSideType sideType) { }
	// RVA: 0x402ddb8 VA: 0x7596645db8
	public Void AddTileBlackList(Tile tile) { }
	// RVA: 0x402de74 VA: 0x7596645e74
	public Int32 CalculateScore(Int32 basic, Int32 add, Color color) { }
	// RVA: 0x402e18c VA: 0x759664618c
	public Void .ctor() { }
	// RVA: 0x402e358 VA: 0x7596646358
	private static Void .cctor() { }
}
```