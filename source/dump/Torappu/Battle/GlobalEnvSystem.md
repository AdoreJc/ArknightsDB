# GlobalEnvSystem

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean m_isComponentCollected`

- `Blackboard m_blackboard`

- `String m_id`

- `SideType _sideType`


## Properties

- `SideType side`

- `String id`


## Methods

- `SideType get_side()`

- `String get_id()`

- `Void OnInit(String, Blackboard)`

- `Void OnPostInit()`

- `Void _EnsureExecutorsAndManagers()`

- `Void _MergeAndInitBlackboard(Blackboard)`

- `Void OnTick(FP)`

- `Void Trigger(Object)`

- `T GetManager()`

- `Void OnEnvChanged(Tile, String)`

- `Void OnEnvChanged(Tile, Int32)`

- `Void OnEnvChanged(Entity, String, Entity)`

- `Void OnEnvChanged(String)`

- `Void OnEnvChanged(IList`1, String)`

- `Void OnEnvChanged(IList`1, String)`

- `Void GatherActionNodes(List`1)`

- `Void GatherProjectiles(List`1)`

- `Void GatherEffects(List`1)`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GlobalEnvSystem : MonoBehaviour, IBuffSource, IEffectSource, IActionNodeSource, IProjectileSource, IHotfixable
{
	private EnvEventExecutor[] m_envExecutors; // 0x18
	private EnvManager[] m_envManagers; // 0x20
	private Boolean m_isComponentCollected; // 0x28
	private Blackboard m_blackboard; // 0x30
	private String m_id; // 0x38
	private SideType _sideType; // 0x40
	private DataPair[] _blackboard; // 0x48
	private static DelegateBridge __Hotfix0_get_side; // 0x0
	private static DelegateBridge __Hotfix0_get_id; // 0x8
	private static DelegateBridge __Hotfix0_get_envExecutors; // 0x10
	private static DelegateBridge __Hotfix0_get_envManagers; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnPostInit; // 0x28
	private static DelegateBridge __Hotfix0__EnsureExecutorsAndManagers; // 0x30
	private static DelegateBridge __Hotfix0__MergeAndInitBlackboard; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_Trigger; // 0x48
	private static DelegateBridge __Hotfix0_GetManager; // 0x50
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x58
	private static DelegateBridge __Hotfix1_OnEnvChanged; // 0x60
	private static DelegateBridge __Hotfix2_OnEnvChanged; // 0x68
	private static DelegateBridge __Hotfix3_OnEnvChanged; // 0x70
	private static DelegateBridge __Hotfix4_OnEnvChanged; // 0x78
	private static DelegateBridge __Hotfix5_OnEnvChanged; // 0x80
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x88
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x90
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x98
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public SideType side { get; }
	public String id { get; }
	private EnvEventExecutor[] envExecutors { get; }
	public EnvManager[] envManagers { get; }

	// RVA: 0x4025a40 VA: 0x759663da40
	public SideType get_side() { }
	// RVA: 0x4028298 VA: 0x7596640298
	public String get_id() { }
	// RVA: 0x4028300 VA: 0x7596640300
	private EnvEventExecutor[] get_envExecutors() { }
	// RVA: 0x40284bc VA: 0x75966404bc
	public EnvManager[] get_envManagers() { }
	// RVA: 0x402852c VA: 0x759664052c
	public Void OnInit(String id, Blackboard overrideBlackboard) { }
	// RVA: 0x4028810 VA: 0x7596640810
	public Void OnPostInit() { }
	// RVA: 0x4028370 VA: 0x7596640370
	private Void _EnsureExecutorsAndManagers() { }
	// RVA: 0x40286e4 VA: 0x75966406e4
	private Void _MergeAndInitBlackboard(Blackboard overrideBlackboard) { }
	// RVA: 0x4028988 VA: 0x7596640988
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x4028af0 VA: 0x7596640af0
	public Void Trigger(Object param) { }
	// RVA: 0x VA: 0x0
	public T GetManager() { }
	// RVA: 0x4028bc8 VA: 0x7596640bc8
	public Void OnEnvChanged(Tile tile, String status) { }
	// RVA: 0x4028ce4 VA: 0x7596640ce4
	public Void OnEnvChanged(Tile tile, Int32 status) { }
	// RVA: 0x4028e00 VA: 0x7596640e00
	public Void OnEnvChanged(Entity target, String status, Entity sourceNullable) { }
	// RVA: 0x4029040 VA: 0x7596641040
	public Void OnEnvChanged(String status) { }
	// RVA: 0x4029118 VA: 0x7596641118
	public Void OnEnvChanged(IList`1 tiles, String status) { }
	// RVA: 0x4029444 VA: 0x7596641444
	public Void OnEnvChanged(IList`1 entities, String status) { }
	// RVA: 0x4029774 VA: 0x7596641774
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x4029848 VA: 0x7596641848
	public Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x40298c0 VA: 0x75966418c0
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x40299e8 VA: 0x75966419e8
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x4029b10 VA: 0x7596641b10
	public Void .ctor() { }
}
```