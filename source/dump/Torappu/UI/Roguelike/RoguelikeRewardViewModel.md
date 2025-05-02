# RoguelikeRewardViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Int32 curDepth`

- `Int32 curIndex`

- `RoguelikeStageEarn earn`

- `String showCharInstId`

- `Int32 battleResultState`

- `Int32 battleIsPerfect`

- `RoguelikeDungeonZone curZone`

- `String topicId`

- `Int32 initPredefinedStyle`


## Properties

- `RoguelikeDungeonNode curNode`


## Methods

- `RoguelikeDungeonNode get_curNode()`

- `Void LoadData(String)`

- `Boolean IsUseSpExpStyle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardViewModel : IHotfixable
{
	public Int32 curDepth; // 0x10
	public Int32 curIndex; // 0x14
	public List`1 rewards; // 0x18
	public RoguelikeStageEarn earn; // 0x20
	public String showCharInstId; // 0x28
	public Int32 battleResultState; // 0x30
	public Int32 battleIsPerfect; // 0x34
	public RoguelikeDungeonZone curZone; // 0x38
	public String topicId; // 0x40
	public Int32 initPredefinedStyle; // 0x48
	private static DelegateBridge __Hotfix0_get_curNode; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_IsUseSpExpStyle; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public RoguelikeDungeonNode curNode { get; }

	// RVA: 0x2a98564 VA: 0x75950b0564
	public RoguelikeDungeonNode get_curNode() { }
	// RVA: 0x2aa5b44 VA: 0x75950bdb44
	public Void LoadData(String topicId) { }
	// RVA: 0x2a98b84 VA: 0x75950b0b84
	public Boolean IsUseSpExpStyle() { }
	// RVA: 0x2aa5d64 VA: 0x75950bdd64
	public Void .ctor() { }
}
```