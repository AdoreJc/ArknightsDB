# DIYCameraSwitchTween

**Namespace:** ` `


## Fields

- `DIYCameraSwitchToggle m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DIYCameraSwitchTween : UISwitchTween
{
	private DIYCameraSwitchToggle m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x20


	// RVA: 0x3813098 VA: 0x7595e2b098
	public Void .ctor(DIYCameraSwitchToggle switchToggle) { }
	// RVA: 0x3813248 VA: 0x7595e2b248
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x3813478 VA: 0x7595e2b478
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x38136a8 VA: 0x7595e2b6a8
	protected override Void BeforeShowEffect() { }
	// RVA: 0x381373c VA: 0x7595e2b73c
	protected override Void AfterHideEffect() { }
	// RVA: 0x38137d0 VA: 0x7595e2b7d0
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x38137d8 VA: 0x7595e2b7d8
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
}
```