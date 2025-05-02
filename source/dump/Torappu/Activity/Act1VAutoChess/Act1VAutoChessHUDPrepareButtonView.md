# Act1VAutoChessHUDPrepareButtonView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `UIAnimationLocation _showSelfAnim`

- `UIAnimationLocation _showEnemyAnim`

- `UIAnimationLocation _switchEnemyInAnim`

- `UIAnimationLocation _switchEnemyOutAnim`

- `GameObject _panelActiveBattle`

- `GameObject _panelInactiveBattle`

- `CanvasGroup _battleCG`

- `CanvasGroup _exitCG`

- `Boolean m_isInited`

- `AnimationSwitchTween m_showSelf`

- `AnimationSwitchTween m_showEnemy`

- `UIBiAnimClipSwitchTween m_swicthEnemy`

- `HUDSeqNumChecker m_stateChecker`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act1VAutoChessHUDViewModel)`

- `Void OnSelfClick()`

- `Void OnEnemyClick()`

- `Void OnTipClick()`

- `Void OnStartBattleClick()`

- `Void OnExitGameClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDPrepareButtonView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _showSelfAnim; // 0x18
	private UIAnimationLocation _showEnemyAnim; // 0x28
	private UIAnimationLocation _switchEnemyInAnim; // 0x38
	private UIAnimationLocation _switchEnemyOutAnim; // 0x48
	private GameObject _panelActiveBattle; // 0x58
	private GameObject _panelInactiveBattle; // 0x60
	private CanvasGroup _battleCG; // 0x68
	private CanvasGroup _exitCG; // 0x70
	private Boolean m_isInited; // 0x78
	private AnimationSwitchTween m_showSelf; // 0x80
	private AnimationSwitchTween m_showEnemy; // 0x88
	private UIBiAnimClipSwitchTween m_swicthEnemy; // 0x90
	private HUDSeqNumChecker m_stateChecker; // 0x98
	private UIPageFinder m_pageFinder; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnSelfClick; // 0x10
	private static DelegateBridge __Hotfix0_OnEnemyClick; // 0x18
	private static DelegateBridge __Hotfix0_OnTipClick; // 0x20
	private static DelegateBridge __Hotfix0_OnStartBattleClick; // 0x28
	private static DelegateBridge __Hotfix0_OnExitGameClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x337cdc8 VA: 0x7595994dc8
	private Void _InitIfNot() { }
	// RVA: 0x337cfcc VA: 0x7595994fcc
	public Void Render(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x337d190 VA: 0x7595995190
	public Void OnSelfClick() { }
	// RVA: 0x337d244 VA: 0x7595995244
	public Void OnEnemyClick() { }
	// RVA: 0x337d2f8 VA: 0x75959952f8
	public Void OnTipClick() { }
	// RVA: 0x337d3ac VA: 0x75959953ac
	public Void OnStartBattleClick() { }
	// RVA: 0x337d460 VA: 0x7595995460
	public Void OnExitGameClick() { }
	// RVA: 0x337d514 VA: 0x7595995514
	public Void .ctor() { }
}
```