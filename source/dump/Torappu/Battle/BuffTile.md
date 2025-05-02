# BuffTile

**Namespace:** `Torappu.Battle`


## Fields

- `TargetOptions _targetOptions`

- `SideType _sourceSide`

- `Boolean _clearBuffsWhenLeft`


## Properties

- `SideType sourceSide`

- `Boolean applyToCharacter`

- `Boolean applyToEnemy`


## Methods

- `SideType get_sourceSide()`

- `Boolean get_applyToCharacter()`

- `Boolean get_applyToEnemy()`

- `Void ApplyBuffs(Entity, List`1)`

- `Void ClearBuffs(Entity, List`1)`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`

- `Void <>xLuaBaseProxy_OnCharacterEnter(Character, Character)`

- `Void <>xLuaBaseProxy_OnCharacterLeave(Character)`

- `Void <>xLuaBaseProxy_OnRallyPointLikeReborn(Unit)`

- `Void <>xLuaBaseProxy_OnEnemyEnter(Enemy)`

- `Void <>xLuaBaseProxy_OnEnemyLeave(Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BuffTile : Tile, IBuffSource
{
	private static readonly List`1 EMPTY_IDS; // 0x0
	protected TargetOptions _targetOptions; // 0x110
	private SideType _sourceSide; // 0x170
	protected BuffData[] _buffs; // 0x178
	private Boolean _clearBuffsWhenLeft; // 0x180
	protected List`1 m_charBuffUids; // 0x188
	private Dictionary`2 m_enemyBuffUids; // 0x190
	private static DelegateBridge __Hotfix0_get_traceBuffUids; // 0x8
	private static DelegateBridge __Hotfix0_get_sourceSide; // 0x10
	private static DelegateBridge __Hotfix0_get_applyToCharacter; // 0x18
	private static DelegateBridge __Hotfix0_get_applyToEnemy; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x30
	private static DelegateBridge __Hotfix0_OnCharacterEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnCharacterLeave; // 0x40
	private static DelegateBridge __Hotfix0_OnRallyPointLikeReborn; // 0x48
	private static DelegateBridge __Hotfix0_OnEnemyEnter; // 0x50
	private static DelegateBridge __Hotfix0_OnEnemyLeave; // 0x58
	private static DelegateBridge __Hotfix0_ApplyBuffs; // 0x60
	private static DelegateBridge __Hotfix0_ClearBuffs; // 0x68
	private static DelegateBridge __Hotfix0_EnsureEnemyBuffList; // 0x70
	private static DelegateBridge __Hotfix0_PreloadBuffAssets; // 0x78
	private static DelegateBridge __Hotfix0_OnInvalidEnemyEnter; // 0x80
	private static DelegateBridge __Hotfix0_OnEnemyValid; // 0x88
	private static DelegateBridge __Hotfix0_OnEnemyInvalid; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	protected virtual Boolean traceBuffUids { get; }
	protected SideType sourceSide { get; }
	protected Boolean applyToCharacter { get; }
	protected Boolean applyToEnemy { get; }

	// RVA: 0x4087ae8 VA: 0x759669fae8
	protected virtual Boolean get_traceBuffUids() { }
	// RVA: 0x4087b60 VA: 0x759669fb60
	protected SideType get_sourceSide() { }
	// RVA: 0x4087bd8 VA: 0x759669fbd8
	protected Boolean get_applyToCharacter() { }
	// RVA: 0x4087c54 VA: 0x759669fc54
	protected Boolean get_applyToEnemy() { }
	// RVA: 0x4087cd0 VA: 0x759669fcd0
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x4088434 VA: 0x75966a0434
	public virtual Void GatherBuffs(List`1 results) { }
	// RVA: 0x40884e4 VA: 0x75966a04e4
	protected override Void OnCharacterEnter(Character newChar, Character oldChar) { }
	// RVA: 0x40889b0 VA: 0x75966a09b0
	protected override Void OnCharacterLeave(Character character) { }
	// RVA: 0x4088ce0 VA: 0x75966a0ce0
	public override Void OnRallyPointLikeReborn(Unit unit) { }
	// RVA: 0x4088e20 VA: 0x75966a0e20
	protected override Void OnEnemyEnter(Enemy enemy) { }
	// RVA: 0x4088f78 VA: 0x75966a0f78
	protected override Void OnEnemyLeave(Enemy enemy) { }
	// RVA: 0x4088854 VA: 0x75966a0854
	private Void ApplyBuffs(Entity target, List`1 buffUids) { }
	// RVA: 0x4088740 VA: 0x75966a0740
	protected Void ClearBuffs(Entity target, List`1 buffUids) { }
	// RVA: 0x4089178 VA: 0x75966a1178
	protected List`1 EnsureEnemyBuffList(Entity enemy, Dictionary`2 buffUidDict) { }
	// RVA: 0x4089334 VA: 0x75966a1334
	protected virtual Void PreloadBuffAssets() { }
	// RVA: 0x40893fc VA: 0x75966a13fc
	public virtual Void OnInvalidEnemyEnter(Enemy enemy) { }
	// RVA: 0x4089484 VA: 0x75966a1484
	public virtual Void OnEnemyValid(Enemy enemy) { }
	// RVA: 0x4089528 VA: 0x75966a1528
	public virtual Void OnEnemyInvalid(Enemy enemy) { }
	// RVA: 0x40895cc VA: 0x75966a15cc
	public Void .ctor() { }
	// RVA: 0x408996c VA: 0x75966a196c
	private static Void .cctor() { }
	// RVA: 0x4089a04 VA: 0x75966a1a04
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
	// RVA: 0x4089a08 VA: 0x75966a1a08
	private Void <>xLuaBaseProxy_OnCharacterEnter(Character P0, Character P1) { }
	// RVA: 0x4089a0c VA: 0x75966a1a0c
	private Void <>xLuaBaseProxy_OnCharacterLeave(Character P0) { }
	// RVA: 0x4089a10 VA: 0x75966a1a10
	private Void <>xLuaBaseProxy_OnRallyPointLikeReborn(Unit P0) { }
	// RVA: 0x4089a14 VA: 0x75966a1a14
	private Void <>xLuaBaseProxy_OnEnemyEnter(Enemy P0) { }
	// RVA: 0x4089a18 VA: 0x75966a1a18
	private Void <>xLuaBaseProxy_OnEnemyLeave(Enemy P0) { }
}
```