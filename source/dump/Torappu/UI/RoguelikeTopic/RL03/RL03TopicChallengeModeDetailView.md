# RL03TopicChallengeModeDetailView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Text _challengeModeTitleText`

- `Text _challengeModeDesc`

- `Text _challengeModeSubDesc`

- `Text _challengeTargetTitleName`

- `Text _challengeTargetPrefixText`

- `SimpleLayoutContent _taskList`

- `SimpleLayoutContent _rewardList`

- `GameObject _panelRewardNotReceived`

- `GameObject _panelRewardReceived`

- `CanvasGroup _canvasItems`

- `RoguelikeTopicChallengeModeDetailState <bindState>k__BackingField`

- `TaskAdapter m_taskListAdapter`

- `RewardAdapter m_rewardListAdapter`

- `Boolean m_cachedRewardReceived`

- `Boolean m_hasInited`


## Properties

- `RoguelikeTopicChallengeModeDetailState bindState`


## Methods

- `RoguelikeTopicChallengeModeDetailState get_bindState()`

- `Void set_bindState(RoguelikeTopicChallengeModeDetailState)`

- `Void _InitIfNot()`

- `Void _Render(RoguelikeTopicModeViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class RL03TopicChallengeModeDetailView : RoguelikeTopicChallengeModeDetailViewBase
{
	private Text _challengeModeTitleText; // 0x20
	private Text _challengeModeDesc; // 0x28
	private Text _challengeModeSubDesc; // 0x30
	private Text _challengeTargetTitleName; // 0x38
	private Text _challengeTargetPrefixText; // 0x40
	private SimpleLayoutContent _taskList; // 0x48
	private SimpleLayoutContent _rewardList; // 0x50
	private GameObject _panelRewardNotReceived; // 0x58
	private GameObject _panelRewardReceived; // 0x60
	private CanvasGroup _canvasItems; // 0x68
	private RoguelikeTopicChallengeModeDetailState <bindState>k__BackingField; // 0x70
	private TaskAdapter m_taskListAdapter; // 0x78
	private RewardAdapter m_rewardListAdapter; // 0x80
	private List`1 m_cachedTaskList; // 0x88
	private List`1 m_cachedRewardList; // 0x90
	private Boolean m_cachedRewardReceived; // 0x98
	private Boolean m_hasInited; // 0x99
	private static DelegateBridge __Hotfix0_get_bindState; // 0x0
	private static DelegateBridge __Hotfix0_set_bindState; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__Render; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private RoguelikeTopicChallengeModeDetailState bindState { get; set; }

	// RVA: 0x267cbd4 VA: 0x7594c94bd4
	private RoguelikeTopicChallengeModeDetailState get_bindState() { }
	// RVA: 0x267cc3c VA: 0x7594c94c3c
	private Void set_bindState(RoguelikeTopicChallengeModeDetailState value) { }
	// RVA: 0x267ccc0 VA: 0x7594c94cc0
	private Void _InitIfNot() { }
	// RVA: 0x267cf0c VA: 0x7594c94f0c
	public override Void Init(RoguelikeTopicChallengeModeDetailState state) { }
	// RVA: 0x267cf8c VA: 0x7594c94f8c
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x267d040 VA: 0x7594c95040
	private Void _Render(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x267d304 VA: 0x7594c95304
	public Void .ctor() { }
}
```