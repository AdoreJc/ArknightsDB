# EnemyDuelBattleIndexState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Coroutine m_coroutine`

- `UIPageFinder m_pageFinder`

- `Int32 m_finishWaitDlg`


## Methods

- `Void _ClearCoroutine()`

- `Void _RouteToProperState()`

- `IEnumerator _CoroutineRouteToProperState()`

- `Type _GetTargetState()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattleIndexState : State
{
	private Coroutine m_coroutine; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private Int32 m_finishWaitDlg; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_NeedRouteToFinish; // 0x18
	private static DelegateBridge __Hotfix0__ClearCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__RouteToProperState; // 0x28
	private static DelegateBridge __Hotfix0__CoroutineRouteToProperState; // 0x30
	private static DelegateBridge __Hotfix0__GetTargetState; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x298771c VA: 0x7594f9f71c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2987780 VA: 0x7594f9f780
	protected override Void OnResume() { }
	// RVA: 0x29879a4 VA: 0x7594f9f9a4
	protected override Void OnExit() { }
	// RVA: 0x2987ad4 VA: 0x7594f9fad4
	public static Boolean NeedRouteToFinish() { }
	// RVA: 0x2987a18 VA: 0x7594f9fa18
	private Void _ClearCoroutine() { }
	// RVA: 0x29877f4 VA: 0x7594f9f7f4
	private Void _RouteToProperState() { }
	// RVA: 0x2987bcc VA: 0x7594f9fbcc
	private IEnumerator _CoroutineRouteToProperState() { }
	// RVA: 0x2987ca0 VA: 0x7594f9fca0
	private Type _GetTargetState() { }
	// RVA: 0x2987e18 VA: 0x7594f9fe18
	public Void .ctor() { }
	// RVA: 0x2987e88 VA: 0x7594f9fe88
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2987e90 VA: 0x7594f9fe90
	private Void <>xLuaBaseProxy_OnExit() { }
}
```