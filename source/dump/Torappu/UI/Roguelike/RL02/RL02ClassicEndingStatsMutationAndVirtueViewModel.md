# RL02ClassicEndingStatsMutationAndVirtueViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `String topicId`

- `RoguelikeCharBuffModel mutation`


## Methods

- `Int32 GetTotalCount()`

- `Boolean HasMutation()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ClassicEndingStatsMutationAndVirtueViewModel : RoguelikeClassicEndingStatsViewComponentModel
{
	public String topicId; // 0x10
	public RoguelikeCharBuffModel mutation; // 0x18
	public List`1 virtueList; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetTotalCount; // 0x8
	private static DelegateBridge __Hotfix0_HasMutation; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b5ee04 VA: 0x7595176e04
	public override Void LoadData(String topicId, EndingResult result) { }
	// RVA: 0x2b5e714 VA: 0x7595176714
	public Int32 GetTotalCount() { }
	// RVA: 0x2b5ed8c VA: 0x7595176d8c
	public Boolean HasMutation() { }
	// RVA: 0x2b5f0b0 VA: 0x75951770b0
	public Void .ctor() { }
}
```