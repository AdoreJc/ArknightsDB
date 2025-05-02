# RoguelikeTopicChallengeModeDetailView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Text _challengeModeDesc`

- `Text _challengeModeSubDesc`

- `Text _challengeName`

- `SimpleLayoutContent _taskList`

- `SimpleLayoutContent _rewardList`

- `GameObject _pnlAwardReceived`

- `CanvasGroup _canvasItems`

- `Text _challengeModeTitleName`

- `Text _challengeTaskTitleName`

- `Text _challengeTaskTargetTitleName`

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
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeModeDetailView : RoguelikeTopicChallengeModeDetailViewBase
{
	private Text _challengeModeDesc; // 0x20
	private Text _challengeModeSubDesc; // 0x28
	private Text _challengeName; // 0x30
	private SimpleLayoutContent _taskList; // 0x38
	private SimpleLayoutContent _rewardList; // 0x40
	private GameObject _pnlAwardReceived; // 0x48
	private CanvasGroup _canvasItems; // 0x50
	private Text _challengeModeTitleName; // 0x58
	private Text _challengeTaskTitleName; // 0x60
	private Text _challengeTaskTargetTitleName; // 0x68
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

	// RVA: 0x2647808 VA: 0x7594c5f808
	private RoguelikeTopicChallengeModeDetailState get_bindState() { }
	// RVA: 0x2647870 VA: 0x7594c5f870
	private Void set_bindState(RoguelikeTopicChallengeModeDetailState value) { }
	// RVA: 0x26478f4 VA: 0x7594c5f8f4
	private Void _InitIfNot() { }
	// RVA: 0x2647b40 VA: 0x7594c5fb40
	public override Void Init(RoguelikeTopicChallengeModeDetailState state) { }
	// RVA: 0x2647bc0 VA: 0x7594c5fbc0
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x2647c74 VA: 0x7594c5fc74
	private Void _Render(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x2647f30 VA: 0x7594c5ff30
	public Void .ctor() { }
}
```