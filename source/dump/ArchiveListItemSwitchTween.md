# ArchiveListItemSwitchTween

**Namespace:** ` `


## Fields

- `ArchiveListItemView m_closure`


## Methods

- `Sequence _GenerateSequence(Boolean)`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_AfterShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ArchiveListItemSwitchTween : UISwitchTween
{
	private ArchiveListItemView m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__GenerateSequence; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x18
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_AfterShowEffect; // 0x28
	private static DelegateBridge __Hotfix0_ResetToState; // 0x30


	// RVA: 0x303379c VA: 0x759564b79c
	public Void .ctor(ArchiveListItemView closure) { }
	// RVA: 0x30339c0 VA: 0x759564b9c0
	private Sequence _GenerateSequence(Boolean isFocus) { }
	// RVA: 0x3033db4 VA: 0x759564bdb4
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x3033e64 VA: 0x759564be64
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x3033f14 VA: 0x759564bf14
	protected override Void AfterHideEffect() { }
	// RVA: 0x3033fa0 VA: 0x759564bfa0
	protected override Void AfterShowEffect() { }
	// RVA: 0x303402c VA: 0x759564c02c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x30342a8 VA: 0x759564c2a8
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x30342b0 VA: 0x759564c2b0
	private Void <>xLuaBaseProxy_AfterShowEffect() { }
	// RVA: 0x30342b8 VA: 0x759564c2b8
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```