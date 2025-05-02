# RoguelikeGameShopSwitchTween

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup m_alphaHandler`

- `RectTransform m_posHandler`

- `Vector2 m_hidePos`

- `Vector2 m_showPos`

- `Single m_duration`

- `Single m_hideDelay`

- `Single m_showDelay`

- `EaseFunction m_showEase`

- `EaseFunction m_hideEase`

- `Single m_time`

- `Single m_position`


## Methods

- `Void ResetShowDelay(Single)`

- `Void ForceSetProgress(Boolean, Single)`

- `Void ResetDuration(Single)`

- `Single _GetTargetTime(Boolean)`

- `Void _UpdateAlpha(Single)`

- `Void _UpdatePos(Single)`

- `Single <GenerateTweenOfHide>b__17_0()`

- `Void <GenerateTweenOfHide>b__17_1(Single)`

- `Single <GenerateTweenOfShow>b__18_0()`

- `Void <GenerateTweenOfShow>b__18_1(Single)`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameShopSwitchTween : UISwitchTween
{
	public const Single DEFAULT_TWEEN_DURATION; // 0x0
	private CanvasGroup m_alphaHandler; // 0x38
	private RectTransform m_posHandler; // 0x40
	private Vector2 m_hidePos; // 0x48
	private Vector2 m_showPos; // 0x50
	private Single m_duration; // 0x58
	private Single m_hideDelay; // 0x5c
	private Single m_showDelay; // 0x60
	private EaseFunction m_showEase; // 0x68
	private EaseFunction m_hideEase; // 0x70
	private Single m_time; // 0x78
	private Single m_position; // 0x7c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ResetShowDelay; // 0x8
	private static DelegateBridge __Hotfix0_ForceSetProgress; // 0x10
	private static DelegateBridge __Hotfix0_ResetDuration; // 0x18
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x20
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x28
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x30
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x38
	private static DelegateBridge __Hotfix0_ResetToState; // 0x40
	private static DelegateBridge __Hotfix0__GetTargetTime; // 0x48
	private static DelegateBridge __Hotfix0__UpdateAlpha; // 0x50
	private static DelegateBridge __Hotfix0__UpdatePos; // 0x58


	// RVA: 0x2ae0f24 VA: 0x75950f8f24
	public Void .ctor(CanvasGroup alphaHandler, RectTransform posHandler, Vector2 hidePos, Vector2 showPos, Single duration, Single hideDelay, Single showDelay, Ease showEase, Ease hideEase) { }
	// RVA: 0x2ae3ab0 VA: 0x75950fbab0
	public Void ResetShowDelay(Single showDelay) { }
	// RVA: 0x2ae3b2c VA: 0x75950fbb2c
	public Void ForceSetProgress(Boolean toShow, Single progress) { }
	// RVA: 0x2ae3c54 VA: 0x75950fbc54
	public Void ResetDuration(Single duration) { }
	// RVA: 0x2ae3cd0 VA: 0x75950fbcd0
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2ae3fe8 VA: 0x75950fbfe8
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2ae41e4 VA: 0x75950fc1e4
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2ae4264 VA: 0x75950fc264
	protected override Void AfterHideEffect() { }
	// RVA: 0x2ae42e4 VA: 0x75950fc2e4
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2ae3ecc VA: 0x75950fbecc
	private Single _GetTargetTime(Boolean isShow) { }
	// RVA: 0x2ae43c8 VA: 0x75950fc3c8
	private Void _UpdateAlpha(Single position) { }
	// RVA: 0x2ae4454 VA: 0x75950fc454
	private Void _UpdatePos(Single position) { }
	// RVA: 0x2ae4504 VA: 0x75950fc504
	private Single <GenerateTweenOfHide>b__17_0() { }
	// RVA: 0x2ae450c VA: 0x75950fc50c
	private Void <GenerateTweenOfHide>b__17_1(Single time) { }
	// RVA: 0x2ae4550 VA: 0x75950fc550
	private Single <GenerateTweenOfShow>b__18_0() { }
	// RVA: 0x2ae4558 VA: 0x75950fc558
	private Void <GenerateTweenOfShow>b__18_1(Single time) { }
	// RVA: 0x2ae45a8 VA: 0x75950fc5a8
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x2ae45b0 VA: 0x75950fc5b0
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x2ae45b8 VA: 0x75950fc5b8
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```