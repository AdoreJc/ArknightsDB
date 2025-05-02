# RoguelikeClassicEndingStatsViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Methods

- `Void AddCompViewModel(Type)`

- `RoguelikeClassicEndingStatsViewComponentModel GetCompViewModel(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingStatsViewModel : RoguelikeClassicEndingPageViewModel
{
	private Dictionary`2 m_data; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_LoadFromResponse; // 0x8
	private static DelegateBridge __Hotfix0_CheckNeedBpView; // 0x10
	private static DelegateBridge __Hotfix0_GeneEndingBpAndGpViewModel; // 0x18
	private static DelegateBridge __Hotfix0_GetRewardItemList; // 0x20
	private static DelegateBridge __Hotfix0_AddCompViewModel; // 0x28
	private static DelegateBridge __Hotfix0_GetCompViewModel; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2a2dd8c VA: 0x7595045d8c
	public override Void LoadData(String topicId, EndingResult result) { }
	// RVA: 0x2a2df28 VA: 0x7595045f28
	public override Void LoadFromResponse(String topicId, RoguelikeTopicGameSettleResponse response) { }
	// RVA: 0x2a2dfa8 VA: 0x7595045fa8
	public override Boolean CheckNeedBpView() { }
	// RVA: 0x2a2e00c VA: 0x759504600c
	public override Model GeneEndingBpAndGpViewModel() { }
	// RVA: 0x2a2e09c VA: 0x759504609c
	public override List`1 GetRewardItemList() { }
	// RVA: 0x2a29328 VA: 0x7595041328
	public Void AddCompViewModel(Type type) { }
	// RVA: 0x2a28d94 VA: 0x7595040d94
	public RoguelikeClassicEndingStatsViewComponentModel GetCompViewModel(Type type) { }
	// RVA: 0x2a29264 VA: 0x7595041264
	public Void .ctor() { }
}
```