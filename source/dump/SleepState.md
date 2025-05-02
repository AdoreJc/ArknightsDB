# SleepState

**Namespace:** ` `


## Fields

- `Boolean m_skeletonUpdateNothing`


## Methods

- `Void _FreezeAnimation(SkeletonAnimation, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SleepState : StateNode
{
	private Boolean m_skeletonUpdateNothing; // 0x18


	// RVA: 0x3850ef4 VA: 0x7595e68ef4
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3851014 VA: 0x7595e69014
	private Void _FreezeAnimation(SkeletonAnimation skeleton, Boolean forceUpdateBeforeFreeze) { }
	// RVA: 0x38510a0 VA: 0x7595e690a0
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x385113c VA: 0x7595e6913c
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x38511b8 VA: 0x7595e691b8
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x384cfb8 VA: 0x7595e64fb8
	public Void .ctor() { }
}
```