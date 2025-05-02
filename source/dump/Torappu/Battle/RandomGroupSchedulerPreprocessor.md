# RandomGroupSchedulerPreprocessor

**Namespace:** `Torappu.Battle`


## Methods

- `Void <>xLuaBaseProxy_DoPreprocess(LevelData)`

- `Void <>xLuaBaseProxy_Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RandomGroupSchedulerPreprocessor : DefaultSchedulerPreprocessor
{
	private readonly Dictionary`2 m_randomActionGroups; // 0x10
	private readonly PriorityQueue`1 m_actionsToDelete; // 0x18
	private readonly Dictionary`2 m_mimicEnemyGroups; // 0x20
	private readonly Dictionary`2 m_mimicTrapGroups; // 0x28
	private readonly HashSet`1 m_actionPacksToDelete; // 0x30
	private static DelegateBridge __Hotfix0_DoPreprocess; // 0x0
	private static DelegateBridge __Hotfix0_Dispose; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x40e29d0 VA: 0x75966fa9d0
	public override Void DoPreprocess(LevelData levelData) { }
	// RVA: 0x40e3878 VA: 0x75966fb878
	public override Void Dispose() { }
	// RVA: 0x40e3988 VA: 0x75966fb988
	public Void .ctor() { }
	// RVA: 0x40e3b70 VA: 0x75966fbb70
	private Void <>xLuaBaseProxy_DoPreprocess(LevelData P0) { }
	// RVA: 0x40e3b78 VA: 0x75966fbb78
	private Void <>xLuaBaseProxy_Dispose() { }
}
```