# EyeSwitchTween

**Namespace:** ` `


## Fields

- `TuningProductEyeItemView m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_BeforeHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class EyeSwitchTween : UISwitchTween
{
	private TuningProductEyeItemView m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x23344a8 VA: 0x759494c4a8
	public Void .ctor(TuningProductEyeItemView closure) { }
	// RVA: 0x23345c0 VA: 0x759494c5c0
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x233467c VA: 0x759494c67c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2334784 VA: 0x759494c784
	protected override Void BeforeShowEffect() { }
	// RVA: 0x233482c VA: 0x759494c82c
	protected override Void BeforeHideEffect() { }
	// RVA: 0x23348b8 VA: 0x759494c8b8
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x233495c VA: 0x759494c95c
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x2334964 VA: 0x759494c964
	private Void <>xLuaBaseProxy_BeforeHideEffect() { }
	// RVA: 0x233496c VA: 0x759494c96c
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```