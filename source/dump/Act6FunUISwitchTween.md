# Act6FunUISwitchTween

**Namespace:** ` `


## Fields

- `Single m_inactiveAlpha`

- `Single m_activeAlpha`

- `CanvasGroup m_alphaHandler`


## Methods

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Act6FunUISwitchTween : UISwitchTween
{
	private Single m_inactiveAlpha; // 0x38
	private Single m_activeAlpha; // 0x3c
	private CanvasGroup m_alphaHandler; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_ResetToState; // 0x18


	// RVA: 0x20fc0ac VA: 0x75947140ac
	public Void .ctor(CanvasGroup alphaHandler, Single inactiveAlpha, Single activeAlpha) { }
	// RVA: 0x20fc4a4 VA: 0x75947144a4
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x20fc580 VA: 0x7594714580
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x20fc65c VA: 0x759471465c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x20fc6f8 VA: 0x75947146f8
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```