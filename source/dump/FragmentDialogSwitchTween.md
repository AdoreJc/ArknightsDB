# FragmentDialogSwitchTween

**Namespace:** ` `


## Fields

- `RL04FragmentDialog m_closure`

- `Single m_duration`


## Methods

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`

- `Void <>xLuaBaseProxy_BeforeShowEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FragmentDialogSwitchTween : UISwitchTween, IHotfixable
{
	private RL04FragmentDialog m_closure; // 0x38
	private Single m_duration; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x10
	private static DelegateBridge __Hotfix0_ResetToState; // 0x18
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x20


	// RVA: 0x2b240b4 VA: 0x759513c0b4
	public Void .ctor(RL04FragmentDialog closure) { }
	// RVA: 0x2b251f4 VA: 0x759513d1f4
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x2b252f8 VA: 0x759513d2f8
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2b25450 VA: 0x759513d450
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x2b25544 VA: 0x759513d544
	protected override Void BeforeShowEffect() { }
	// RVA: 0x2b255f8 VA: 0x759513d5f8
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
	// RVA: 0x2b25604 VA: 0x759513d604
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
}
```