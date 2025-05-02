# SandboxV2RiftSettleView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `TwoStateToggle _leftMainToggle`

- `Text _mainTargetTitle`

- `GameObject _difficultyGo`

- `Text _difficultyLevel`

- `Text _portHpPercent`

- `UIAtlasImage _portHpBg`

- `Color _hpTextSafe`

- `Color _hpTextDanger`

- `Color _hpBgSafe`

- `Color _hpBgDanger`

- `TwoStateToggle _portToggle`

- `Text _teamName`

- `Image _teamIcon`

- `Text _stayDayCount`

- `TwoStateToggle _mainTargetToggle`

- `Text _mainTargetDesc`

- `Text _mainTargetProgress`

- `TwoStateToggle _subTargetToggle`

- `Text _subTargetDesc`

- `Text _subTargetProgress`

- `GameObject _rewardIcon`

- `GameObject _mainRewardGo`

- `SimpleLayoutContent _mainRewardContent`

- `UIAnimationLocation _mainRewardTitleAnim`

- `GameObject _subRewardGo`

- `SimpleLayoutContent _subRewardContent`

- `UIAnimationLocation _subRewardTitleAnim`

- `Text _mainRewardTitleWhite`

- `Text _mainRewardTitleColor`

- `RectTransform _backClickArea`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _leftTargetLoopAnim`

- `UIAnimationLocation _confirmBtnAnim`

- `Single _rewardShowDelay`

- `Single _rewardCanSkipTime`

- `Single _rewardShowInterval`

- `Int32 _rewardTitleShowCount`

- `Boolean m_hasInited`

- `SandboxV2RiftSettleViewModel m_model`

- `RewardAdapter m_mainRewardAdapter`

- `RewardAdapter m_subRewardAdapter`

- `Tween m_tween`

- `Tween m_mainRewardTitleTween`

- `Tween m_subRewardTitleTween`

- `UIStateFinder m_stateFinder`

- `InternalState m_state`

- `UIPageFinder m_pageFinder`

- `Coroutine m_rewardAppearCoroutine`


## Methods

- `Void _InitIfNot()`

- `Void OnConfirmClicked()`

- `Void OnBackgroundClicked()`

- `IEnumerator _UpdateInternalStateCoroutine()`

- `Void _OnEnterAnimComplete()`

- `Void _OnRewardAppearAnimComplete()`

- `Void _OnConfirmBtnAnimComplete()`

- `Void _JumpToRewardShowAnimEnd()`

- `IEnumerator _PlayRewardShowAnim()`

- `Void _PlayAnim(ref, ref, Single, TweenCallback)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftSettleView : DataBinder`1
{
	private const String PORT_HP_FORMAT; // 0x0
	private TwoStateToggle _leftMainToggle; // 0x20
	private Text _mainTargetTitle; // 0x28
	private GameObject _difficultyGo; // 0x30
	private Text _difficultyLevel; // 0x38
	private Text _portHpPercent; // 0x40
	private UIAtlasImage _portHpBg; // 0x48
	private Color _hpTextSafe; // 0x50
	private Color _hpTextDanger; // 0x60
	private Color _hpBgSafe; // 0x70
	private Color _hpBgDanger; // 0x80
	private TwoStateToggle _portToggle; // 0x90
	private Text _teamName; // 0x98
	private Image _teamIcon; // 0xa0
	private Text _stayDayCount; // 0xa8
	private TwoStateToggle _mainTargetToggle; // 0xb0
	private Text _mainTargetDesc; // 0xb8
	private Text _mainTargetProgress; // 0xc0
	private TwoStateToggle _subTargetToggle; // 0xc8
	private Text _subTargetDesc; // 0xd0
	private Text _subTargetProgress; // 0xd8
	private GameObject[] _hideWhenNoSubTarget; // 0xe0
	private GameObject _rewardIcon; // 0xe8
	private GameObject _mainRewardGo; // 0xf0
	private SimpleLayoutContent _mainRewardContent; // 0xf8
	private UIAnimationLocation _mainRewardTitleAnim; // 0x100
	private GameObject _subRewardGo; // 0x110
	private SimpleLayoutContent _subRewardContent; // 0x118
	private UIAnimationLocation _subRewardTitleAnim; // 0x120
	private Text _mainRewardTitleWhite; // 0x130
	private Text _mainRewardTitleColor; // 0x138
	private RectTransform _backClickArea; // 0x140
	private UIAnimationLocation _enterAnim; // 0x148
	private UIAnimationLocation _leftTargetLoopAnim; // 0x158
	private UIAnimationLocation _confirmBtnAnim; // 0x168
	private Single _rewardShowDelay; // 0x178
	private Single _rewardCanSkipTime; // 0x17c
	private Single _rewardShowInterval; // 0x180
	private Int32 _rewardTitleShowCount; // 0x184
	private Boolean m_hasInited; // 0x188
	private SandboxV2RiftSettleViewModel m_model; // 0x190
	private RewardAdapter m_mainRewardAdapter; // 0x198
	private RewardAdapter m_subRewardAdapter; // 0x1a0
	private Tween m_tween; // 0x1a8
	private Tween m_mainRewardTitleTween; // 0x1b0
	private Tween m_subRewardTitleTween; // 0x1b8
	private UIStateFinder m_stateFinder; // 0x1c0
	private InternalState m_state; // 0x1d0
	private UIPageFinder m_pageFinder; // 0x1d8
	private Coroutine m_rewardAppearCoroutine; // 0x1e8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnBackgroundClicked; // 0x18
	private static DelegateBridge __Hotfix0__UpdateInternalStateCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__OnEnterAnimComplete; // 0x28
	private static DelegateBridge __Hotfix0__OnRewardAppearAnimComplete; // 0x30
	private static DelegateBridge __Hotfix0__OnConfirmBtnAnimComplete; // 0x38
	private static DelegateBridge __Hotfix0__JumpToRewardShowAnimEnd; // 0x40
	private static DelegateBridge __Hotfix0__PlayRewardShowAnim; // 0x48
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x251bb94 VA: 0x7594b33b94
	public override Void OnValueChanged(SandboxV2RiftSettleProperty property) { }
	// RVA: 0x251c378 VA: 0x7594b34378
	private Void _InitIfNot() { }
	// RVA: 0x251c720 VA: 0x7594b34720
	public Void OnConfirmClicked() { }
	// RVA: 0x251c7d0 VA: 0x7594b347d0
	public Void OnBackgroundClicked() { }
	// RVA: 0x251c674 VA: 0x7594b34674
	private IEnumerator _UpdateInternalStateCoroutine() { }
	// RVA: 0x251c9cc VA: 0x7594b349cc
	private Void _OnEnterAnimComplete() { }
	// RVA: 0x251ca38 VA: 0x7594b34a38
	private Void _OnRewardAppearAnimComplete() { }
	// RVA: 0x251caa4 VA: 0x7594b34aa4
	private Void _OnConfirmBtnAnimComplete() { }
	// RVA: 0x251c850 VA: 0x7594b34850
	private Void _JumpToRewardShowAnimEnd() { }
	// RVA: 0x251cc68 VA: 0x7594b34c68
	private IEnumerator _PlayRewardShowAnim() { }
	// RVA: 0x251cd3c VA: 0x7594b34d3c
	private Void _PlayAnim(ref UIAnimationLocation anim, ref Tween tween, Single delay, TweenCallback callback) { }
	// RVA: 0x251cee4 VA: 0x7594b34ee4
	public Void .ctor() { }
}
```