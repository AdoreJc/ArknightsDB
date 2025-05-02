# EnemyDuelBetState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelBetView _view`

- `UIAnimationLocation _animShow`

- `EnemyDuelBetProperty m_property`

- `Boolean m_inited`

- `UIAnimationTween m_showTween`

- `EnemyDuelBattleCoolDownController m_coolDownController`

- `UIPageFinder m_pageFinder`

- `Single m_minBetCd`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnStatusChanged(Object)`

- `Void _OnBetBtnClicked(EnemyDuelBetSelectStatus)`

- `Void _OnEnemyDetailBtnClicked()`

- `Void _OnHideDetailPnlClicked()`

- `Void _OnDisableEmoticonClicked()`

- `Boolean _IsUIStable()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetState : EnemyDuelBattleState, IValueMsgReceiver
{
	public const Int32 MSG_ON_BET_BTN_CLICKED; // 0x0
	public const Int32 MSG_ON_ENEMY_DETAIL_BTN_CLICKED; // 0x0
	public const Int32 MSG_ON_HIDE_ENEMY_DETAIL_PNL; // 0x0
	public const Int32 MSG_ON_DISABLE_EMOTICON_CLICKED; // 0x0
	private EnemyDuelBetView _view; // 0x80
	private UIAnimationLocation _animShow; // 0x88
	private EnemyDuelBetProperty m_property; // 0x98
	private Boolean m_inited; // 0xa0
	private UIAnimationTween m_showTween; // 0xa8
	private EnemyDuelBattleCoolDownController m_coolDownController; // 0xb0
	private UIPageFinder m_pageFinder; // 0xb8
	private Single m_minBetCd; // 0xc8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPause; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__OnStatusChanged; // 0x28
	private static DelegateBridge __Hotfix0__OnBetBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnEnemyDetailBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnHideDetailPnlClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnDisableEmoticonClicked; // 0x48
	private static DelegateBridge __Hotfix0__IsUIStable; // 0x50
	private static DelegateBridge __Hotfix0_GetSupportedGameState; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x297ca70 VA: 0x7594f94a70
	private Void _InitIfNot() { }
	// RVA: 0x297cbf8 VA: 0x7594f94bf8
	protected override Void OnEnter() { }
	// RVA: 0x297d5f8 VA: 0x7594f955f8
	protected override Void OnPause() { }
	// RVA: 0x297d740 VA: 0x7594f95740
	public override IStateBean GetCacheBean() { }
	// RVA: 0x297d7a4 VA: 0x7594f957a4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x297dd18 VA: 0x7594f95d18
	private Void _OnStatusChanged(Object arg) { }
	// RVA: 0x297d8b0 VA: 0x7594f958b0
	private Void _OnBetBtnClicked(EnemyDuelBetSelectStatus selectStatus) { }
	// RVA: 0x297da04 VA: 0x7594f95a04
	private Void _OnEnemyDetailBtnClicked() { }
	// RVA: 0x297dad0 VA: 0x7594f95ad0
	private Void _OnHideDetailPnlClicked() { }
	// RVA: 0x297db98 VA: 0x7594f95b98
	private Void _OnDisableEmoticonClicked() { }
	// RVA: 0x297e248 VA: 0x7594f96248
	private Boolean _IsUIStable() { }
	// RVA: 0x297e914 VA: 0x7594f96914
	protected override EnemyDuelServiceGameState GetSupportedGameState() { }
	// RVA: 0x297e97c VA: 0x7594f9697c
	public Void .ctor() { }
	// RVA: 0x297eb00 VA: 0x7594f96b00
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x297eb04 VA: 0x7594f96b04
	private Void <>xLuaBaseProxy_OnPause() { }
}
```