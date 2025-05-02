# PrivateBetShowTween

**Namespace:** ` `


## Fields

- `EnemyDuelBetView m_closure`

- `UIAnimationTween m_countdownLoopTween`

- `UIAnimationTween m_clockLoopTween`

- `Tween m_tickLoopTween`


## Methods

- `Void _PlayLoopTween()`

- `Void _ClearLoopTween()`

- `Void StopTickLoopTween()`

- `Void <GenerateTweenOfShow>b__5_0()`

- `Void <GenerateTweenOfHide>b__6_0()`

- `Void <_PlayLoopTween>b__10_0()`

- `Void <>xLuaBaseProxy_AfterShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PrivateBetShowTween : UISwitchTween
{
	private EnemyDuelBetView m_closure; // 0x38
	private UIAnimationTween m_countdownLoopTween; // 0x40
	private UIAnimationTween m_clockLoopTween; // 0x48
	private Tween m_tickLoopTween; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10
	private static DelegateBridge __Hotfix0_AfterShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28
	private static DelegateBridge __Hotfix0__PlayLoopTween; // 0x30
	private static DelegateBridge __Hotfix0__ClearLoopTween; // 0x38
	private static DelegateBridge __Hotfix0_StopTickLoopTween; // 0x40


	// RVA: 0x297fea4 VA: 0x7594f97ea4
	public Void .ctor(EnemyDuelBetView closure) { }
	// RVA: 0x29812c4 VA: 0x7594f992c4
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2981524 VA: 0x7594f99524
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x298178c VA: 0x7594f9978c
	protected override Void AfterShowEffect() { }
	// RVA: 0x2981b48 VA: 0x7594f99b48
	protected override Void AfterHideEffect() { }
	// RVA: 0x2981d10 VA: 0x7594f99d10
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2981800 VA: 0x7594f99800
	private Void _PlayLoopTween() { }
	// RVA: 0x2981bbc VA: 0x7594f99bbc
	private Void _ClearLoopTween() { }
	// RVA: 0x2980030 VA: 0x7594f98030
	public Void StopTickLoopTween() { }
	// RVA: 0x2981e64 VA: 0x7594f99e64
	private Void <GenerateTweenOfShow>b__5_0() { }
	// RVA: 0x2981ebc VA: 0x7594f99ebc
	private Void <GenerateTweenOfHide>b__6_0() { }
	// RVA: 0x2981f14 VA: 0x7594f99f14
	private Void <_PlayLoopTween>b__10_0() { }
	// RVA: 0x2981fac VA: 0x7594f99fac
	private Void <>xLuaBaseProxy_AfterShowEffect() { }
	// RVA: 0x2981fb4 VA: 0x7594f99fb4
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x2981fbc VA: 0x7594f99fbc
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```