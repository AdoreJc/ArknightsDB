# Act1VAutoChessHUDMidView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _playerHp`

- `Text _enemyHp`

- `Text _curRoundNum`

- `Text _prevRoundNum`

- `Text _goldGainNum`

- `GameObject _goldGainNumPanel`

- `Text _specialEnemyNotice`

- `Text _nextEnemyName`

- `Text _roundEndEnemyName`

- `Text _roundEndKilledEnemyName`

- `Act1VAutoChessHUDHpView _playerHpView`

- `Act1VAutoChessHUDHpView _enemyHpView`

- `GameObject _panelWaveMessage`

- `GameObject _panelSpecialEndNotice`

- `GameObject _panelDiffEnemyHighlight`

- `UIAnimationLocation _roundEndAnimWin`

- `UIAnimationLocation _roundEndAnimLose`

- `UIAnimationLocation _roundEndAnimDraw`

- `UIAnimationLocation _roundEndAnimKill`

- `UIAnimationLocation _roundStartShowEnemyFromWin`

- `UIAnimationLocation _roundStartShowEnemyFromLose`

- `UIAnimationLocation _roundStartShowEnemyFromEntry`

- `UIAnimationLocation _roundStartShowEnemyFromDraw`

- `UIAnimationLocation _roundStartShowEnemyFromKill`

- `UIAnimationLocation _showSwitchAnim`

- `Single _hpTweenDelay`

- `Single _hpTweenDuration`

- `Image _selfIcon`

- `Image _enemyIcon`

- `Boolean m_isInited`

- `String m_selfIconId`

- `String m_enemyIconId`

- `HUDSeqNumChecker m_stateSeqChecker`

- `UIPageFinder m_pageFinder`

- `Tween m_playerHpTween`

- `Tween m_playerHpViewTween`

- `Tween m_enemyHpTween`

- `Tween m_enemyHpViewTween`

- `Tween m_roundStartAnimSequence`

- `Tween m_roundEndAnimSequence`

- `ShowSwitchTween m_showAnimTween`

- `Coroutine m_animCoroutine`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act1VAutoChessHUDViewModel)`

- `Void _RenderSelfIcon(Act1VAutoChessHUDViewModel, ILoadAsset)`

- `Void _RenderResultEnemyIcon(Act1VAutoChessHUDViewModel, ILoadAsset)`

- `Void _RenderEnemyIcon(Act1VAutoChessHUDViewModel, ILoadAsset)`

- `Void _RenderStart(Act1VAutoChessHUDViewModel, Boolean)`

- `Void _RenderEndRound(Act1VAutoChessHUDViewModel, Boolean)`

- `UIAnimationTween _GetShowEnemyTween(Boolean, Act1VAutoChessHUDRoundResultViewModel)`

- `UIAnimationTween _GetRoundEndTween(AutoChessRoundBattleFinishState)`

- `UIAnimationTween _GetKillEnemyTween()`

- `UIAnimationLocation _GetShowEnemyAnimLocation(Boolean, Act1VAutoChessHUDRoundResultViewModel)`

- `UIAnimationLocation _GetRoundEndAnimLocation(AutoChessRoundBattleFinishState)`

- `Void _SendMsg(Int32, ValueBundle)`

- `IEnumerator _PlayStartRoundCoroutine(Act1VAutoChessHUDViewModel)`

- `IEnumerator _PlayEndRoundCoroutine(Act1VAutoChessHUDViewModel)`

- `Void _PlayPlayerHpTween(Int32, Int32, Int32)`

- `Void _PlayEnemyHpTween(Int32, Int32, Int32)`

- `Void _PlayHpTween(HpTweenParam, out, out)`

- `Tween _PlayRoundStartSequence(Boolean, Act1VAutoChessHUDRoundResultViewModel)`

- `Tween _PlayRoundEndSequence(AutoChessRoundBattleFinishState, Boolean)`

- `Void _ClearAllAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDMidView : MonoBehaviour, IHotfixable
{
	private Text _playerHp; // 0x18
	private Text _enemyHp; // 0x20
	private Text _curRoundNum; // 0x28
	private Text _prevRoundNum; // 0x30
	private Text _goldGainNum; // 0x38
	private GameObject _goldGainNumPanel; // 0x40
	private Text _specialEnemyNotice; // 0x48
	private Text _nextEnemyName; // 0x50
	private Text _roundEndEnemyName; // 0x58
	private Text _roundEndKilledEnemyName; // 0x60
	private Act1VAutoChessHUDHpView _playerHpView; // 0x68
	private Act1VAutoChessHUDHpView _enemyHpView; // 0x70
	private GameObject _panelWaveMessage; // 0x78
	private GameObject _panelSpecialEndNotice; // 0x80
	private GameObject _panelDiffEnemyHighlight; // 0x88
	private UIAnimationLocation _roundEndAnimWin; // 0x90
	private UIAnimationLocation _roundEndAnimLose; // 0xa0
	private UIAnimationLocation _roundEndAnimDraw; // 0xb0
	private UIAnimationLocation _roundEndAnimKill; // 0xc0
	private UIAnimationLocation _roundStartShowEnemyFromWin; // 0xd0
	private UIAnimationLocation _roundStartShowEnemyFromLose; // 0xe0
	private UIAnimationLocation _roundStartShowEnemyFromEntry; // 0xf0
	private UIAnimationLocation _roundStartShowEnemyFromDraw; // 0x100
	private UIAnimationLocation _roundStartShowEnemyFromKill; // 0x110
	private UIAnimationLocation _showSwitchAnim; // 0x120
	private Single _hpTweenDelay; // 0x130
	private Single _hpTweenDuration; // 0x134
	private Image _selfIcon; // 0x138
	private Image _enemyIcon; // 0x140
	private Boolean m_isInited; // 0x148
	private String m_selfIconId; // 0x150
	private String m_enemyIconId; // 0x158
	private HUDSeqNumChecker m_stateSeqChecker; // 0x160
	private UIPageFinder m_pageFinder; // 0x168
	private Tween m_playerHpTween; // 0x178
	private Tween m_playerHpViewTween; // 0x180
	private Tween m_enemyHpTween; // 0x188
	private Tween m_enemyHpViewTween; // 0x190
	private Tween m_roundStartAnimSequence; // 0x198
	private Tween m_roundEndAnimSequence; // 0x1a0
	private ShowSwitchTween m_showAnimTween; // 0x1a8
	private Coroutine m_animCoroutine; // 0x1b0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderSelfIcon; // 0x10
	private static DelegateBridge __Hotfix0__RenderResultEnemyIcon; // 0x18
	private static DelegateBridge __Hotfix0__RenderEnemyIcon; // 0x20
	private static DelegateBridge __Hotfix0__RenderStart; // 0x28
	private static DelegateBridge __Hotfix0__RenderEndRound; // 0x30
	private static DelegateBridge __Hotfix0__GetShowEnemyTween; // 0x38
	private static DelegateBridge __Hotfix0__GetRoundEndTween; // 0x40
	private static DelegateBridge __Hotfix0__GetKillEnemyTween; // 0x48
	private static DelegateBridge __Hotfix0__GetShowEnemyAnimLocation; // 0x50
	private static DelegateBridge __Hotfix0__GetRoundEndAnimLocation; // 0x58
	private static DelegateBridge __Hotfix0__SendMsg; // 0x60
	private static DelegateBridge __Hotfix0__PlayStartRoundCoroutine; // 0x68
	private static DelegateBridge __Hotfix0__PlayEndRoundCoroutine; // 0x70
	private static DelegateBridge __Hotfix0__PlayPlayerHpTween; // 0x78
	private static DelegateBridge __Hotfix0__PlayEnemyHpTween; // 0x80
	private static DelegateBridge __Hotfix0__PlayHpTween; // 0x88
	private static DelegateBridge __Hotfix0__PlayRoundStartSequence; // 0x90
	private static DelegateBridge __Hotfix0__PlayRoundEndSequence; // 0x98
	private static DelegateBridge __Hotfix0__ClearAllAnim; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x3379a74 VA: 0x7595991a74
	private Void _InitIfNot() { }
	// RVA: 0x3379bd8 VA: 0x7595991bd8
	public Void Render(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x3379e7c VA: 0x7595991e7c
	private Void _RenderSelfIcon(Act1VAutoChessHUDViewModel viewModel, ILoadAsset assetLoader) { }
	// RVA: 0x3379fd0 VA: 0x7595991fd0
	private Void _RenderResultEnemyIcon(Act1VAutoChessHUDViewModel viewModel, ILoadAsset assetLoader) { }
	// RVA: 0x337a3f0 VA: 0x75959923f0
	protected Void _RenderEnemyIcon(Act1VAutoChessHUDViewModel viewModel, ILoadAsset assetLoader) { }
	// RVA: 0x337a550 VA: 0x7595992550
	private Void _RenderStart(Act1VAutoChessHUDViewModel viewModel, Boolean shouldPlayTween) { }
	// RVA: 0x337a118 VA: 0x7595992118
	private Void _RenderEndRound(Act1VAutoChessHUDViewModel viewModel, Boolean shouldPlayTween) { }
	// RVA: 0x337aeb8 VA: 0x7595992eb8
	private UIAnimationTween _GetShowEnemyTween(Boolean isFromEntry, Act1VAutoChessHUDRoundResultViewModel roundResult) { }
	// RVA: 0x337afb0 VA: 0x7595992fb0
	private UIAnimationTween _GetRoundEndTween(AutoChessRoundBattleFinishState finishState) { }
	// RVA: 0x337b09c VA: 0x759599309c
	private UIAnimationTween _GetKillEnemyTween() { }
	// RVA: 0x337ab04 VA: 0x7595992b04
	private UIAnimationLocation _GetShowEnemyAnimLocation(Boolean isFromEntry, Act1VAutoChessHUDRoundResultViewModel roundResult) { }
	// RVA: 0x337aca8 VA: 0x7595992ca8
	private UIAnimationLocation _GetRoundEndAnimLocation(AutoChessRoundBattleFinishState finishState) { }
	// RVA: 0x337b174 VA: 0x7595993174
	private Void _SendMsg(Int32 msgType, ValueBundle value) { }
	// RVA: 0x337abd8 VA: 0x7595992bd8
	private IEnumerator _PlayStartRoundCoroutine(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x337ade8 VA: 0x7595992de8
	private IEnumerator _PlayEndRoundCoroutine(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x337b29c VA: 0x759599329c
	private Void _PlayPlayerHpTween(Int32 from, Int32 to, Int32 maxHp) { }
	// RVA: 0x337b8cc VA: 0x75959938cc
	private Void _PlayEnemyHpTween(Int32 from, Int32 to, Int32 maxHp) { }
	// RVA: 0x337b384 VA: 0x7595993384
	private Void _PlayHpTween(HpTweenParam tweenParam, out Tween hpTextTween, out Tween hpViewTween) { }
	// RVA: 0x337b9bc VA: 0x75959939bc
	private Tween _PlayRoundStartSequence(Boolean isFromEntry, Act1VAutoChessHUDRoundResultViewModel roundResult) { }
	// RVA: 0x337bb10 VA: 0x7595993b10
	private Tween _PlayRoundEndSequence(AutoChessRoundBattleFinishState finishState, Boolean isEnemyKilled) { }
	// RVA: 0x337a9a8 VA: 0x75959929a8
	private Void _ClearAllAnim() { }
	// RVA: 0x337bca0 VA: 0x7595993ca0
	public Void .ctor() { }
}
```