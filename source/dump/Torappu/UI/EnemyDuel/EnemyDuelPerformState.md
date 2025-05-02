# EnemyDuelPerformState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelPerformView _performView`

- `UIAnimationLocation _enterAnim`

- `EnemyDuelRoundStartView _startView`

- `UIAnimationLocation _startAnim`

- `CanvasGroup _performCanvasGroup`

- `Boolean m_isInited`

- `EnemyDuelBattleStateBean m_stateBean`

- `Tween m_enterTween`

- `UIPageFinder m_pageFinder`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void _PlayEnterAnim()`

- `Void _UpdateData()`

- `Void _OnBattleFinishWait(Object)`

- `Void _OnDisableEmoticonClicked()`

- `Void _SetPerformCanvasRaycast(Boolean)`

- `Void <_PlayEnterAnim>b__15_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPerformState : EnemyDuelBattleState, IValueMsgReceiver
{
	public const Int32 MSG_ON_DISABLE_EMOTICON_CLICKED; // 0x0
	private EnemyDuelPerformView _performView; // 0x80
	private UIAnimationLocation _enterAnim; // 0x88
	private EnemyDuelRoundStartView _startView; // 0x98
	private UIAnimationLocation _startAnim; // 0xa0
	private CanvasGroup _performCanvasGroup; // 0xb0
	private Boolean m_isInited; // 0xb8
	private EnemyDuelBattleStateBean m_stateBean; // 0xc0
	private Tween m_enterTween; // 0xc8
	private UIPageFinder m_pageFinder; // 0xd0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnPause; // 0x20
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x28
	private static DelegateBridge __Hotfix0__UpdateData; // 0x30
	private static DelegateBridge __Hotfix0__OnBattleFinishWait; // 0x38
	private static DelegateBridge __Hotfix0__OnDisableEmoticonClicked; // 0x40
	private static DelegateBridge __Hotfix0__SetPerformCanvasRaycast; // 0x48
	private static DelegateBridge __Hotfix0_GetSupportedGameState; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x298a074 VA: 0x7594fa2074
	public override IStateBean GetCacheBean() { }
	// RVA: 0x298a0dc VA: 0x7594fa20dc
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x298a37c VA: 0x7594fa237c
	private Void _InitIfNot() { }
	// RVA: 0x298a4b4 VA: 0x7594fa24b4
	protected override Void OnEnter() { }
	// RVA: 0x298aa14 VA: 0x7594fa2a14
	protected override Void OnPause() { }
	// RVA: 0x298a71c VA: 0x7594fa271c
	private Void _PlayEnterAnim() { }
	// RVA: 0x298a534 VA: 0x7594fa2534
	private Void _UpdateData() { }
	// RVA: 0x298ab60 VA: 0x7594fa2b60
	private Void _OnBattleFinishWait(Object obj) { }
	// RVA: 0x298a180 VA: 0x7594fa2180
	private Void _OnDisableEmoticonClicked() { }
	// RVA: 0x298aad4 VA: 0x7594fa2ad4
	private Void _SetPerformCanvasRaycast(Boolean isOn) { }
	// RVA: 0x298ac3c VA: 0x7594fa2c3c
	protected override EnemyDuelServiceGameState GetSupportedGameState() { }
	// RVA: 0x298aca4 VA: 0x7594fa2ca4
	public Void .ctor() { }
	// RVA: 0x298ae38 VA: 0x7594fa2e38
	private Void <_PlayEnterAnim>b__15_0() { }
	// RVA: 0x298ae40 VA: 0x7594fa2e40
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x298ae44 VA: 0x7594fa2e44
	private Void <>xLuaBaseProxy_OnPause() { }
}
```