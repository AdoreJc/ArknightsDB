# RoguelikeTopicBattlePassViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Int32 curBpPoint`

- `RoguelikeTopicBPTopViewModel topViewModel`

- `RoguelikeTopicBattlePassStyle style`


## Methods

- `Int32 GetIndexByLevel(Int32)`

- `Int32 GetTotalCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassViewModel : IHotfixable
{
	public List`1 milestoneViewModelList; // 0x10
	public Int32 curBpPoint; // 0x18
	public RoguelikeTopicBPTopViewModel topViewModel; // 0x20
	public RoguelikeTopicBattlePassStyle style; // 0x28
	public List`1 obtainableRewardList; // 0x30
	private static DelegateBridge __Hotfix0_GetIndexByLevel; // 0x0
	private static DelegateBridge __Hotfix0_GetTotalCount; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2676960 VA: 0x7594c8e960
	public Int32 GetIndexByLevel(Int32 level) { }
	// RVA: 0x2676d0c VA: 0x7594c8ed0c
	public Int32 GetTotalCount() { }
	// RVA: 0x2676168 VA: 0x7594c8e168
	public Void .ctor() { }
}
```