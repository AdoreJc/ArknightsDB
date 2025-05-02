# SelectedInShopSwitchTween

**Namespace:** ` `


## Fields

- `CarvingMainCardView m_closure`

- `Tween m_selectedInShopLightTween`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SelectedInShopSwitchTween : UISwitchTween
{
	private CarvingMainCardView m_closure; // 0x38
	private Tween m_selectedInShopLightTween; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x2da6ccc VA: 0x75953beccc
	public Void .ctor(CarvingMainCardView closure) { }
	// RVA: 0x2da7a4c VA: 0x75953bfa4c
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2da7b50 VA: 0x75953bfb50
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2da7c54 VA: 0x75953bfc54
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2da7d78 VA: 0x75953bfd78
	protected override Void AfterHideEffect() { }
	// RVA: 0x2da7e34 VA: 0x75953bfe34
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2da7f48 VA: 0x75953bff48
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x2da7f50 VA: 0x75953bff50
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x2da7f58 VA: 0x75953bff58
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```