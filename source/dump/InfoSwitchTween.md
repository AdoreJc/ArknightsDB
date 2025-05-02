# InfoSwitchTween

**Namespace:** ` `


## Fields

- `DeepSeaRPBattlePreviewInfoBasicPanel m_closure`


## Methods

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class InfoSwitchTween : UISwitchTween
{
	private DeepSeaRPBattlePreviewInfoBasicPanel m_closure; // 0x38
	private const Single HIDE_POSITION_Y; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x18
	private static DelegateBridge __Hotfix0_ResetToState; // 0x20


	// RVA: 0x29bd910 VA: 0x7594fd5910
	public Void .ctor(DeepSeaRPBattlePreviewInfoBasicPanel closure) { }
	// RVA: 0x29bda50 VA: 0x7594fd5a50
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x29bdb20 VA: 0x7594fd5b20
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x29bdcf0 VA: 0x7594fd5cf0
	protected override Void AfterHideEffect() { }
	// RVA: 0x29bddc4 VA: 0x7594fd5dc4
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x29bdf18 VA: 0x7594fd5f18
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x29bdf20 VA: 0x7594fd5f20
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```