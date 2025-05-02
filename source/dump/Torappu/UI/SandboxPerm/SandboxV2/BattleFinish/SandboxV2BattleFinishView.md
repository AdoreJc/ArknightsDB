# SandboxV2BattleFinishView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2.BattleFinish`


## Fields

- `RectTransform _backRt`

- `UIFullScreenImage _fullScreenImage`

- `RectTransform _illustContainer`

- `Text _textNodeType`

- `Text _textStageName`

- `GameObject _targetPartGo`

- `Text _textTargetName`

- `Text _textTargetHealthRatio`

- `Slider _sliderTargetHealth`

- `UIAtlasImage _iconTargetNestGo`

- `UIAtlasImage _iconTargetMineGo`

- `UIAtlasImage _iconTargetGateGo`

- `UIAtlasImage _iconTargetCaveGo`

- `GameObject _targetAllDefeatedGo`

- `Color _colorIconTargetAllDefeated`

- `Color _colorIconTargetNormal`

- `UIAtlasImage _imgTargetHpSlider`

- `Color _colorSliderTargetNormal`

- `Color _colorSliderTargetCave`

- `GameObject _basementHpPartGo`

- `Text _textBasementName`

- `Text _textBasementHpRatio`

- `Slider _sliderBasementHp`

- `UIAtlasImage _imgBasementHpGlow`

- `UIAtlasImage _imgBasementHpSlider`

- `UIAtlasImage _imgBasementHpRatio`

- `Color _colorBasementHpNormal`

- `Color _colorBasementHpEmpty`

- `GameObject _enemyRushPartGo`

- `GameObject _enemyRushAllDefeatedGo`

- `Text _textEnemeyCnt`

- `UIAtlasImage _imgEnemyRushIcon`

- `Color _colorEnemyRushNormal`

- `Color _colorEnemyRushAllDefeat`

- `CanvasGroup _illustCanvasGroup`

- `CanvasGroup _infoListCanvasGroup`

- `CanvasGroup _basementHpCanvasGroup`

- `CanvasGroup _targetHpCanvasGroup`

- `CanvasGroup _enemyRushCanvasGroup`

- `CanvasGroup _rewardCanvasGroup`

- `SimpleLayoutContent _normalRewardList`

- `SimpleLayoutContent _randomRewardList`

- `GameObject _rewardPartGo`

- `SandboxV2BattleFinishViewModel m_viewModel`

- `Sequence m_sequence`

- `RewardListAdapter m_normalRewardListAdapter`

- `RewardListAdapter m_randomRewardListAdapter`


## Methods

- `Void _RenderView()`

- `Void _PlayAnimEnter()`

- `Void _RenderRewardPart()`

- `Void _RenderEnemeyRushPart()`

- `Void _RenderBasementHealthPart()`

- `Void _RenderTargetPart()`

- `Void _UpdateIconTarget(UIAtlasImage, SandboxV2NodeType)`

- `String _GetPercentRatio(Single)`

- `Void _RouteToHomeScene()`

- `Void EventOnViewClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2.BattleFinish
public class SandboxV2BattleFinishView : DynBattleFinishView
{
	private RectTransform _backRt; // 0x20
	private UIFullScreenImage _fullScreenImage; // 0x28
	private RectTransform _illustContainer; // 0x30
	private Text _textNodeType; // 0x38
	private Text _textStageName; // 0x40
	private GameObject _targetPartGo; // 0x48
	private Text _textTargetName; // 0x50
	private Text _textTargetHealthRatio; // 0x58
	private Slider _sliderTargetHealth; // 0x60
	private UIAtlasImage _iconTargetNestGo; // 0x68
	private UIAtlasImage _iconTargetMineGo; // 0x70
	private UIAtlasImage _iconTargetGateGo; // 0x78
	private UIAtlasImage _iconTargetCaveGo; // 0x80
	private GameObject _targetAllDefeatedGo; // 0x88
	private Color _colorIconTargetAllDefeated; // 0x90
	private Color _colorIconTargetNormal; // 0xa0
	private UIAtlasImage _imgTargetHpSlider; // 0xb0
	private Color _colorSliderTargetNormal; // 0xb8
	private Color _colorSliderTargetCave; // 0xc8
	private GameObject _basementHpPartGo; // 0xd8
	private Text _textBasementName; // 0xe0
	private Text _textBasementHpRatio; // 0xe8
	private Slider _sliderBasementHp; // 0xf0
	private UIAtlasImage _imgBasementHpGlow; // 0xf8
	private UIAtlasImage _imgBasementHpSlider; // 0x100
	private UIAtlasImage _imgBasementHpRatio; // 0x108
	private Color _colorBasementHpNormal; // 0x110
	private Color _colorBasementHpEmpty; // 0x120
	private GameObject _enemyRushPartGo; // 0x130
	private GameObject _enemyRushAllDefeatedGo; // 0x138
	private Text _textEnemeyCnt; // 0x140
	private UIAtlasImage _imgEnemyRushIcon; // 0x148
	private Color _colorEnemyRushNormal; // 0x150
	private Color _colorEnemyRushAllDefeat; // 0x160
	private CanvasGroup _illustCanvasGroup; // 0x170
	private CanvasGroup _infoListCanvasGroup; // 0x178
	private CanvasGroup _basementHpCanvasGroup; // 0x180
	private CanvasGroup _targetHpCanvasGroup; // 0x188
	private CanvasGroup _enemyRushCanvasGroup; // 0x190
	private CanvasGroup _rewardCanvasGroup; // 0x198
	private SimpleLayoutContent _normalRewardList; // 0x1a0
	private SimpleLayoutContent _randomRewardList; // 0x1a8
	private GameObject _rewardPartGo; // 0x1b0
	private const Single TWEEN_MOVE_DURATION; // 0x0
	private const String PERCENTAGE_STR; // 0x0
	private SandboxV2BattleFinishViewModel m_viewModel; // 0x1b8
	private Sequence m_sequence; // 0x1c0
	private RewardListAdapter m_normalRewardListAdapter; // 0x1c8
	private RewardListAdapter m_randomRewardListAdapter; // 0x1d0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__RenderView; // 0x8
	private static DelegateBridge __Hotfix0__PlayAnimEnter; // 0x10
	private static DelegateBridge __Hotfix0__RenderRewardPart; // 0x18
	private static DelegateBridge __Hotfix0__RenderEnemeyRushPart; // 0x20
	private static DelegateBridge __Hotfix0__RenderBasementHealthPart; // 0x28
	private static DelegateBridge __Hotfix0__RenderTargetPart; // 0x30
	private static DelegateBridge __Hotfix0__UpdateIconTarget; // 0x38
	private static DelegateBridge __Hotfix0__GetPercentRatio; // 0x40
	private static DelegateBridge __Hotfix0__RouteToHomeScene; // 0x48
	private static DelegateBridge __Hotfix0_EventOnViewClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2626718 VA: 0x7594c3e718
	protected override Void OnInit() { }
	// RVA: 0x26271a8 VA: 0x7594c3f1a8
	private Void _RenderView() { }
	// RVA: 0x2627d0c VA: 0x7594c3fd0c
	private Void _PlayAnimEnter() { }
	// RVA: 0x2627b60 VA: 0x7594c3fb60
	private Void _RenderRewardPart() { }
	// RVA: 0x2627978 VA: 0x7594c3f978
	private Void _RenderEnemeyRushPart() { }
	// RVA: 0x2627754 VA: 0x7594c3f754
	private Void _RenderBasementHealthPart() { }
	// RVA: 0x2627580 VA: 0x7594c3f580
	private Void _RenderTargetPart() { }
	// RVA: 0x2628828 VA: 0x7594c40828
	private Void _UpdateIconTarget(UIAtlasImage imgIcon, SandboxV2NodeType imgNodeType) { }
	// RVA: 0x2628690 VA: 0x7594c40690
	private String _GetPercentRatio(Single ratio) { }
	// RVA: 0x2627050 VA: 0x7594c3f050
	private Void _RouteToHomeScene() { }
	// RVA: 0x262894c VA: 0x7594c4094c
	public Void EventOnViewClick() { }
	// RVA: 0x26289b4 VA: 0x7594c409b4
	public Void .ctor() { }
}
```