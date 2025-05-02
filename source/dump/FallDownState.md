# FallDownState

**Namespace:** ` `


## Fields

- `Single FALLDOWN_TIME`

- `Single FALLDOWN_HEIGHT_OFFSET`

- `Single FALLDOWN_SHRINK_SCALE`

- `Tween m_tween`


## Methods

- `Void _PlayAnimation()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FallDownState : BasicState
{
	private Single FALLDOWN_TIME; // 0x18
	private Single FALLDOWN_HEIGHT_OFFSET; // 0x1c
	private Single FALLDOWN_SHRINK_SCALE; // 0x20
	private Tween m_tween; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnExit; // 0x8
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnimation; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c10d7c VA: 0x7594228d7c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c1143c VA: 0x759422943c
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c11520 VA: 0x7594229520
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1c10e74 VA: 0x7594228e74
	private Void _PlayAnimation() { }
	// RVA: 0x1c09d34 VA: 0x7594221d34
	public Void .ctor() { }
}
```