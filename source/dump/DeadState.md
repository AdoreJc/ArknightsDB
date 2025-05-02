# DeadState

**Namespace:** ` `


## Fields

- `Tween m_tween`


## Methods

- `Void _PlayAnimation()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DeadState : BasicState
{
	private Tween m_tween; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnExit; // 0x8
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnimation; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c0c184 VA: 0x7594224184
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c0c91c VA: 0x759422491c
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c0ca00 VA: 0x7594224a00
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1c0c338 VA: 0x7594224338
	private Void _PlayAnimation() { }
	// RVA: 0x1c09b84 VA: 0x7594221b84
	public Void .ctor() { }
}
```