# Act1VAutoChessHUDTopView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessHUDBasementView _basementView`

- `Act1VAutoChessHUDPrepareView _prepareView`

- `Act1VAutoChessHUDBattleView _battleView`

- `Act1VAutoChessHUDTopSelfHpView _selfHpView`

- `Act1VAutoChessHUDTopEnemyHpView _enemyHpView`

- `Act1VAutoChessHUDPrepareHintView _prepareHintView`

- `Act1VAutoChessHUDBattleHintView _battleHintView`

- `Act1VAutoChessHUDCampView _campView`

- `Act1VAutoChessHUDPrepareButtonView _prepareBtnView`

- `Act1VAutoChessHUDBattleButtonView _battleBtnView`

- `CanvasGroup _prepareBtnCG`

- `CanvasGroup _prepareBtnCGDown`

- `CanvasGroup _battleBtnCG`

- `GameObject _panelCampRaycast`

- `UIAnimationLocation _topSwitchAnim`

- `CanvasGroup _rootCg`

- `UIAnimationLocation _startToPrepare`

- `UIAnimationLocation _battleToEnd`

- `Boolean m_isInited`

- `FadeSwitchTween m_prepareBtnFade`

- `FadeSwitchTween m_prepareDownBtnFade`

- `FadeSwitchTween m_battleBtnFade`

- `FadeSwitchTween m_rootFade`

- `AnimationSwitchTween m_topSwitchTween`

- `UIBiAnimClipSwitchTween m_topShowTween`

- `UIPageFinder m_pageFinder`

- `HUDSeqNumChecker m_gameStartSeqChecker`

- `HUDSeqNumChecker m_stateSeqChecker`

- `HUDSeqNumChecker m_selfHpSeqChecker`

- `HUDSeqNumChecker m_enemyHpSeqChecker`

- `HUDSeqNumChecker m_prepareBtnSeqChecker`

- `HUDSeqNumChecker m_battleBtnSeqChecker`

- `HUDSeqNumChecker m_campSwitchSeqChecker`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act1VAutoChessHUDViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDTopView : MonoBehaviour, IHotfixable
{
	private Act1VAutoChessHUDBasementView _basementView; // 0x18
	private Act1VAutoChessHUDPrepareView _prepareView; // 0x20
	private Act1VAutoChessHUDBattleView _battleView; // 0x28
	private Act1VAutoChessHUDTopSelfHpView _selfHpView; // 0x30
	private Act1VAutoChessHUDTopEnemyHpView _enemyHpView; // 0x38
	private Act1VAutoChessHUDPrepareHintView _prepareHintView; // 0x40
	private Act1VAutoChessHUDBattleHintView _battleHintView; // 0x48
	private Act1VAutoChessHUDCampView _campView; // 0x50
	private Act1VAutoChessHUDPrepareButtonView _prepareBtnView; // 0x58
	private Act1VAutoChessHUDBattleButtonView _battleBtnView; // 0x60
	private CanvasGroup _prepareBtnCG; // 0x68
	private CanvasGroup _prepareBtnCGDown; // 0x70
	private CanvasGroup _battleBtnCG; // 0x78
	private GameObject _panelCampRaycast; // 0x80
	private UIAnimationLocation _topSwitchAnim; // 0x88
	private CanvasGroup _rootCg; // 0x98
	private UIAnimationLocation _startToPrepare; // 0xa0
	private UIAnimationLocation _battleToEnd; // 0xb0
	private Boolean m_isInited; // 0xc0
	private FadeSwitchTween m_prepareBtnFade; // 0xc8
	private FadeSwitchTween m_prepareDownBtnFade; // 0xd0
	private FadeSwitchTween m_battleBtnFade; // 0xd8
	private FadeSwitchTween m_rootFade; // 0xe0
	private AnimationSwitchTween m_topSwitchTween; // 0xe8
	private UIBiAnimClipSwitchTween m_topShowTween; // 0xf0
	private UIPageFinder m_pageFinder; // 0xf8
	private HUDSeqNumChecker m_gameStartSeqChecker; // 0x108
	private HUDSeqNumChecker m_stateSeqChecker; // 0x110
	private HUDSeqNumChecker m_selfHpSeqChecker; // 0x118
	private HUDSeqNumChecker m_enemyHpSeqChecker; // 0x120
	private HUDSeqNumChecker m_prepareBtnSeqChecker; // 0x128
	private HUDSeqNumChecker m_battleBtnSeqChecker; // 0x130
	private HUDSeqNumChecker m_campSwitchSeqChecker; // 0x138
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x337eb00 VA: 0x7595996b00
	private Void _InitIfNot() { }
	// RVA: 0x337ee00 VA: 0x7595996e00
	public Void Render(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x337f220 VA: 0x7595997220
	public Void OnClick() { }
	// RVA: 0x337f324 VA: 0x7595997324
	public Void .ctor() { }
}
```