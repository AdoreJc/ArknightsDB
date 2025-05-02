# RoguelikeClassicEndingViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String theme`

- `RoguelikeTopicMode mode`

- `Int32 grade`

- `Boolean isSuccess`

- `String endingId`

- `String failEndingId`

- `Boolean needPopReport`

- `String endingFrameDetail`

- `RoguelikeTopicDetail topicDetail`

- `RoguelikeTopicCustomizeData topicCustomize`

- `GameSettleOuterInfo gameSettleOuterInfo`

- `String seed`

- `String copySeedFormat`

- `String copySucceededTextHint`

- `Boolean isShowSeed`

- `Boolean <hideEndingStory>k__BackingField`


## Properties

- `Boolean hideEndingStory`


## Methods

- `Boolean get_hideEndingStory()`

- `Void set_hideEndingStory(Boolean)`

- `Void LoadDataFromResponse(String, RoguelikeTopicGameSettleResponse)`

- `Void AddPageViewModel(ViewType, RoguelikeClassicEndingPageViewModel)`

- `RoguelikeClassicEndingPageViewModel GetPageViewModel(ViewType)`

- `Void _LoadRogueActivitySeed(String, EndingBrief)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingViewModel : RoguelikeEndingViewModel
{
	private Dictionary`2 m_data; // 0x10
	public String theme; // 0x18
	public RoguelikeTopicMode mode; // 0x20
	public Int32 grade; // 0x24
	public Boolean isSuccess; // 0x28
	public String endingId; // 0x30
	public String failEndingId; // 0x38
	public Boolean needPopReport; // 0x40
	public String endingFrameDetail; // 0x48
	public RoguelikeTopicDetail topicDetail; // 0x50
	public RoguelikeTopicCustomizeData topicCustomize; // 0x58
	public GameSettleOuterInfo gameSettleOuterInfo; // 0x60
	public String seed; // 0x68
	public String copySeedFormat; // 0x70
	public String copySucceededTextHint; // 0x78
	public Boolean isShowSeed; // 0x80
	private Boolean <hideEndingStory>k__BackingField; // 0x81
	private static DelegateBridge __Hotfix0_get_hideEndingStory; // 0x0
	private static DelegateBridge __Hotfix0_set_hideEndingStory; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_LoadDataFromResponse; // 0x18
	private static DelegateBridge __Hotfix0_AddPageViewModel; // 0x20
	private static DelegateBridge __Hotfix0_GetPageViewModel; // 0x28
	private static DelegateBridge __Hotfix0__LoadRogueActivitySeed; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean hideEndingStory { get; set; }

	// RVA: 0x2a2f874 VA: 0x7595047874
	public Boolean get_hideEndingStory() { }
	// RVA: 0x2a2f8dc VA: 0x75950478dc
	private Void set_hideEndingStory(Boolean value) { }
	// RVA: 0x2a2f95c VA: 0x759504795c
	public override Void LoadData(String topicId) { }
	// RVA: 0x2a3007c VA: 0x759504807c
	public Void LoadDataFromResponse(String topicId, RoguelikeTopicGameSettleResponse response) { }
	// RVA: 0x2a3022c VA: 0x759504822c
	public Void AddPageViewModel(ViewType viewType, RoguelikeClassicEndingPageViewModel viewModel) { }
	// RVA: 0x2a30318 VA: 0x7595048318
	public RoguelikeClassicEndingPageViewModel GetPageViewModel(ViewType viewType) { }
	// RVA: 0x2a2fe68 VA: 0x7595047e68
	private Void _LoadRogueActivitySeed(String topicId, EndingBrief brief) { }
	// RVA: 0x2a303cc VA: 0x75950483cc
	public Void .ctor() { }
}
```