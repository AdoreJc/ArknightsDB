# UIBiAnimClipSwitchTween

**Namespace:** `Torappu.UI`


## Fields

- `UIAnimationLocation m_clipOn`

- `UIAnimationLocation m_clipOff`

- `Single m_durationOn`

- `Single m_durationOff`

- `Ease m_easeOn`

- `Ease m_easeOff`

- `Boolean m_tweenFromStart`

- `Boolean m_ignoreTimeScale`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIBiAnimClipSwitchTween : UISwitchTween
{
	private UIAnimationLocation m_clipOn; // 0x38
	private UIAnimationLocation m_clipOff; // 0x48
	private Single m_durationOn; // 0x58
	private Single m_durationOff; // 0x5c
	private Ease m_easeOn; // 0x60
	private Ease m_easeOff; // 0x64
	private Boolean m_tweenFromStart; // 0x68
	private Boolean m_ignoreTimeScale; // 0x69
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0__UseLastStopPos; // 0x18
	private static DelegateBridge __Hotfix0__GenerateAnimTween; // 0x20
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x28
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x30
	private static DelegateBridge __Hotfix0_ResetToState; // 0x38


	// RVA: 0x217a690 VA: 0x7594792690
	private Void .ctor() { }
	// RVA: 0x217a700 VA: 0x7594792700
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x217aa44 VA: 0x7594792a44
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x217ab00 VA: 0x7594792b00
	private static Boolean _UseLastStopPos(TweenContext context, Boolean tweenFromStart) { }
	// RVA: 0x217a7bc VA: 0x75947927bc
	private static UIAnimationTween _GenerateAnimTween(TweenContext context, Boolean tweenFromStart, UIAnimationLocation animClip, Single duration, Ease ease, Boolean ignoreTimeScale) { }
	// RVA: 0x217ac18 VA: 0x7594792c18
	protected override Void BeforeShowEffect() { }
	// RVA: 0x217acd8 VA: 0x7594792cd8
	protected override Void AfterHideEffect() { }
	// RVA: 0x217ad4c VA: 0x7594792d4c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x217ade8 VA: 0x7594792de8
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x217adf0 VA: 0x7594792df0
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x217adf8 VA: 0x7594792df8
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```