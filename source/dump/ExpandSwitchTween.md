# ExpandSwitchTween

**Namespace:** ` `


## Fields

- `RoguelikeTopicInnerTaskObject m_closure`

- `Single m_tweenValue`

- `AnimationHandler m_animationHandler`


## Methods

- `Single _GetValue()`

- `Void _SetValue(Single)`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ExpandSwitchTween : UISwitchTween
{
	private RoguelikeTopicInnerTaskObject m_closure; // 0x38
	private Single m_tweenValue; // 0x40
	private AnimationHandler m_animationHandler; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__GetValue; // 0x8
	private static DelegateBridge __Hotfix0__SetValue; // 0x10
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x18
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x2a71fa4 VA: 0x7595089fa4
	public Void .ctor(RoguelikeTopicInnerTaskObject closure) { }
	// RVA: 0x2a7252c VA: 0x759508a52c
	private Single _GetValue() { }
	// RVA: 0x2a72594 VA: 0x759508a594
	private Void _SetValue(Single value) { }
	// RVA: 0x2a72654 VA: 0x759508a654
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2a72800 VA: 0x759508a800
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2a729ac VA: 0x759508a9ac
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2a72a74 VA: 0x759508aa74
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```