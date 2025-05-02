# RoguelikeSchedulerPreprocessor

**Namespace:** `Torappu.Battle`


## Fields

- `String m_topidId`

- `RoguelikeRetainData m_retainData`


## Methods

- `Void set_randomActionGroups(Dictionary`2)`

- `Void set_mimicEnemyGroups(Dictionary`2)`

- `Void set_mimicTrapGroups(Dictionary`2)`

- `Void set_actionsToDelete(PriorityQueue`1)`

- `String GetPredefinedTokenKey(LevelData, ActionData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RoguelikeSchedulerPreprocessor : SchedulerPreprocessor
{
	private String m_topidId; // 0x10
	private RoguelikeRetainData m_retainData; // 0x18
	private Dictionary`2 m_randomActionGroups; // 0x20
	private Dictionary`2 m_mimicEnemyGroups; // 0x28
	private Dictionary`2 m_mimicTrapGroups; // 0x30
	private PriorityQueue`1 m_actionsToDelete; // 0x38
	private static DelegateBridge __Hotfix0_get_randomActionGroups; // 0x0
	private static DelegateBridge __Hotfix0_set_randomActionGroups; // 0x8
	private static DelegateBridge __Hotfix0_get_mimicEnemyGroups; // 0x10
	private static DelegateBridge __Hotfix0_set_mimicEnemyGroups; // 0x18
	private static DelegateBridge __Hotfix0_get_mimicTrapGroups; // 0x20
	private static DelegateBridge __Hotfix0_set_mimicTrapGroups; // 0x28
	private static DelegateBridge __Hotfix0_get_actionsToDelete; // 0x30
	private static DelegateBridge __Hotfix0_set_actionsToDelete; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40
	private static DelegateBridge __Hotfix0_DoPreprocess; // 0x48
	private static DelegateBridge __Hotfix0_GetPredefinedTokenKey; // 0x50
	private static DelegateBridge __Hotfix0_Dispose; // 0x58

	protected Dictionary`2 randomActionGroups { get; set; }
	protected Dictionary`2 mimicEnemyGroups { get; set; }
	protected Dictionary`2 mimicTrapGroups { get; set; }
	protected PriorityQueue`1 actionsToDelete { get; set; }

	// RVA: 0x40cc41c VA: 0x75966e441c
	protected Dictionary`2 get_randomActionGroups() { }
	// RVA: 0x40cc4e4 VA: 0x75966e44e4
	protected Void set_randomActionGroups(Dictionary`2 value) { }
	// RVA: 0x40cc568 VA: 0x75966e4568
	protected Dictionary`2 get_mimicEnemyGroups() { }
	// RVA: 0x40cc630 VA: 0x75966e4630
	protected Void set_mimicEnemyGroups(Dictionary`2 value) { }
	// RVA: 0x40cc6b4 VA: 0x75966e46b4
	protected Dictionary`2 get_mimicTrapGroups() { }
	// RVA: 0x40cc77c VA: 0x75966e477c
	protected Void set_mimicTrapGroups(Dictionary`2 value) { }
	// RVA: 0x40cc800 VA: 0x75966e4800
	protected PriorityQueue`1 get_actionsToDelete() { }
	// RVA: 0x40cc8c8 VA: 0x75966e48c8
	protected Void set_actionsToDelete(PriorityQueue`1 value) { }
	// RVA: 0x40cc118 VA: 0x75966e4118
	public Void .ctor(RoguelikeInput input) { }
	// RVA: 0x40cc9bc VA: 0x75966e49bc
	public override Void DoPreprocess(LevelData levelData) { }
	// RVA: 0x40cdf68 VA: 0x75966e5f68
	protected String GetPredefinedTokenKey(LevelData levelData, ActionData actionData) { }
	// RVA: 0x40ce0a8 VA: 0x75966e60a8
	public override Void Dispose() { }
}
```