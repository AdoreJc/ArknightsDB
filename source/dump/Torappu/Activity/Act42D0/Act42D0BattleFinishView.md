# Act42D0BattleFinishView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `UIAnimationLocation _animRatingEnter`

- `UIAnimationLocation _animSquadEnter`

- `UIAnimationLocation _animRewardEnter`

- `CanvasGroup _ratingPanel`

- `CanvasGroup _squadPanel`

- `UIBlurFloatPanel _rewardBlurPanel`

- `RectTransform _illustContainer`

- `Text _textStageName`

- `Text _textPlayerName`

- `Text _textFinishTime`

- `RectTransform _avatarContainer`

- `SimpleLayoutContent _charList`

- `Text _textRatingDesc`

- `Text _textRewardCount`

- `Text _textRewardLv`

- `Text _textRewardProgress`

- `Slider _rewardSlider`

- `Single _sliderTweenDuration`

- `Image _imgItemIcon`

- `Text _textRewardCaption`

- `Image _imgDisplayIcon`

- `NormalBattleUI _normalBattleUI`

- `ChallengeBattleUI _challengeBattleUI`

- `Single _fadeDuration`

- `Act42D0BattleFinishViewModel m_viewModel`

- `FadeSwitchTween m_ratingSwitchTween`

- `FadeSwitchTween m_squadSwitchTween`

- `DisplayState m_displayState`

- `CharListAdapter m_adapter`

- `PlayerAvatarView m_avatar`


## Methods

- `Void _RenderRatingView()`

- `Void _RenderSquadView()`

- `Void _RenderRewardView()`

- `Void _PlayRatingSignal()`

- `DisplayState _FindInitState(Act42D0BattleFinishViewModel)`

- `Void _JumpToActivity()`

- `Void EventOnViewClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0BattleFinishView : ActivityBattleFinishView
{
	private UIAnimationLocation _animRatingEnter; // 0x30
	private UIAnimationLocation _animSquadEnter; // 0x40
	private UIAnimationLocation _animRewardEnter; // 0x50
	private CanvasGroup _ratingPanel; // 0x60
	private CanvasGroup _squadPanel; // 0x68
	private UIBlurFloatPanel _rewardBlurPanel; // 0x70
	private RectTransform _illustContainer; // 0x78
	private Text _textStageName; // 0x80
	private Text _textPlayerName; // 0x88
	private Text _textFinishTime; // 0x90
	private RectTransform _avatarContainer; // 0x98
	private SimpleLayoutContent _charList; // 0xa0
	private Text _textRatingDesc; // 0xa8
	private GameObject[] _ratingList; // 0xb0
	private Text _textRewardCount; // 0xb8
	private Text _textRewardLv; // 0xc0
	private Text _textRewardProgress; // 0xc8
	private Slider _rewardSlider; // 0xd0
	private Single _sliderTweenDuration; // 0xd8
	private Image _imgItemIcon; // 0xe0
	private Text _textRewardCaption; // 0xe8
	private Image _imgDisplayIcon; // 0xf0
	private NormalBattleUI _normalBattleUI; // 0xf8
	private ChallengeBattleUI _challengeBattleUI; // 0x100
	private Single _fadeDuration; // 0x108
	private Act42D0BattleFinishViewModel m_viewModel; // 0x110
	private FadeSwitchTween m_ratingSwitchTween; // 0x118
	private FadeSwitchTween m_squadSwitchTween; // 0x120
	private DisplayState m_displayState; // 0x128
	private CharListAdapter m_adapter; // 0x130
	private PlayerAvatarView m_avatar; // 0x138
	private static DelegateBridge __Hotfix0__RenderRatingView; // 0x0
	private static DelegateBridge __Hotfix0__RenderSquadView; // 0x8
	private static DelegateBridge __Hotfix0__RenderRewardView; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0__PlayRatingSignal; // 0x20
	private static DelegateBridge __Hotfix0__FindInitState; // 0x28
	private static DelegateBridge __Hotfix0__JumpToActivity; // 0x30
	private static DelegateBridge __Hotfix0_EventOnViewClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3205160 VA: 0x759581d160
	private Void _RenderRatingView() { }
	// RVA: 0x3205438 VA: 0x759581d438
	private Void _RenderSquadView() { }
	// RVA: 0x3206028 VA: 0x759581e028
	private Void _RenderRewardView() { }
	// RVA: 0x32065e8 VA: 0x759581e5e8
	protected override Void OnInit() { }
	// RVA: 0x3206c18 VA: 0x759581ec18
	private Void _PlayRatingSignal() { }
	// RVA: 0x3206a9c VA: 0x759581ea9c
	private DisplayState _FindInitState(Act42D0BattleFinishViewModel viewModel) { }
	// RVA: 0x3206ed8 VA: 0x759581eed8
	private Void _JumpToActivity() { }
	// RVA: 0x3206f3c VA: 0x759581ef3c
	public Void EventOnViewClick() { }
	// RVA: 0x3207020 VA: 0x759581f020
	public Void .ctor() { }
}
```