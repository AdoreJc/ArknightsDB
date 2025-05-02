# FormEffectSwitchTween

**Namespace:** ` `


## Fields

- `TuningProductSlotFormEffectView m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_BeforeHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FormEffectSwitchTween : UISwitchTween
{
	private TuningProductSlotFormEffectView m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x23371d4 VA: 0x759494f1d4
	public Void .ctor(TuningProductSlotFormEffectView closure) { }
	// RVA: 0x23372ec VA: 0x759494f2ec
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x23373a8 VA: 0x759494f3a8
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2337468 VA: 0x759494f468
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2337594 VA: 0x759494f594
	protected override Void BeforeHideEffect() { }
	// RVA: 0x2337620 VA: 0x759494f620
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x23376c4 VA: 0x759494f6c4
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x23376cc VA: 0x759494f6cc
	private Void <>xLuaBaseProxy_BeforeHideEffect() { }
	// RVA: 0x23376d4 VA: 0x759494f6d4
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```