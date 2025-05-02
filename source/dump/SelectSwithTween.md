# SelectSwithTween

**Namespace:** ` `


## Fields

- `Act42D0EffectSelectItemView m_closure`

- `Tween m_lightTween`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SelectSwithTween : UISwitchTween
{
	private Act42D0EffectSelectItemView m_closure; // 0x38
	private Tween m_lightTween; // 0x40
	private const Single ANIM_DURATION; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x320f4e4 VA: 0x75958274e4
	public Void .ctor(Act42D0EffectSelectItemView closure) { }
	// RVA: 0x320f70c VA: 0x759582770c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x320f9fc VA: 0x75958279fc
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x320fc58 VA: 0x7595827c58
	protected override Void BeforeShowEffect() { }
	// RVA: 0x320fce0 VA: 0x7595827ce0
	protected override Void AfterHideEffect() { }
	// RVA: 0x320fd68 VA: 0x7595827d68
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x320ff20 VA: 0x7595827f20
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x320ff28 VA: 0x7595827f28
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x320ff30 VA: 0x7595827f30
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```