# LoadingShowSwitchTween

**Namespace:** ` `


## Fields

- `AnimationWrapper m_anim1`

- `AnimationWrapper m_anim2`

- `UIFadeFloatPanel m_maskView`

- `Tween m_selectionLoopTween`


## Methods

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LoadingShowSwitchTween : UISwitchTween
{
	private AnimationWrapper m_anim1; // 0x38
	private AnimationWrapper m_anim2; // 0x40
	private UIFadeFloatPanel m_maskView; // 0x48
	private Tween m_selectionLoopTween; // 0x50
	private const String LOADING_ENTER_ANIM; // 0x0
	private const String LOADING_HIDE_ANIM; // 0x0
	private const String LOADING_LOOP_ANIM; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x377234c VA: 0x7595d8a34c
	public Void .ctor(UIFadeFloatPanel maskView, AnimationWrapper entry, AnimationWrapper loop) { }
	// RVA: 0x3773b1c VA: 0x7595d8bb1c
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x3773bf0 VA: 0x7595d8bbf0
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x3773cc4 VA: 0x7595d8bcc4
	protected override Void AfterHideEffect() { }
	// RVA: 0x3773d94 VA: 0x7595d8bd94
	protected override Void BeforeShowEffect() { }
	// RVA: 0x3773edc VA: 0x7595d8bedc
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x3774064 VA: 0x7595d8c064
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x377406c VA: 0x7595d8c06c
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x3774074 VA: 0x7595d8c074
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```