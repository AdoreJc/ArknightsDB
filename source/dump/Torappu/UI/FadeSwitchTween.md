# FadeSwitchTween

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup m_alphaHandler`

- `Boolean m_ignoreTimeScale`

- `Single m_activeAlpha`

- `Ease <ease>k__BackingField`

- `Boolean <dontDisableGameObject>k__BackingField`

- `Boolean <controlBlockRaycast>k__BackingField`

- `Durations <complexDuration>k__BackingField`

- `Single <duration>k__BackingField`


## Properties

- `Ease ease`

- `Boolean dontDisableGameObject`

- `Boolean controlBlockRaycast`

- `Durations complexDuration`

- `Single duration`

- `CanvasGroup alphaHandler`

- `Single activeAlpha`


## Methods

- `Ease get_ease()`

- `Void set_ease(Ease)`

- `Boolean get_dontDisableGameObject()`

- `Void set_dontDisableGameObject(Boolean)`

- `Boolean get_controlBlockRaycast()`

- `Void set_controlBlockRaycast(Boolean)`

- `Durations get_complexDuration()`

- `Void set_complexDuration(Durations)`

- `Single get_duration()`

- `Void set_duration(Single)`

- `CanvasGroup get_alphaHandler()`

- `Single get_activeAlpha()`

- `Void set_activeAlpha(Single)`

- `Void Release()`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class FadeSwitchTween : UISwitchTween
{
	public const Single DEFAULT_TWEEN_DURATION; // 0x0
	private CanvasGroup m_alphaHandler; // 0x38
	private Boolean m_ignoreTimeScale; // 0x40
	private Single m_activeAlpha; // 0x44
	private Ease <ease>k__BackingField; // 0x48
	private Boolean <dontDisableGameObject>k__BackingField; // 0x4c
	private Boolean <controlBlockRaycast>k__BackingField; // 0x4d
	private Durations <complexDuration>k__BackingField; // 0x50
	private Single <duration>k__BackingField; // 0x58
	private static __XLua_Gen_Delegate105 __Hotfix0_get_ease; // 0x0
	private static __XLua_Gen_Delegate106 __Hotfix0_set_ease; // 0x8
	private static __XLua_Gen_Delegate8 __Hotfix0_get_dontDisableGameObject; // 0x10
	private static __XLua_Gen_Delegate9 __Hotfix0_set_dontDisableGameObject; // 0x18
	private static __XLua_Gen_Delegate8 __Hotfix0_get_controlBlockRaycast; // 0x20
	private static __XLua_Gen_Delegate9 __Hotfix0_set_controlBlockRaycast; // 0x28
	private static __XLua_Gen_Delegate107 __Hotfix0_get_complexDuration; // 0x30
	private static __XLua_Gen_Delegate108 __Hotfix0_set_complexDuration; // 0x38
	private static __XLua_Gen_Delegate109 _c__Hotfix0_ctor; // 0x40
	private static __XLua_Gen_Delegate110 _c__Hotfix1_ctor; // 0x48
	private static __XLua_Gen_Delegate6 __Hotfix0_get_duration; // 0x50
	private static __XLua_Gen_Delegate7 __Hotfix0_set_duration; // 0x58
	private static __XLua_Gen_Delegate111 __Hotfix0_get_alphaHandler; // 0x60
	private static __XLua_Gen_Delegate6 __Hotfix0_get_activeAlpha; // 0x68
	private static __XLua_Gen_Delegate7 __Hotfix0_set_activeAlpha; // 0x70
	private static __XLua_Gen_Delegate112 __Hotfix0_GenerateTweenOfHide; // 0x78
	private static __XLua_Gen_Delegate112 __Hotfix0_GenerateTweenOfShow; // 0x80
	private static __XLua_Gen_Delegate1 __Hotfix0_BeforeShowEffect; // 0x88
	private static __XLua_Gen_Delegate1 __Hotfix0_AfterHideEffect; // 0x90
	private static __XLua_Gen_Delegate9 __Hotfix0_ResetToState; // 0x98
	private static __XLua_Gen_Delegate109 __Hotfix0_SetObjectActive; // 0xa0
	private static __XLua_Gen_Delegate1 __Hotfix0_Release; // 0xa8

	protected Ease ease { get; set; }
	protected Boolean dontDisableGameObject { get; set; }
	protected Boolean controlBlockRaycast { get; set; }
	protected Durations complexDuration { get; set; }
	public Single duration { get; set; }
	public CanvasGroup alphaHandler { get; }
	public Single activeAlpha { get; set; }

	// RVA: 0x678a74c VA: 0x7598da274c
	protected Ease get_ease() { }
	// RVA: 0x678a7bc VA: 0x7598da27bc
	private Void set_ease(Ease value) { }
	// RVA: 0x678a840 VA: 0x7598da2840
	protected Boolean get_dontDisableGameObject() { }
	// RVA: 0x678a8b0 VA: 0x7598da28b0
	private Void set_dontDisableGameObject(Boolean value) { }
	// RVA: 0x678a938 VA: 0x7598da2938
	protected Boolean get_controlBlockRaycast() { }
	// RVA: 0x678a9a8 VA: 0x7598da29a8
	private Void set_controlBlockRaycast(Boolean value) { }
	// RVA: 0x678aa30 VA: 0x7598da2a30
	protected Durations get_complexDuration() { }
	// RVA: 0x678aa9c VA: 0x7598da2a9c
	private Void set_complexDuration(Durations value) { }
	// RVA: 0x678ab28 VA: 0x7598da2b28
	public Void .ctor(CanvasGroup alphaHandler, Boolean ignoreTimeScale) { }
	// RVA: 0x678abcc VA: 0x7598da2bcc
	public Void .ctor(CanvasGroup alphaHandler, Single duration, Boolean ignoreTimeScale) { }
	// RVA: 0x678ada0 VA: 0x7598da2da0
	public Single get_duration() { }
	// RVA: 0x678ad1c VA: 0x7598da2d1c
	public Void set_duration(Single value) { }
	// RVA: 0x678ae10 VA: 0x7598da2e10
	public CanvasGroup get_alphaHandler() { }
	// RVA: 0x678ae80 VA: 0x7598da2e80
	public Single get_activeAlpha() { }
	// RVA: 0x678aef0 VA: 0x7598da2ef0
	public Void set_activeAlpha(Single value) { }
	// RVA: 0x678afa4 VA: 0x7598da2fa4
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x678b0f4 VA: 0x7598da30f4
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x678b248 VA: 0x7598da3248
	protected sealed override Void BeforeShowEffect() { }
	// RVA: 0x678b2e0 VA: 0x7598da32e0
	protected sealed override Void AfterHideEffect() { }
	// RVA: 0x678b360 VA: 0x7598da3360
	protected sealed override Void ResetToState(Boolean isShow) { }
	// RVA: 0x678b414 VA: 0x7598da3414
	protected virtual Void SetObjectActive(CanvasGroup alphaHandler, Boolean isActive) { }
	// RVA: 0x678b4f4 VA: 0x7598da34f4
	public Void Release() { }
	// RVA: 0x678b564 VA: 0x7598da3564
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x678b568 VA: 0x7598da3568
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x678b56c VA: 0x7598da356c
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```