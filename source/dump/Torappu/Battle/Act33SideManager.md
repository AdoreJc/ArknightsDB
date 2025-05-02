# Act33SideManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _rangeId`

- `FilterType _postFilter`

- `Int32 _ropeMaxCnt`

- `BuffData _breakRopebuff`

- `Ability _projectileAbility`

- `TargetOptions _targetOptions`

- `PeriodicTimer m_createHitLineTimer`

- `PeriodicTimer m_createHitLineGamecityTimer`

- `Single m_createHitLineInterval`

- `Single m_createHitLineGamecityInterval`

- `Act33SideRopeTileBuildableChecker m_tileBuildableChecker`

- `Tile m_currentDummyTile`

- `String m_rangeId`


## Methods

- `Void ModifyRopeTileDeployableValue(Tile, Int32)`

- `Void AddManagedProjectile(Character, Projectile)`

- `Void FinishManagedProjectile(Character, String)`

- `Void _CreateProjectile(String, Character, Character, Boolean)`

- `Boolean _CreateProjectileForDummy(String, Character, Character)`

- `Void _CreateProjectileUseSourceAsProjectileSource(String, Character, Character)`

- `Void _RefreshTiles(Character, Int32)`

- `Void _ModifyRopeCnt(Character, Boolean)`

- `Void CutRope(Character)`

- `Int32 GetCharaterCurrentRopeCnt(Character)`

- `Void CollectCharactersWithRope(Character)`

- `Void _CollectCharactersWithRope(Character)`

- `Void ApplyDamageCharactersWithRope(FP, Entity, FP, DamageType)`

- `Void ApplyElementDamageCharactersWithRope(FP, Entity, ElementType)`

- `Void _ApplyDamageModifier(FP, Entity, Character, DamageType, FP)`

- `Void _ApplyElementDamageModifier(FP, Entity, Character, ElementType)`

- `Void OnDummyLocateTile(Object)`

- `Void RefreshRopeAndTiles(Object)`

- `Void CreateRopeOnCharacterBorn(Object)`

- `Void GatherAudio(List`1)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act33SideManager : EnvManager, IBuffSource, IHotfixable, IAudioSource
{
	public static readonly String EVENT_SYSTEM_KEY; // 0x0
	private const String RAROPE_TILE_KEY; // 0x0
	private const String MEROPE_TILE_KEY; // 0x0
	private const String ROPE_LINE_PROJECTILEKEY; // 0x0
	private const String ROPE_HIT_LINE_PROJECTILEKEY; // 0x0
	private const String ROPE_DUMMY_EFFECT_PROJECTILEKEY; // 0x0
	private const String ROPE_HIT_LINE_PROJECTILE_FOR_GAMECITY; // 0x0
	private const String ROPE_LINE_CREATE_AUDIO; // 0x0
	private String _rangeId; // 0x28
	protected FilterType _postFilter; // 0x30
	private Int32 _ropeMaxCnt; // 0x34
	private BuffData _breakRopebuff; // 0x38
	private Ability _projectileAbility; // 0x40
	private TargetOptions _targetOptions; // 0x48
	private PeriodicTimer m_createHitLineTimer; // 0xa8
	private PeriodicTimer m_createHitLineGamecityTimer; // 0xb0
	private Single m_createHitLineInterval; // 0xb8
	private Single m_createHitLineGamecityInterval; // 0xbc
	private Dictionary`2 m_managedProjectiles; // 0xc0
	private Dictionary`2 m_ropeDict; // 0xc8
	private Dictionary`2 m_ropeTiles; // 0xd0
	private List`1 m_burnedCharacters; // 0xd8
	private Act33SideRopeTileBuildableChecker m_tileBuildableChecker; // 0xe0
	private Tile m_currentDummyTile; // 0xe8
	private String m_rangeId; // 0xf0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0_ModifyRopeTileDeployableValue; // 0x20
	private static DelegateBridge __Hotfix0_AddManagedProjectile; // 0x28
	private static DelegateBridge __Hotfix0_FinishManagedProjectile; // 0x30
	private static DelegateBridge __Hotfix0__CreateProjectile; // 0x38
	private static DelegateBridge __Hotfix0__CreateProjectileForDummy; // 0x40
	private static DelegateBridge __Hotfix0__CreateProjectileUseSourceAsProjectileSource; // 0x48
	private static DelegateBridge __Hotfix0__RefreshTiles; // 0x50
	private static DelegateBridge __Hotfix0__ModifyRopeCnt; // 0x58
	private static DelegateBridge __Hotfix0_CutRope; // 0x60
	private static DelegateBridge __Hotfix0_GetCharaterCurrentRopeCnt; // 0x68
	private static DelegateBridge __Hotfix0_CollectCharactersWithRope; // 0x70
	private static DelegateBridge __Hotfix0__CollectCharactersWithRope; // 0x78
	private static DelegateBridge __Hotfix0_ApplyDamageCharactersWithRope; // 0x80
	private static DelegateBridge __Hotfix0_ApplyElementDamageCharactersWithRope; // 0x88
	private static DelegateBridge __Hotfix0__ApplyDamageModifier; // 0x90
	private static DelegateBridge __Hotfix0__ApplyElementDamageModifier; // 0x98
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0xa0
	private static DelegateBridge __Hotfix0_OnDummyLocateTile; // 0xa8
	private static DelegateBridge __Hotfix0_RefreshRopeAndTiles; // 0xb0
	private static DelegateBridge __Hotfix0_CreateRopeOnCharacterBorn; // 0xb8
	private static DelegateBridge __Hotfix0_GatherAudio; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4030f3c VA: 0x7596648f3c
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x40313ec VA: 0x75966493ec
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x40314fc VA: 0x75966494fc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x4031bb8 VA: 0x7596649bb8
	public Void ModifyRopeTileDeployableValue(Tile tile, Int32 value) { }
	// RVA: 0x4031d10 VA: 0x7596649d10
	public Void AddManagedProjectile(Character character, Projectile projectile) { }
	// RVA: 0x4032018 VA: 0x759664a018
	public Void FinishManagedProjectile(Character character, String projectileKey) { }
	// RVA: 0x4032404 VA: 0x759664a404
	private Void _CreateProjectile(String projectileKey, Character source, Character target, Boolean addManaged) { }
	// RVA: 0x40325f8 VA: 0x759664a5f8
	private Boolean _CreateProjectileForDummy(String projectileKey, Character source, Character target) { }
	// RVA: 0x40319e8 VA: 0x75966499e8
	private Void _CreateProjectileUseSourceAsProjectileSource(String projectileKey, Character source, Character target) { }
	// RVA: 0x40327e8 VA: 0x759664a7e8
	private Void _RefreshTiles(Character character, Int32 value) { }
	// RVA: 0x403298c VA: 0x759664a98c
	private Void _ModifyRopeCnt(Character character, Boolean isminus) { }
	// RVA: 0x4032c90 VA: 0x759664ac90
	public Void CutRope(Character source) { }
	// RVA: 0x4032e28 VA: 0x759664ae28
	public Int32 GetCharaterCurrentRopeCnt(Character character) { }
	// RVA: 0x4032f18 VA: 0x759664af18
	public Void CollectCharactersWithRope(Character target) { }
	// RVA: 0x4032fe4 VA: 0x759664afe4
	private Void _CollectCharactersWithRope(Character target) { }
	// RVA: 0x4033448 VA: 0x759664b448
	public Void ApplyDamageCharactersWithRope(FP atk, Entity source, FP atkscale, DamageType damageType) { }
	// RVA: 0x40337f4 VA: 0x759664b7f4
	public Void ApplyElementDamageCharactersWithRope(FP fixedEpDamage, Entity source, ElementType elementDamageType) { }
	// RVA: 0x4033654 VA: 0x759664b654
	private Void _ApplyDamageModifier(FP atk, Entity source, Character target, DamageType damageType, FP atkScale) { }
	// RVA: 0x40339ec VA: 0x759664b9ec
	private Void _ApplyElementDamageModifier(FP fixedEpDamage, Entity source, Character target, ElementType elementDamageType) { }
	// RVA: 0x4033bcc VA: 0x759664bbcc
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4033e7c VA: 0x759664be7c
	public Void OnDummyLocateTile(Object arg) { }
	// RVA: 0x4034874 VA: 0x759664c874
	public Void RefreshRopeAndTiles(Object arg) { }
	// RVA: 0x4034f70 VA: 0x759664cf70
	public Void CreateRopeOnCharacterBorn(Object arg) { }
	// RVA: 0x4035bd4 VA: 0x759664dbd4
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x4035cec VA: 0x759664dcec
	public Void .ctor() { }
	// RVA: 0x4035f64 VA: 0x759664df64
	private static Void .cctor() { }
	// RVA: 0x4035fd0 VA: 0x759664dfd0
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4035fd4 VA: 0x759664dfd4
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x4035fd8 VA: 0x759664dfd8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x4035fdc VA: 0x759664dfdc
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
}
```