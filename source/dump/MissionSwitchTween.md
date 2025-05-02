# MissionSwitchTween

**Namespace:** ` `


## Fields

- `Act13sideDecorMissionView m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_BeforeHideEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MissionSwitchTween : UISwitchTween
{
	private Act13sideDecorMissionView m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x28
	private static DelegateBridge __Hotfix0_ResetToState; // 0x30


	// RVA: 0x3446cc8 VA: 0x7595a5ecc8
	public Void .ctor(Act13sideDecorMissionView closure) { }
	// RVA: 0x3447454 VA: 0x7595a5f454
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x34475b4 VA: 0x7595a5f5b4
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x3447784 VA: 0x7595a5f784
	protected override Void BeforeShowEffect() { }
	// RVA: 0x344780c VA: 0x7595a5f80c
	protected override Void BeforeHideEffect() { }
	// RVA: 0x3447894 VA: 0x7595a5f894
	protected override Void AfterHideEffect() { }
	// RVA: 0x3447930 VA: 0x7595a5f930
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x3447aa4 VA: 0x7595a5faa4
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x3447aac VA: 0x7595a5faac
	private Void <>xLuaBaseProxy_BeforeHideEffect() { }
	// RVA: 0x3447ab4 VA: 0x7595a5fab4
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x3447abc VA: 0x7595a5fabc
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```