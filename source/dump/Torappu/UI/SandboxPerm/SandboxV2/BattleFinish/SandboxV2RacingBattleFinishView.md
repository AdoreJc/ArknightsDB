# SandboxV2RacingBattleFinishView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2.BattleFinish`


## Fields

- `RectTransform _backRt`

- `UIAnimationLocation _animEnter`

- `Text _textStageName`

- `Text _textMyPos`

- `GameObject _unfinishedPosGo`

- `Text _textCompleteTime`

- `GameObject _newBestTimeGo`

- `Text _textBestTime`

- `Color _colorBestTimeNormal`

- `Color _colorBestTimeNew`

- `SimpleLayoutContent _rankItemList`

- `GameObject _winnerMedelGo`

- `Image _winnerMedalIcon`

- `SimpleLayoutContent _normalRewardList`

- `GameObject _rewardPartGo`

- `ScrollRect _racerScrollRect`

- `VerticalLayoutGroup _racerListGroup`

- `Single _itemHeight`

- `UILayoutDimensionListener _dimListener`

- `Tween m_enterTween`

- `RankListAdapter m_rankListAdapter`

- `RewardListAdapter m_rewardListAdapter`

- `SandboxV2RacingBattleFinishViewModel m_viewModel`


## Methods

- `Void _ScrollToMyPosIfNeed()`

- `Void _RenderView()`

- `Void EventOnViewClick()`

- `Void _RouteToHomeScene()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2.BattleFinish
public class SandboxV2RacingBattleFinishView : DynBattleFinishView
{
	private RectTransform _backRt; // 0x20
	private UIAnimationLocation _animEnter; // 0x28
	private Text _textStageName; // 0x38
	private Text _textMyPos; // 0x40
	private GameObject _unfinishedPosGo; // 0x48
	private Text _textCompleteTime; // 0x50
	private GameObject _newBestTimeGo; // 0x58
	private Text _textBestTime; // 0x60
	private Color _colorBestTimeNormal; // 0x68
	private Color _colorBestTimeNew; // 0x78
	private SandboxV2BattleFinishRacerItem[] _racerItemList; // 0x88
	private SimpleLayoutContent _rankItemList; // 0x90
	private GameObject _winnerMedelGo; // 0x98
	private Image _winnerMedalIcon; // 0xa0
	private SimpleLayoutContent _normalRewardList; // 0xa8
	private GameObject _rewardPartGo; // 0xb0
	private ScrollRect _racerScrollRect; // 0xb8
	private VerticalLayoutGroup _racerListGroup; // 0xc0
	private Single _itemHeight; // 0xc8
	private UILayoutDimensionListener _dimListener; // 0xd0
	private Tween m_enterTween; // 0xd8
	private RankListAdapter m_rankListAdapter; // 0xe0
	private RewardListAdapter m_rewardListAdapter; // 0xe8
	private SandboxV2RacingBattleFinishViewModel m_viewModel; // 0xf0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__ScrollToMyPosIfNeed; // 0x8
	private static DelegateBridge __Hotfix0__RenderView; // 0x10
	private static DelegateBridge __Hotfix0_EventOnViewClick; // 0x18
	private static DelegateBridge __Hotfix0__RouteToHomeScene; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x262a488 VA: 0x7594c42488
	protected override Void OnInit() { }
	// RVA: 0x262b0e4 VA: 0x7594c430e4
	private Void _ScrollToMyPosIfNeed() { }
	// RVA: 0x262abf0 VA: 0x7594c42bf0
	private Void _RenderView() { }
	// RVA: 0x262bb00 VA: 0x7594c43b00
	public Void EventOnViewClick() { }
	// RVA: 0x262ab68 VA: 0x7594c42b68
	private Void _RouteToHomeScene() { }
	// RVA: 0x262bb68 VA: 0x7594c43b68
	public Void .ctor() { }
}
```