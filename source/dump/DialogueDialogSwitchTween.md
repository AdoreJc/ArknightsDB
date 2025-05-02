# DialogueDialogSwitchTween

**Namespace:** ` `


## Fields

- `CarvingDialogueDialog m_closure`

- `Single m_duration`


## Methods

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DialogueDialogSwitchTween : UISwitchTween, IHotfixable
{
	private CarvingDialogueDialog m_closure; // 0x38
	private Single m_duration; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_ResetToState; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20


	// RVA: 0x2d90614 VA: 0x75953a8614
	public Void .ctor(CarvingDialogueDialog closure) { }
	// RVA: 0x2d90a14 VA: 0x75953a8a14
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2d90b18 VA: 0x75953a8b18
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2d90c70 VA: 0x75953a8c70
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2d90d64 VA: 0x75953a8d64
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2d90e24 VA: 0x75953a8e24
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
	// RVA: 0x2d90e30 VA: 0x75953a8e30
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
}
```