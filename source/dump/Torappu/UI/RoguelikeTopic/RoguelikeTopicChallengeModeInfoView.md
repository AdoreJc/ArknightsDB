# RoguelikeTopicChallengeModeInfoView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Image _imgTaskTitle`

- `Text _textTaskTitle`

- `Image _bkgReward`

- `Text _textReward`

- `GameObject _pnlAwardReceived`

- `GameObject _pnlAwardNotReceived`

- `Single _rewardItemScale`

- `Text _textConditionTitle`

- `Boolean m_hasInited`

- `String m_cachedChallengeId`


## Methods

- `Void _InitIfNot()`

- `Void _LoadRewardItemIcon(Int32, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeModeInfoView : RoguelikeTopicChallengeModeInfoViewBase
{
	private Image _imgTaskTitle; // 0x28
	private Text _textTaskTitle; // 0x30
	private ChallengeTaskInfoPanel[] _challengeTaskInfos; // 0x38
	private Image _bkgReward; // 0x40
	private Text _textReward; // 0x48
	private GameObject _pnlAwardReceived; // 0x50
	private GameObject _pnlAwardNotReceived; // 0x58
	private RectTransform[] _itemIconHolder; // 0x60
	private Single _rewardItemScale; // 0x68
	private Text _textConditionTitle; // 0x70
	private ChallengeConditionLine[] _challengeDescLines; // 0x78
	private Boolean m_hasInited; // 0x80
	private UIItemCard[] m_itemCardList; // 0x88
	private String m_cachedChallengeId; // 0x90
	private static DelegateBridge __Hotfix0_InitStyle; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__LoadRewardItemIcon; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x26488a8 VA: 0x7594c608a8
	public override Void InitStyle(RoguelikeTopicChallengeModelStyle style) { }
	// RVA: 0x2648ae0 VA: 0x7594c60ae0
	public override Void Render(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x2648e88 VA: 0x7594c60e88
	private Void _InitIfNot() { }
	// RVA: 0x26494bc VA: 0x7594c614bc
	private Void _LoadRewardItemIcon(Int32 index, List`1 items) { }
	// RVA: 0x2649834 VA: 0x7594c61834
	public Void .ctor() { }
}
```