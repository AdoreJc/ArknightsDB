# FadeTranslationSwitchTween

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup m_alphaHandler`

- `RectTransform m_posHandler`

- `Vector2 m_hidePos`

- `Vector2 m_showPos`

- `Single m_duration`

- `Single m_hideDelay`

- `Single m_showDelay`


## Methods

- `Single GetTargetAlpha(Boolean)`

- `Vector2 GetTargetPos(Boolean)`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class FadeTranslationSwitchTween : UISwitchTween
{
	private const Single DEFAULT_TWEEN_DURATION; // 0x0
	private CanvasGroup m_alphaHandler; // 0x38
	private RectTransform m_posHandler; // 0x40
	private Vector2 m_hidePos; // 0x48
	private Vector2 m_showPos; // 0x50
	private Single m_duration; // 0x58
	private Single m_hideDelay; // 0x5c
	private Single m_showDelay; // 0x60
	private static __XLua_Gen_Delegate113 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate112 __Hotfix0_GenerateTweenOfHide; // 0x8
	private static __XLua_Gen_Delegate112 __Hotfix0_GenerateTweenOfShow; // 0x10
	private static __XLua_Gen_Delegate1 __Hotfix0_BeforeShowEffect; // 0x18
	private static __XLua_Gen_Delegate1 __Hotfix0_AfterHideEffect; // 0x20
	private static __XLua_Gen_Delegate9 __Hotfix0_ResetToState; // 0x28
	private static __XLua_Gen_Delegate114 __Hotfix0_GetTargetAlpha; // 0x30
	private static __XLua_Gen_Delegate115 __Hotfix0_GetTargetPos; // 0x38


	// RVA: 0x678b62c VA: 0x7598da362c
	public Void .ctor(CanvasGroup alphaHandler, RectTransform posHandler, Vector2 hidePos, Vector2 showPos, Single duration, Single hideDelay, Single showDelay) { }
	// RVA: 0x678b7fc VA: 0x7598da37fc
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x678bb18 VA: 0x7598da3b18
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x678bc68 VA: 0x7598da3c68
	protected override Void BeforeShowEffect() { }
	// RVA: 0x678bcf0 VA: 0x7598da3cf0
	protected override Void AfterHideEffect() { }
	// RVA: 0x678bd78 VA: 0x7598da3d78
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x678b94c VA: 0x7598da394c
	private Single GetTargetAlpha(Boolean isShow) { }
	// RVA: 0x678b9dc VA: 0x7598da39dc
	private Vector2 GetTargetPos(Boolean isShow) { }
	// RVA: 0x678be58 VA: 0x7598da3e58
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x678be5c VA: 0x7598da3e5c
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x678be60 VA: 0x7598da3e60
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```