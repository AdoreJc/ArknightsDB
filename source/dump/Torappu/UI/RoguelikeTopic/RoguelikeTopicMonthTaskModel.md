# RoguelikeTopicMonthTaskModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Int32 m_position`

- `RoguelikeTopicMonthMission m_taskData`

- `Int32 m_progress`

- `Int32 m_target`

- `Int32 m_state`

- `Boolean m_bpMax`


## Properties

- `Int32 position`

- `RoguelikeTopicMonthMission taskData`

- `Int32 progress`

- `Int32 target`

- `Boolean isCompleted`


## Methods

- `Int32 get_position()`

- `RoguelikeTopicMonthMission get_taskData()`

- `Int32 get_progress()`

- `Int32 get_target()`

- `Boolean get_isCompleted()`

- `Void LoadData(Int32, RoguelikeTopicMonthMission, Int32, Int32, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthTaskModel : IHotfixable
{
	private Int32 m_position; // 0x10
	private RoguelikeTopicMonthMission m_taskData; // 0x18
	private Int32 m_progress; // 0x20
	private Int32 m_target; // 0x24
	private Int32 m_state; // 0x28
	private Boolean m_bpMax; // 0x2c
	private static DelegateBridge __Hotfix0_get_position; // 0x0
	private static DelegateBridge __Hotfix0_get_taskData; // 0x8
	private static DelegateBridge __Hotfix0_get_progress; // 0x10
	private static DelegateBridge __Hotfix0_get_target; // 0x18
	private static DelegateBridge __Hotfix0_get_isCompleted; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 position { get; }
	public RoguelikeTopicMonthMission taskData { get; }
	public Int32 progress { get; }
	public Int32 target { get; }
	public Boolean isCompleted { get; }

	// RVA: 0x265a368 VA: 0x7594c72368
	public Int32 get_position() { }
	// RVA: 0x265b5a4 VA: 0x7594c735a4
	public RoguelikeTopicMonthMission get_taskData() { }
	// RVA: 0x265b60c VA: 0x7594c7360c
	public Int32 get_progress() { }
	// RVA: 0x265b674 VA: 0x7594c73674
	public Int32 get_target() { }
	// RVA: 0x265b0dc VA: 0x7594c730dc
	public Boolean get_isCompleted() { }
	// RVA: 0x265b008 VA: 0x7594c73008
	public Void LoadData(Int32 pos, RoguelikeTopicMonthMission taskData, Int32 progress, Int32 target, Int32 state, Boolean isBpMax) { }
	// RVA: 0x265af98 VA: 0x7594c72f98
	public Void .ctor() { }
}
```