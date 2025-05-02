# SelectionSwitchTween

**Namespace:** ` `


## Fields

- `SandboxV2NodeFloatView m_closure`

- `Tween m_selectionLoopTween`


## Methods

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SelectionSwitchTween : UISwitchTween
{
	private SandboxV2NodeFloatView m_closure; // 0x38
	private Tween m_selectionLoopTween; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x256399c VA: 0x7594b7b99c
	public Void .ctor(SandboxV2NodeFloatView closure) { }
	// RVA: 0x2563a40 VA: 0x7594b7ba40
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2563b44 VA: 0x7594b7bb44
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2563c48 VA: 0x7594b7bc48
	protected override Void AfterHideEffect() { }
	// RVA: 0x2563cfc VA: 0x7594b7bcfc
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2563e28 VA: 0x7594b7be28
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2563fa8 VA: 0x7594b7bfa8
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x2563fb0 VA: 0x7594b7bfb0
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x2563fb8 VA: 0x7594b7bfb8
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```