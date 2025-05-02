# RoguelikeClassicEndingStatsRelicGroupViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Methods

- `Void _LoadRelics(String, EndingRecord)`

- `Int32 GetWholeRelicViewModelsCount(CombineParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingStatsRelicGroupViewModel : RoguelikeClassicEndingStatsViewComponentModel
{
	public List`1 relicViewModels; // 0x10
	public List`1 trapViewModels; // 0x18
	public List`1 exploreToolViewModels; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadRelics; // 0x8
	private static DelegateBridge __Hotfix0_LoadWholeRelicViewModelList; // 0x10
	private static DelegateBridge __Hotfix0_GetWholeRelicViewModelsCount; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2a2ec50 VA: 0x7595046c50
	public override Void LoadData(String topicId, EndingResult result) { }
	// RVA: 0x2a2ed8c VA: 0x7595046d8c
	private Void _LoadRelics(String topicId, EndingRecord endingRecord) { }
	// RVA: 0x2a2f228 VA: 0x7595047228
	public List`1 LoadWholeRelicViewModelList(CombineParam combineParam) { }
	// RVA: 0x2a2f5b0 VA: 0x75950475b0
	public Int32 GetWholeRelicViewModelsCount(CombineParam combineParam) { }
	// RVA: 0x2a2f6a0 VA: 0x75950476a0
	public Void .ctor() { }
}
```