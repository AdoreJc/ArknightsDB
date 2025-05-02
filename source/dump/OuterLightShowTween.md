# OuterLightShowTween

**Namespace:** ` `


## Fields

- `RoguelikeMenuTaskObject m_closure`

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
private class OuterLightShowTween : UISwitchTween
{
	private RoguelikeMenuTaskObject m_closure; // 0x38
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


	// RVA: 0x2a6c0e0 VA: 0x75950840e0
	public Void .ctor(RoguelikeMenuTaskObject closure) { }
	// RVA: 0x2a6e410 VA: 0x7595086410
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2a6e514 VA: 0x7595086514
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2a6e618 VA: 0x7595086618
	protected override Void BeforeHideEffect() { }
	// RVA: 0x2a6e71c VA: 0x759508671c
	protected override Void AfterHideEffect() { }
	// RVA: 0x2a6e7b0 VA: 0x75950867b0
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2a6e844 VA: 0x7595086844
	protected override Void AfterShowEffect() { }
	// RVA: 0x2a6ea38 VA: 0x7595086a38
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2a6e8b8 VA: 0x75950868b8
	private Void _PlayLoopTween() { }
	// RVA: 0x2a6e68c VA: 0x759508668c
	private Void _ClearLoopTween() { }
	// RVA: 0x2a6eb20 VA: 0x7595086b20
	private Void <>xLuaBaseProxy_BeforeHideEffect() { }
	// RVA: 0x2a6eb28 VA: 0x7595086b28
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x2a6eb30 VA: 0x7595086b30
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x2a6eb38 VA: 0x7595086b38
	private Void <>xLuaBaseProxy_AfterShowEffect() { }
	// RVA: 0x2a6eb40 VA: 0x7595086b40
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```