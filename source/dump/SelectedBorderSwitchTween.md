# SelectedBorderSwitchTween

**Namespace:** ` `


## Fields

- `CanvasGroup m_borderSelected`


## Methods

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class SelectedBorderSwitchTween : UISwitchTween
{
	private CanvasGroup m_borderSelected; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x26cbcb8 VA: 0x7594ce3cb8
	public Void .ctor(CanvasGroup borderSelected) { }
	// RVA: 0x26d04c0 VA: 0x7594ce84c0
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x26d059c VA: 0x7594ce859c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x26d0678 VA: 0x7594ce8678
	protected override Void AfterHideEffect() { }
	// RVA: 0x26d0704 VA: 0x7594ce8704
	protected override Void BeforeShowEffect() { }
	// RVA: 0x26d0790 VA: 0x7594ce8790
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x26d0844 VA: 0x7594ce8844
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x26d084c VA: 0x7594ce884c
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x26d0854 VA: 0x7594ce8854
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```