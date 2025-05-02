# FadeTranslationSwitchTween

**Namespace:** ` `


## Fields

- `SiracusaCharTaskRingItemView m_closure`

- `CanvasGroup m_alphaHandler`

- `LayoutElement m_layoutElement`

- `Graphic m_line`

- `Single m_duration`


## Methods

- `ITweenHandler _GenerateTween(Boolean)`

- `Single GetTargetAlpha(Boolean)`

- `Single GetTargetHeight(Boolean)`

- `Single <_GenerateTween>b__9_0()`

- `Void <_GenerateTween>b__9_1(Single)`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FadeTranslationSwitchTween : UISwitchTween
{
	private SiracusaCharTaskRingItemView m_closure; // 0x38
	private CanvasGroup m_alphaHandler; // 0x40
	private LayoutElement m_layoutElement; // 0x48
	private Graphic m_line; // 0x50
	private Single m_duration; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0__GenerateTween; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x28
	private static DelegateBridge __Hotfix0_ResetToState; // 0x30
	private static DelegateBridge __Hotfix0_GetTargetAlpha; // 0x38
	private static DelegateBridge __Hotfix0_GetTargetHeight; // 0x40


	// RVA: 0x23ea700 VA: 0x7594a02700
	public Void .ctor(SiracusaCharTaskRingItemView closure) { }
	// RVA: 0x23ea8f0 VA: 0x7594a028f0
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x23eab6c VA: 0x7594a02b6c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x23ea95c VA: 0x7594a0295c
	private ITweenHandler _GenerateTween(Boolean isShow) { }
	// RVA: 0x23eadc0 VA: 0x7594a02dc0
	protected override Void BeforeShowEffect() { }
	// RVA: 0x23eae5c VA: 0x7594a02e5c
	protected override Void AfterHideEffect() { }
	// RVA: 0x23eaef8 VA: 0x7594a02ef8
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x23eabd8 VA: 0x7594a02bd8
	private Single GetTargetAlpha(Boolean isShow) { }
	// RVA: 0x23eac60 VA: 0x7594a02c60
	private Single GetTargetHeight(Boolean isShow) { }
	// RVA: 0x23eb014 VA: 0x7594a03014
	private Single <_GenerateTween>b__9_0() { }
	// RVA: 0x23eb038 VA: 0x7594a03038
	private Void <_GenerateTween>b__9_1(Single val) { }
	// RVA: 0x23eb05c VA: 0x7594a0305c
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x23eb064 VA: 0x7594a03064
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x23eb06c VA: 0x7594a0306c
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```