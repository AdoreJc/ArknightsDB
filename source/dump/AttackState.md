# AttackState

**Namespace:** ` `


## Methods

- `Void _AttackFinishCallback(Ability, FinishReason, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AttackState : BasicState
{
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0__AttackFinishCallback; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c0b8fc VA: 0x75942238fc
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c0be30 VA: 0x7594223e30
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c0bf90 VA: 0x7594223f90
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c0c0b8 VA: 0x75942240b8
	private Void _AttackFinishCallback(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1c09a40 VA: 0x7594221a40
	public Void .ctor() { }
}
```