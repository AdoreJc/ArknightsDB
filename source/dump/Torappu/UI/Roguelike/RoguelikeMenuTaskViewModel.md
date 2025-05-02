# RoguelikeMenuTaskViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String taskId`

- `String taskTitle`

- `String taskDesc`

- `Int32 maxProgress`

- `Int32 currProgress`

- `RoguelikeTaskRarity taskRarity`


## Properties

- `Int32 progress`

- `Boolean isComplete`


## Methods

- `Int32 get_progress()`

- `Boolean get_isComplete()`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuTaskViewModel : RoguelikeMenuCompViewModel
{
	public String taskId; // 0x18
	public String taskTitle; // 0x20
	public String taskDesc; // 0x28
	public Int32 maxProgress; // 0x30
	public Int32 currProgress; // 0x34
	public RoguelikeTaskRarity taskRarity; // 0x38
	private static DelegateBridge __Hotfix0_get_progress; // 0x0
	private static DelegateBridge __Hotfix0_get_isComplete; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Int32 progress { get; }
	public Boolean isComplete { get; }

	// RVA: 0x2a7d6d8 VA: 0x75950956d8
	public Int32 get_progress() { }
	// RVA: 0x2a7d7dc VA: 0x75950957dc
	public Boolean get_isComplete() { }
	// RVA: 0x2a7d85c VA: 0x759509585c
	public override Void LoadData(String topicId) { }
	// RVA: 0x2a7da94 VA: 0x7595095a94
	public Void .ctor() { }
	// RVA: 0x2a7db00 VA: 0x7595095b00
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```