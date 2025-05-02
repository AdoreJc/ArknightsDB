# AnimationSwitchTween

**Namespace:** `Torappu.UI`


## Fields

- `UIAnimationLocation m_animLocation`

- `GameObject m_targetObject`

- `Boolean m_inactivateTargetIfHide`

- `Boolean m_tweenFromStart`

- `Ease m_ease`

- `Boolean m_ignoreTimeScale`

- `Single <duration>k__BackingField`


## Properties

- `Single duration`

- `Boolean inactivateTargetIfHide`


## Methods

- `Single get_duration()`

- `Void set_duration(Single)`

- `Boolean get_inactivateTargetIfHide()`

- `Void set_inactivateTargetIfHide(Boolean)`

- `Boolean _ResetTargetDisplayStatus(Boolean)`

- `Boolean _UseLastStopPos(TweenContext)`

- `Void Release()`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class AnimationSwitchTween : UISwitchTween
{
	private UIAnimationLocation m_animLocation; // 0x38
	private GameObject m_targetObject; // 0x48
	private Boolean m_inactivateTargetIfHide; // 0x50
	private Boolean m_tweenFromStart; // 0x51
	private Ease m_ease; // 0x54
	private Boolean m_ignoreTimeScale; // 0x58
	private Single <duration>k__BackingField; // 0x5c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_duration; // 0x8
	private static DelegateBridge __Hotfix0_set_duration; // 0x10
	private static DelegateBridge __Hotfix0_get_inactivateTargetIfHide; // 0x18
	private static DelegateBridge __Hotfix0_set_inactivateTargetIfHide; // 0x20
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x28
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x30
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x38
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x40
	private static DelegateBridge __Hotfix0_ResetToState; // 0x48
	private static DelegateBridge __Hotfix0__ResetTargetDisplayStatus; // 0x50
	private static DelegateBridge __Hotfix0__UseLastStopPos; // 0x58
	private static DelegateBridge __Hotfix0_Release; // 0x60

	public Single duration { get; set; }
	public Boolean inactivateTargetIfHide { get; set; }

	// RVA: 0x217990c VA: 0x759479190c
	public Void .ctor(UIAnimationLocation location, GameObject targetObject, Single duration) { }
	// RVA: 0x2179b9c VA: 0x7594791b9c
	public Single get_duration() { }
	// RVA: 0x2179b20 VA: 0x7594791b20
	private Void set_duration(Single value) { }
	// RVA: 0x2179c04 VA: 0x7594791c04
	public Boolean get_inactivateTargetIfHide() { }
	// RVA: 0x2179c6c VA: 0x7594791c6c
	public Void set_inactivateTargetIfHide(Boolean value) { }
	// RVA: 0x2179cec VA: 0x7594791cec
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x217a03c VA: 0x759479203c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x217a1e4 VA: 0x75947921e4
	protected override Void BeforeShowEffect() { }
	// RVA: 0x217a348 VA: 0x7594792348
	protected override Void AfterHideEffect() { }
	// RVA: 0x217a3d8 VA: 0x75947923d8
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x217a2a8 VA: 0x75947922a8
	private Boolean _ResetTargetDisplayStatus(Boolean isShow) { }
	// RVA: 0x2179e84 VA: 0x7594791e84
	private Boolean _UseLastStopPos(TweenContext context) { }
	// RVA: 0x217a494 VA: 0x7594792494
	public Void Release() { }
	// RVA: 0x217a500 VA: 0x7594792500
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x217a508 VA: 0x7594792508
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x217a510 VA: 0x7594792510
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```