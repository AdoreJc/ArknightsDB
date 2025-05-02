# DefaultDialogSwitchTween

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup m_alphaHandler`

- `Boolean m_ignoreTimeScale`

- `Single duration`


## Methods

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DefaultDialogSwitchTween : UISwitchTween
{
	private CanvasGroup m_alphaHandler; // 0x38
	private Boolean m_ignoreTimeScale; // 0x40
	public Single duration; // 0x44
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_ResetToState; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20


	// RVA: 0x22658ec VA: 0x759487d8ec
	public Void .ctor(CanvasGroup alphaHandler, Boolean ignoreTimeScale) { }
	// RVA: 0x2267580 VA: 0x759487f580
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2267658 VA: 0x759487f658
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2267760 VA: 0x759487f760
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x22677f8 VA: 0x759487f7f8
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2267870 VA: 0x759487f870
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
	// RVA: 0x226787c VA: 0x759487f87c
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
}
```