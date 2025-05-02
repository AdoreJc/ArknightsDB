# SelectedSwitchTween

**Namespace:** ` `


## Fields

- `ClimbTowerTrapMenuObject m_closure`


## Methods

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SelectedSwitchTween : UISwitchTween
{
	private const Single ANIM_DURATION; // 0x0
	private const Single ALPHA_SELECTED_BKG; // 0x0
	private ClimbTowerTrapMenuObject m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x2c879a0 VA: 0x759529f9a0
	public Void .ctor(ClimbTowerTrapMenuObject closure) { }
	// RVA: 0x2c88384 VA: 0x75952a0384
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2c884fc VA: 0x75952a04fc
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2c88678 VA: 0x75952a0678
	protected override Void AfterHideEffect() { }
	// RVA: 0x2c8870c VA: 0x75952a070c
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2c887a0 VA: 0x75952a07a0
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2c88898 VA: 0x75952a0898
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x2c888a0 VA: 0x75952a08a0
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x2c888a8 VA: 0x75952a08a8
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```