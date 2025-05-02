# ActiveShowSwitchTween

**Namespace:** ` `


## Fields

- `RL01MenuCapsuleObject m_closure`

- `Tween m_loopTween`


## Methods

- `Void _PlayLoopTween()`

- `Void _ClearLoopTween()`

- `Void <>xLuaBaseProxy_BeforeHideEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class ActiveShowSwitchTween : UISwitchTween
{
	private const Single ANIM_DURATION; // 0x0
	private const Single LOOP_DURATION; // 0x0
	private const Single ALPHA_BREATH_UP; // 0x0
	private const Single ALPHA_BREATH_DOWN; // 0x0
	private RL01MenuCapsuleObject m_closure; // 0x38
	private Tween m_loopTween; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_BeforeHideEffect; // 0x18
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x28
	private static DelegateBridge __Hotfix0_AfterShowEffect; // 0x30
	private static DelegateBridge __Hotfix0_ResetToState; // 0x38
	private static DelegateBridge __Hotfix0__PlayLoopTween; // 0x40
	private static DelegateBridge __Hotfix0__ClearLoopTween; // 0x48


	// RVA: 0x2b78fa4 VA: 0x7595190fa4
	public Void .ctor(RL01MenuCapsuleObject closure) { }
	// RVA: 0x2b793a8 VA: 0x75951913a8
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2b7948c VA: 0x759519148c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2b79570 VA: 0x7595191570
	protected override Void BeforeHideEffect() { }
	// RVA: 0x2b79674 VA: 0x7595191674
	protected override Void AfterHideEffect() { }
	// RVA: 0x2b79708 VA: 0x7595191708
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2b7979c VA: 0x759519179c
	protected override Void AfterShowEffect() { }
	// RVA: 0x2b7998c VA: 0x759519198c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2b79810 VA: 0x7595191810
	private Void _PlayLoopTween() { }
	// RVA: 0x2b795e4 VA: 0x75951915e4
	private Void _ClearLoopTween() { }
	// RVA: 0x2b79a74 VA: 0x7595191a74
	private Void <>xLuaBaseProxy_BeforeHideEffect() { }
	// RVA: 0x2b79a7c VA: 0x7595191a7c
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x2b79a84 VA: 0x7595191a84
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x2b79a8c VA: 0x7595191a8c
	private Void <>xLuaBaseProxy_AfterShowEffect() { }
	// RVA: 0x2b79a94 VA: 0x7595191a94
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```