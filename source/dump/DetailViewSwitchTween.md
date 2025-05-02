# DetailViewSwitchTween

**Namespace:** ` `


## Fields

- `DeepSeaRPBattleDetailView m_closure`


## Methods

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_AfterShowEffect()`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DetailViewSwitchTween : UISwitchTween
{
	private const Single FADE_POS_Y; // 0x0
	private DeepSeaRPBattleDetailView m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x10
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x18
	private static DelegateBridge __Hotfix0_AfterShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x28
	private static DelegateBridge __Hotfix0_ResetToState; // 0x30


	// RVA: 0x29bc01c VA: 0x7594fd401c
	public Void .ctor(DeepSeaRPBattleDetailView closure) { }
	// RVA: 0x29bc180 VA: 0x7594fd4180
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x29bc31c VA: 0x7594fd431c
	protected override Void AfterHideEffect() { }
	// RVA: 0x29bc424 VA: 0x7594fd4424
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x29bc5b4 VA: 0x7594fd45b4
	protected override Void AfterShowEffect() { }
	// RVA: 0x29bc694 VA: 0x7594fd4694
	protected override Void BeforeShowEffect() { }
	// RVA: 0x29bc720 VA: 0x7594fd4720
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x29bc88c VA: 0x7594fd488c
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x29bc894 VA: 0x7594fd4894
	private Void <>xLuaBaseProxy_AfterShowEffect() { }
	// RVA: 0x29bc89c VA: 0x7594fd489c
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x29bc8a4 VA: 0x7594fd48a4
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```