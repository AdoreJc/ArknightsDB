# InquireFadeSwitchTween

**Namespace:** ` `


## Fields

- `GrocerySellView m_closure`


## Methods

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterShowEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InquireFadeSwitchTween : UISwitchTween, IHotfixable
{
	private GrocerySellView m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ResetToState; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_AfterShowEffect; // 0x28


	// RVA: 0x289e848 VA: 0x7594eb6848
	public Void .ctor(GrocerySellView closure) { }
	// RVA: 0x289eef4 VA: 0x7594eb6ef4
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x289f00c VA: 0x7594eb700c
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x289f0f0 VA: 0x7594eb70f0
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x289f21c VA: 0x7594eb721c
	protected override Void BeforeShowEffect() { }
	// RVA: 0x289f2d8 VA: 0x7594eb72d8
	protected override Void AfterShowEffect() { }
	// RVA: 0x289f378 VA: 0x7594eb7378
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
	// RVA: 0x289f384 VA: 0x7594eb7384
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x289f38c VA: 0x7594eb738c
	private Void <>xLuaBaseProxy_AfterShowEffect() { }
}
```