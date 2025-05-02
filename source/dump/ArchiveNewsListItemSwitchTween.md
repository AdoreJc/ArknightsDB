# ArchiveNewsListItemSwitchTween

**Namespace:** ` `


## Fields

- `ArchiveNewsListItemView m_closure`


## Methods

- `Sequence _GenerateSequence(Boolean)`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_AfterShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ArchiveNewsListItemSwitchTween : UISwitchTween
{
	private ArchiveNewsListItemView m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__GenerateSequence; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x18
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_AfterShowEffect; // 0x28
	private static DelegateBridge __Hotfix0_ResetToState; // 0x30


	// RVA: 0x3065c50 VA: 0x759567dc50
	public Void .ctor(ArchiveNewsListItemView closure) { }
	// RVA: 0x3065e74 VA: 0x759567de74
	private Sequence _GenerateSequence(Boolean isFocus) { }
	// RVA: 0x3066224 VA: 0x759567e224
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x30662d4 VA: 0x759567e2d4
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x3066384 VA: 0x759567e384
	protected override Void AfterHideEffect() { }
	// RVA: 0x3066410 VA: 0x759567e410
	protected override Void AfterShowEffect() { }
	// RVA: 0x306649c VA: 0x759567e49c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x30666f8 VA: 0x759567e6f8
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x3066700 VA: 0x759567e700
	private Void <>xLuaBaseProxy_AfterShowEffect() { }
	// RVA: 0x3066708 VA: 0x759567e708
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```