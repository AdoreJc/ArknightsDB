# TechUnlockTipsPopTween

**Namespace:** ` `


## Fields

- `DeepSeaRPZoneBarContainer m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TechUnlockTipsPopTween : UISwitchTween
{
	private DeepSeaRPZoneBarContainer m_closure; // 0x38
	private static readonly Vector2 TIPS_END_POS; // 0x0
	private const Single TECH_TIPS_START_SHOW_DELAY; // 0x0
	private const Single TECH_TIPS_SHOW_ANIM_DUR; // 0x0
	private const Single TECH_TIPS_STAY_ANIM_DUR; // 0x0
	private const Single TECH_TIPS_HIDE_ANIM_DUR; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_AfterShowEffect; // 0x28
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x30
	private static DelegateBridge __Hotfix0_ResetToState; // 0x38


	// RVA: 0x29cd720 VA: 0x7594fe5720
	public Void .ctor(DeepSeaRPZoneBarContainer closure) { }
	// RVA: 0x29ce8bc VA: 0x7594fe68bc
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x29ce9d4 VA: 0x7594fe69d4
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x29cebdc VA: 0x7594fe6bdc
	protected override Void BeforeShowEffect() { }
	// RVA: 0x29cec74 VA: 0x7594fe6c74
	protected override Void AfterShowEffect() { }
	// RVA: 0x29ced04 VA: 0x7594fe6d04
	protected override Void AfterHideEffect() { }
	// RVA: 0x29ced94 VA: 0x7594fe6d94
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x29cee5c VA: 0x7594fe6e5c
	private static Void .cctor() { }
	// RVA: 0x29ceeac VA: 0x7594fe6eac
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x29ceeb4 VA: 0x7594fe6eb4
	private Void <>xLuaBaseProxy_AfterShowEffect() { }
	// RVA: 0x29ceebc VA: 0x7594fe6ebc
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x29ceec4 VA: 0x7594fe6ec4
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```