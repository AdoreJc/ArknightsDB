# ShowHideSwitchTween

**Namespace:** ` `


## Fields

- `Act42D0EffectView m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_BeforeHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ShowHideSwitchTween : UISwitchTween
{
	private Act42D0EffectView m_closure; // 0x38
	private const Single ANIM_DURATION; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x32108f4 VA: 0x75958288f4
	public Void .ctor(Act42D0EffectView closure) { }
	// RVA: 0x3210abc VA: 0x7595828abc
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x3210be4 VA: 0x7595828be4
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x3210d0c VA: 0x7595828d0c
	protected override Void BeforeShowEffect() { }
	// RVA: 0x3210d98 VA: 0x7595828d98
	protected override Void BeforeHideEffect() { }
	// RVA: 0x3210e24 VA: 0x7595828e24
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x3210ef0 VA: 0x7595828ef0
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x3210ef8 VA: 0x7595828ef8
	private Void <>xLuaBaseProxy_BeforeHideEffect() { }
	// RVA: 0x3210f00 VA: 0x7595828f00
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```