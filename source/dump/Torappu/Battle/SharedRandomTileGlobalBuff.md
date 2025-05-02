# SharedRandomTileGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _tickForEnemy`

- `Single _tickInterval`

- `PeriodicTimer m_timer`


## Properties

- `Boolean tickForEnemy`


## Methods

- `Boolean get_tickForEnemy()`

- `Boolean _CheckEnemyContainsAnyBuff(Enemy)`

- `Void _FinishBuffForEnemy(Enemy)`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`

- `Boolean <>xLuaBaseProxy_TryAddBindingTiles(List`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Boolean <>xLuaBaseProxy_FilterTile(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SharedRandomTileGlobalBuff : RandomTileGlobalBuff
{
	protected static List`1 s_targetTiles; // 0x0
	private Boolean _tickForEnemy; // 0x108
	private Single _tickInterval; // 0x10c
	private PeriodicTimer m_timer; // 0x110
	private static DelegateBridge __Hotfix0_get_tickForEnemy; // 0x8
	private static DelegateBridge __Hotfix0_ClearStaticVariables; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_TryAddBindingTiles; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_VerifyUnitTile; // 0x30
	private static DelegateBridge __Hotfix0_FilterTile; // 0x38
	private static DelegateBridge __Hotfix0__CheckEnemyContainsAnyBuff; // 0x40
	private static DelegateBridge __Hotfix0__FinishBuffForEnemy; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Boolean tickForEnemy { get; }

	// RVA: 0x401cb90 VA: 0x7596634b90
	private Boolean get_tickForEnemy() { }
	// RVA: 0x401cc08 VA: 0x7596634c08
	public static Void ClearStaticVariables() { }
	// RVA: 0x401aea4 VA: 0x7596632ea4
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x401c5ec VA: 0x75966345ec
	public override Boolean TryAddBindingTiles(List`1 tiles) { }
	// RVA: 0x401bdd8 VA: 0x7596633dd8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x401cf5c VA: 0x7596634f5c
	protected override Boolean VerifyUnitTile(Unit unit, Boolean isInit) { }
	// RVA: 0x401ca8c VA: 0x7596634a8c
	protected override Boolean FilterTile(Tile tile) { }
	// RVA: 0x401ccb0 VA: 0x7596634cb0
	private Boolean _CheckEnemyContainsAnyBuff(Enemy enemy) { }
	// RVA: 0x401ce0c VA: 0x7596634e0c
	private Void _FinishBuffForEnemy(Enemy enemy) { }
	// RVA: 0x401c430 VA: 0x7596634430
	public Void .ctor() { }
	// RVA: 0x401d094 VA: 0x7596635094
	private static Void .cctor() { }
	// RVA: 0x401d12c VA: 0x759663512c
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
	// RVA: 0x401d130 VA: 0x7596635130
	private Boolean <>xLuaBaseProxy_TryAddBindingTiles(List`1 P0) { }
	// RVA: 0x401d134 VA: 0x7596635134
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x401d138 VA: 0x7596635138
	private Boolean <>xLuaBaseProxy_FilterTile(Tile P0) { }
}
```