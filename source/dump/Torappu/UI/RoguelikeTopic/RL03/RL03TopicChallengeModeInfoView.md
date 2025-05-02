# RL03TopicChallengeModeInfoView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Text _textTaskTitle`

- `GameObject _taskCompletePanel`

- `GameObject _taskIncompletePanel`

- `Text _textClaimReward`

- `Text _textRewardClaimed`

- `GameObject _panelRewardClaimed`

- `GameObject _panelRewardUnclaimed`

- `Single _rewardItemScale`

- `Text _textConditionTitle`

- `GameObject _challengeBookNormalPanel`

- `GameObject _challengeBookLockedPanel`

- `GameObject _challengeBookNewPanel`

- `Boolean m_hasInited`

- `String m_cachedChallengeId`

- `Boolean m_cachedChallengeBookAccessible`


## Methods

- `Void OnOpenChallengeBookEvent()`

- `Void _InitIfNot()`

- `Void _LoadRewardItemIcon(Int32, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class RL03TopicChallengeModeInfoView : RoguelikeTopicChallengeModeInfoViewBase
{
	private Text _textTaskTitle; // 0x28
	private ChallengeTaskInfoPanel[] _challengeTaskInfos; // 0x30
	private GameObject _taskCompletePanel; // 0x38
	private GameObject _taskIncompletePanel; // 0x40
	private Text _textClaimReward; // 0x48
	private Text _textRewardClaimed; // 0x50
	private GameObject _panelRewardClaimed; // 0x58
	private GameObject _panelRewardUnclaimed; // 0x60
	private RectTransform[] _itemIconHolder; // 0x68
	private Single _rewardItemScale; // 0x70
	private Text _textConditionTitle; // 0x78
	private ChallengeConditionLine[] _challengeDescLines; // 0x80
	private GameObject _challengeBookNormalPanel; // 0x88
	private GameObject _challengeBookLockedPanel; // 0x90
	private GameObject _challengeBookNewPanel; // 0x98
	private Boolean m_hasInited; // 0xa0
	private UIItemCard[] m_itemCardList; // 0xa8
	private String m_cachedChallengeId; // 0xb0
	private Boolean m_cachedChallengeBookAccessible; // 0xb8
	private static DelegateBridge __Hotfix0_OnOpenChallengeBookEvent; // 0x0
	private static DelegateBridge __Hotfix0_InitStyle; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__LoadRewardItemIcon; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x267d818 VA: 0x7594c95818
	public Void OnOpenChallengeBookEvent() { }
	// RVA: 0x267da14 VA: 0x7594c95a14
	public override Void InitStyle(RoguelikeTopicChallengeModelStyle style) { }
	// RVA: 0x267da8c VA: 0x7594c95a8c
	public override Void Render(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x267dec0 VA: 0x7594c95ec0
	private Void _InitIfNot() { }
	// RVA: 0x267e258 VA: 0x7594c96258
	private Void _LoadRewardItemIcon(Int32 index, List`1 items) { }
	// RVA: 0x267e5d0 VA: 0x7594c965d0
	public Void .ctor() { }
}
```