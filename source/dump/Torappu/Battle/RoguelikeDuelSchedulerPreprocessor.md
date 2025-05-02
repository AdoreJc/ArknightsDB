# RoguelikeDuelSchedulerPreprocessor

**Namespace:** `Torappu.Battle`


## Methods

- `Void set_randomActionGroups_2(Dictionary`2)`

- `Void set_actionsToDelete_2(PriorityQueue`1)`

- `Void <>xLuaBaseProxy_DoPreprocess(LevelData)`

- `Void <>xLuaBaseProxy_Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RoguelikeDuelSchedulerPreprocessor : Roguelike2SchedulerPreprocessor
{
	private Dictionary`2 m_randomActionGroups; // 0x60
	private PriorityQueue`1 m_actionsToDelete; // 0x68
	private List`1 m_fragmentEnemiesAppeared; // 0x70
	private const Int32 MAX_RANDOM_COUNT; // 0x0
	private const Int32 MAX_GROUP_NUM; // 0x0
	private static DelegateBridge __Hotfix0_get_randomActionGroups_2; // 0x0
	private static DelegateBridge __Hotfix0_set_randomActionGroups_2; // 0x8
	private static DelegateBridge __Hotfix0_get_actionsToDelete_2; // 0x10
	private static DelegateBridge __Hotfix0_set_actionsToDelete_2; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge __Hotfix0_DoPreprocess; // 0x28
	private static DelegateBridge __Hotfix0_Dispose; // 0x30

	protected Dictionary`2 randomActionGroups_2 { get; set; }
	protected PriorityQueue`1 actionsToDelete_2 { get; set; }

	// RVA: 0x40ce214 VA: 0x75966e6214
	protected Dictionary`2 get_randomActionGroups_2() { }
	// RVA: 0x40ce2dc VA: 0x75966e62dc
	protected Void set_randomActionGroups_2(Dictionary`2 value) { }
	// RVA: 0x40ce360 VA: 0x75966e6360
	protected PriorityQueue`1 get_actionsToDelete_2() { }
	// RVA: 0x40ce428 VA: 0x75966e6428
	protected Void set_actionsToDelete_2(PriorityQueue`1 value) { }
	// RVA: 0x40ce4ac VA: 0x75966e64ac
	public Void .ctor(RoguelikeInput input) { }
	// RVA: 0x40ce628 VA: 0x75966e6628
	public override Void DoPreprocess(LevelData levelData) { }
	// RVA: 0x40cf4b8 VA: 0x75966e74b8
	public override Void Dispose() { }
	// RVA: 0x40cf5a8 VA: 0x75966e75a8
	private Void <>xLuaBaseProxy_DoPreprocess(LevelData P0) { }
	// RVA: 0x40cf5b0 VA: 0x75966e75b0
	private Void <>xLuaBaseProxy_Dispose() { }
}
```