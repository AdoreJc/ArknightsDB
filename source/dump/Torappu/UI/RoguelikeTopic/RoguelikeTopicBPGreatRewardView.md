# RoguelikeTopicBPGreatRewardView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `GameObject _panelReward`

- `Image _rewardImg`

- `UIAtlasImage _dustImg`

- `GameObject _panelValidLevel`

- `GameObject _panelValidDate`

- `Text _levelLabel`

- `Text _levelText`

- `Text _yearText`

- `Text _monthText`

- `Text _acquireTitleText`

- `Text _rewardNameText`

- `Text _rewardInfoText`

- `GameObject _panelCheckBtn`

- `GameObject _panelReceivedState`

- `GameObject _panelLeftArrow`

- `GameObject _panelRightArrow`

- `GameObject _btnRewardDetailGo`

- `UIAnimationLocation _switchAnim`

- `GameObject _panelNotReceived`

- `GameObject _panelCanReceive`

- `GameObject _panelPurchase`

- `Text _textReceive`

- `Action onLeftArrowClick`

- `Action onRightArrowClick`

- `Int32 m_cachedSelectPos`

- `Int32 m_milestoneLevel`

- `CharUISkinStruct m_charUISkinStruct`

- `UICharacterIllust m_charIllust`

- `RoguelikeTopicBPPrizeViewModel m_cachedSelectPrizeModel`

- `RoguelikeTopicBattlePassState <bindState>k__BackingField`


## Properties

- `RoguelikeTopicBattlePassState bindState`


## Methods

- `RoguelikeTopicBattlePassState get_bindState()`

- `Void set_bindState(RoguelikeTopicBattlePassState)`

- `Void Init(RoguelikeTopicBattlePassState)`

- `Void _RenderView(RoguelikeTopicBPGrandPrizeViewModel)`

- `Void _RenderGrandPrizeState(RoguelikeTopicBPGrandPrizeViewModel)`

- `Void PlaySwitchAnim(Boolean, TweenCallback)`

- `Void OnCheckBtnClick()`

- `Void OnLeftArrowClick()`

- `Void OnRightArrowClick()`

- `Void OnBtnRewardDetailClick()`

- `Void OnPurchaseGrandPrizeClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBPGreatRewardView : DataBinder`1
{
	private GameObject _panelReward; // 0x20
	private Image _rewardImg; // 0x28
	private UIAtlasImage _dustImg; // 0x30
	private GameObject _panelValidLevel; // 0x38
	private GameObject _panelValidDate; // 0x40
	private Text _levelLabel; // 0x48
	private Text _levelText; // 0x50
	private Text _yearText; // 0x58
	private Text _monthText; // 0x60
	private Text _acquireTitleText; // 0x68
	private Text _rewardNameText; // 0x70
	private Text _rewardInfoText; // 0x78
	private GameObject _panelCheckBtn; // 0x80
	private GameObject _panelReceivedState; // 0x88
	private GameObject _panelLeftArrow; // 0x90
	private GameObject _panelRightArrow; // 0x98
	private GameObject _btnRewardDetailGo; // 0xa0
	private UIAnimationLocation _switchAnim; // 0xa8
	private GameObject _panelNotReceived; // 0xb8
	private GameObject _panelCanReceive; // 0xc0
	private GameObject _panelPurchase; // 0xc8
	private Text _textReceive; // 0xd0
	public Action`1 onCheckBtnClick; // 0xd8
	public Action onLeftArrowClick; // 0xe0
	public Action onRightArrowClick; // 0xe8
	public Action`1 onRewardDetailClick; // 0xf0
	public Action`1 onPurchaseGrandPrizeClick; // 0xf8
	private Int32 m_cachedSelectPos; // 0x100
	private Int32 m_milestoneLevel; // 0x104
	private CharUISkinStruct m_charUISkinStruct; // 0x108
	private UICharacterIllust m_charIllust; // 0x118
	private RoguelikeTopicBPPrizeViewModel m_cachedSelectPrizeModel; // 0x120
	private RoguelikeTopicBattlePassState <bindState>k__BackingField; // 0x128
	private static DelegateBridge __Hotfix0_get_bindState; // 0x0
	private static DelegateBridge __Hotfix0_set_bindState; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__RenderView; // 0x20
	private static DelegateBridge __Hotfix0__RenderGrandPrizeState; // 0x28
	private static DelegateBridge __Hotfix0_PlaySwitchAnim; // 0x30
	private static DelegateBridge __Hotfix0_OnCheckBtnClick; // 0x38
	private static DelegateBridge __Hotfix0_OnLeftArrowClick; // 0x40
	private static DelegateBridge __Hotfix0_OnRightArrowClick; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnRewardDetailClick; // 0x50
	private static DelegateBridge __Hotfix0_OnPurchaseGrandPrizeClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private RoguelikeTopicBattlePassState bindState { get; set; }

	// RVA: 0x2643098 VA: 0x7594c5b098
	private RoguelikeTopicBattlePassState get_bindState() { }
	// RVA: 0x2643100 VA: 0x7594c5b100
	private Void set_bindState(RoguelikeTopicBattlePassState value) { }
	// RVA: 0x263fe04 VA: 0x7594c57e04
	public Void Init(RoguelikeTopicBattlePassState state) { }
	// RVA: 0x2643184 VA: 0x7594c5b184
	public override Void OnValueChanged(RoguelikeTopicBPGreatPrizeProperty property) { }
	// RVA: 0x2643428 VA: 0x7594c5b428
	private Void _RenderView(RoguelikeTopicBPGrandPrizeViewModel viewModel) { }
	// RVA: 0x2643284 VA: 0x7594c5b284
	private Void _RenderGrandPrizeState(RoguelikeTopicBPGrandPrizeViewModel viewModel) { }
	// RVA: 0x26401d0 VA: 0x7594c581d0
	public Void PlaySwitchAnim(Boolean isReverse, TweenCallback callback) { }
	// RVA: 0x2643930 VA: 0x7594c5b930
	public Void OnCheckBtnClick() { }
	// RVA: 0x26439b8 VA: 0x7594c5b9b8
	public Void OnLeftArrowClick() { }
	// RVA: 0x2643a3c VA: 0x7594c5ba3c
	public Void OnRightArrowClick() { }
	// RVA: 0x2643ac0 VA: 0x7594c5bac0
	public Void OnBtnRewardDetailClick() { }
	// RVA: 0x2643b4c VA: 0x7594c5bb4c
	public Void OnPurchaseGrandPrizeClick() { }
	// RVA: 0x2643bd8 VA: 0x7594c5bbd8
	public Void .ctor() { }
}
```