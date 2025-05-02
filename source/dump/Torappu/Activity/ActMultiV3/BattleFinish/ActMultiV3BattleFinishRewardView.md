# ActMultiV3BattleFinishRewardView

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `Image _imgItemIcon1`

- `Image _imgItemIcon2`

- `Image _imgSeasonIcon`

- `Image _imgSeasonIcon2`

- `GameObject _rewardPanelGO`

- `GameObject _complexRewardGO`

- `GameObject _normalRewardGO`

- `Text _textNormalReward1`

- `Text _textNormalReward2`

- `Text _textDailyReward`

- `Text _textDailyProgressCurr`

- `Text _textDailyProgressMax`

- `UIAnimationLocation _animDailyReward`

- `Text _textMilestoneLv`

- `Text _textMilestoneProgressCurr`

- `Text _textMilestoneProgressMax`

- `Text _textMilestoneAdd`

- `Color _colorMilestoneAddNormal`

- `Color _colorMilestoneAddMax`

- `Slider _sliderMilestone`

- `UIAnimationLocation _animMilestoneLvUp`

- `Single _milestoneTweenDuration`

- `Boolean m_hasInited`

- `Tween m_showTween`

- `Tween m_lvUpTween`

- `ActMultiV3BattleFinishViewModel m_viewModel`

- `Int32 m_tweenMilestoneVal`

- `Int32 m_tweenMilestoneLv`


## Methods

- `Void Render(ActMultiV3BattleFinishViewModel)`

- `Void _RenderMilestone(ActMultiV3BattleFinishMilestoneInfo)`

- `Void _InitIfNot()`

- `Tween GenerateShowTween()`

- `Void _UpdateMilestone(Int32)`

- `Int32 <GenerateShowTween>b__33_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishRewardView : MonoBehaviour, IHotfixable
{
	private const String REWARD_DISPLAY_STR; // 0x0
	private const String MILESTONE_PROGRESS_MAX; // 0x0
	private Image _imgItemIcon1; // 0x18
	private Image _imgItemIcon2; // 0x20
	private Image _imgSeasonIcon; // 0x28
	private Image _imgSeasonIcon2; // 0x30
	private GameObject _rewardPanelGO; // 0x38
	private GameObject _complexRewardGO; // 0x40
	private GameObject _normalRewardGO; // 0x48
	private Text _textNormalReward1; // 0x50
	private Text _textNormalReward2; // 0x58
	private Text _textDailyReward; // 0x60
	private Text _textDailyProgressCurr; // 0x68
	private Text _textDailyProgressMax; // 0x70
	private UIAnimationLocation _animDailyReward; // 0x78
	private Text _textMilestoneLv; // 0x88
	private Text _textMilestoneProgressCurr; // 0x90
	private Text _textMilestoneProgressMax; // 0x98
	private Text _textMilestoneAdd; // 0xa0
	private Color _colorMilestoneAddNormal; // 0xa8
	private Color _colorMilestoneAddMax; // 0xb8
	private Slider _sliderMilestone; // 0xc8
	private UIAnimationLocation _animMilestoneLvUp; // 0xd0
	private Single _milestoneTweenDuration; // 0xe0
	private Boolean m_hasInited; // 0xe4
	private Tween m_showTween; // 0xe8
	private Tween m_lvUpTween; // 0xf0
	private ActMultiV3BattleFinishViewModel m_viewModel; // 0xf8
	private Int32 m_tweenMilestoneVal; // 0x100
	private Int32 m_tweenMilestoneLv; // 0x104
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderMilestone; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x18
	private static DelegateBridge __Hotfix0__UpdateMilestone; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3183ea0 VA: 0x759579bea0
	public Void Render(ActMultiV3BattleFinishViewModel viewModel) { }
	// RVA: 0x318485c VA: 0x759579c85c
	private Void _RenderMilestone(ActMultiV3BattleFinishMilestoneInfo milestoneInfo) { }
	// RVA: 0x3184228 VA: 0x759579c228
	private Void _InitIfNot() { }
	// RVA: 0x3184b88 VA: 0x759579cb88
	public Tween GenerateShowTween() { }
	// RVA: 0x3184ef4 VA: 0x759579cef4
	private Void _UpdateMilestone(Int32 milestonePoint) { }
	// RVA: 0x3185040 VA: 0x759579d040
	public Void .ctor() { }
	// RVA: 0x31850b8 VA: 0x759579d0b8
	private Int32 <GenerateShowTween>b__33_0() { }
}
```