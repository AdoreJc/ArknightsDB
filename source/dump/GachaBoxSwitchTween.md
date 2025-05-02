# GachaBoxSwitchTween

**Namespace:** ` `


## Fields

- `Act24sideMeldingView m_closure`


## Methods

- `Void _ResetTotem(Boolean)`

- `Tweener _GetTotemTween(Material, Boolean)`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GachaBoxSwitchTween : UISwitchTween
{
	private Act24sideMeldingView m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_ResetToState; // 0x18
	private static DelegateBridge __Hotfix0__ResetTotem; // 0x20
	private static DelegateBridge __Hotfix0__GetTotemTween; // 0x28


	// RVA: 0x32a86b4 VA: 0x75958c06b4
	public Void .ctor(Act24sideMeldingView itemView) { }
	// RVA: 0x32aa3ac VA: 0x75958c23ac
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x32aa8d0 VA: 0x75958c28d0
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x32aac4c VA: 0x75958c2c4c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x32aad40 VA: 0x75958c2d40
	private Void _ResetTotem(Boolean isSecond) { }
	// RVA: 0x32aa728 VA: 0x75958c2728
	private Tweener _GetTotemTween(Material mat, Boolean isShow) { }
	// RVA: 0x32aae38 VA: 0x75958c2e38
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```