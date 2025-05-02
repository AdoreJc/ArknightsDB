# SwitchTween

**Namespace:** ` `


## Fields

- `Act25sideMapDecorMissionPlugin m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SwitchTween : UISwitchTween
{
	private Act25sideMapDecorMissionPlugin m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x3271228 VA: 0x7595889228
	public Void .ctor(Act25sideMapDecorMissionPlugin closure) { }
	// RVA: 0x32716d8 VA: 0x75958896d8
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x3271958 VA: 0x7595889958
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x3271bd8 VA: 0x7595889bd8
	protected override Void BeforeShowEffect() { }
	// RVA: 0x3271c84 VA: 0x7595889c84
	protected override Void AfterHideEffect() { }
	// RVA: 0x3271d30 VA: 0x7595889d30
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x3271f10 VA: 0x7595889f10
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x3271f18 VA: 0x7595889f18
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x3271f20 VA: 0x7595889f20
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```