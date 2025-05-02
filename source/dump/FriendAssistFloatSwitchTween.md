# FriendAssistFloatSwitchTween

**Namespace:** ` `


## Fields

- `FriendAssistItemFloatPanel m_closure`


## Methods

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FriendAssistFloatSwitchTween : UISwitchTween
{
	private const Single ANIM_DURATION; // 0x0
	private FriendAssistItemFloatPanel m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x28c89d4 VA: 0x7594ee09d4
	public Void .ctor(FriendAssistItemFloatPanel floatPanel) { }
	// RVA: 0x28c8f24 VA: 0x7594ee0f24
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x28c902c VA: 0x7594ee102c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x28c9134 VA: 0x7594ee1134
	protected override Void AfterHideEffect() { }
	// RVA: 0x28c91d4 VA: 0x7594ee11d4
	protected override Void BeforeShowEffect() { }
	// RVA: 0x28c92e8 VA: 0x7594ee12e8
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x28c93bc VA: 0x7594ee13bc
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x28c93c4 VA: 0x7594ee13c4
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x28c93cc VA: 0x7594ee13cc
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```