# StorySwitchTween

**Namespace:** ` `


## Fields

- `DeepSeaRPBattleStoryView m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class StorySwitchTween : UISwitchTween
{
	private static readonly Vector2 LEFT_START_POS; // 0x0
	private static readonly Vector2 LEFT_END_POS; // 0x8
	private static readonly Vector2 RIGHT_START_POS; // 0x10
	private static readonly Vector2 RIGHT_END_POS; // 0x18
	private DeepSeaRPBattleStoryView m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x28
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x30
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x38
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x40
	private static DelegateBridge __Hotfix0_ResetToState; // 0x48


	// RVA: 0x29c1804 VA: 0x7594fd9804
	public Void .ctor(DeepSeaRPBattleStoryView closure) { }
	// RVA: 0x29c1938 VA: 0x7594fd9938
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x29c1ba4 VA: 0x7594fd9ba4
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x29c1e6c VA: 0x7594fd9e6c
	protected override Void BeforeShowEffect() { }
	// RVA: 0x29c1efc VA: 0x7594fd9efc
	protected override Void AfterHideEffect() { }
	// RVA: 0x29c1fa0 VA: 0x7594fd9fa0
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x29c21d0 VA: 0x7594fda1d0
	private static Void .cctor() { }
	// RVA: 0x29c2254 VA: 0x7594fda254
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x29c225c VA: 0x7594fda25c
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x29c2264 VA: 0x7594fda264
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```