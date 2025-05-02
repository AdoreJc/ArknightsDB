# GroupFadeSwitchTween

**Namespace:** ` `


## Fields

- `Act42D0EffectDetailGroupView m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_BeforeHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GroupFadeSwitchTween : UISwitchTween
{
	private Act42D0EffectDetailGroupView m_closure; // 0x38
	private const Single ANIM_DURATION; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x320baec VA: 0x7595823aec
	public Void .ctor(Act42D0EffectDetailGroupView closrue) { }
	// RVA: 0x320dad4 VA: 0x7595825ad4
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x320db98 VA: 0x7595825b98
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x320dc5c VA: 0x7595825c5c
	protected override Void BeforeShowEffect() { }
	// RVA: 0x320dce8 VA: 0x7595825ce8
	protected override Void BeforeHideEffect() { }
	// RVA: 0x320dd74 VA: 0x7595825d74
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x320de40 VA: 0x7595825e40
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x320de48 VA: 0x7595825e48
	private Void <>xLuaBaseProxy_BeforeHideEffect() { }
	// RVA: 0x320de50 VA: 0x7595825e50
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```