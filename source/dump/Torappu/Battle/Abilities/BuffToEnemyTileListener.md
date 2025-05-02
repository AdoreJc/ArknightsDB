# BuffToEnemyTileListener

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TargetValidator _targetValidator`

- `Boolean _clearBuffWhenAbilityDetached`

- `Blackboard m_blackboard`


## Methods

- `Void _BuffToEnemy(BuffData[], Enemy)`

- `Void <>xLuaBaseProxy_DoSetData(Options)`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_OnCasted(Tile, Int32)`

- `Void <>xLuaBaseProxy_OnRefresh(Tile)`

- `Void <>xLuaBaseProxy_OnEntityEnter(Entity)`

- `Void <>xLuaBaseProxy_OnEntityLeave(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffToEnemyTileListener : AttachableTileListener
{
	private TargetValidator _targetValidator; // 0x20
	private BuffData[] _buffsWhenCasted; // 0x28
	private BuffData[] _buffsWhenEnemyEnter; // 0x30
	private BuffData[] _buffsWhenEnemyLeave; // 0x38
	private Boolean _clearBuffWhenAbilityDetached; // 0x40
	private const String CASTED_TIMES; // 0x0
	private Blackboard m_blackboard; // 0x48
	private List`1 m_buffs; // 0x50
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnDetached; // 0x8
	private static DelegateBridge __Hotfix0_OnCasted; // 0x10
	private static DelegateBridge __Hotfix0_OnRefresh; // 0x18
	private static DelegateBridge __Hotfix0_OnEntityEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnEntityLeave; // 0x28
	private static DelegateBridge __Hotfix0__BuffToEnemy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1ed6b4c VA: 0x75944eeb4c
	public override Void DoSetData(Options options) { }
	// RVA: 0x1ed6c4c VA: 0x75944eec4c
	public override Void OnDetached() { }
	// RVA: 0x1ed6e68 VA: 0x75944eee68
	public override Void OnCasted(Tile tile, Int32 times) { }
	// RVA: 0x1ed7498 VA: 0x75944ef498
	public override Void OnRefresh(Tile tile) { }
	// RVA: 0x1ed77a4 VA: 0x75944ef7a4
	public override Void OnEntityEnter(Entity entity) { }
	// RVA: 0x1ed7870 VA: 0x75944ef870
	public override Void OnEntityLeave(Entity entity) { }
	// RVA: 0x1ed717c VA: 0x75944ef17c
	private Void _BuffToEnemy(BuffData[] buffs, Enemy enemy) { }
	// RVA: 0x1ed793c VA: 0x75944ef93c
	public Void .ctor() { }
	// RVA: 0x1ed7ab0 VA: 0x75944efab0
	private Void <>xLuaBaseProxy_DoSetData(Options P0) { }
	// RVA: 0x1ed7ad8 VA: 0x75944efad8
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1ed7ae0 VA: 0x75944efae0
	private Void <>xLuaBaseProxy_OnCasted(Tile P0, Int32 P1) { }
	// RVA: 0x1ed7ae8 VA: 0x75944efae8
	private Void <>xLuaBaseProxy_OnRefresh(Tile P0) { }
	// RVA: 0x1ed7af0 VA: 0x75944efaf0
	private Void <>xLuaBaseProxy_OnEntityEnter(Entity P0) { }
	// RVA: 0x1ed7af8 VA: 0x75944efaf8
	private Void <>xLuaBaseProxy_OnEntityLeave(Entity P0) { }
}
```