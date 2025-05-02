# SkillState

**Namespace:** ` `


## Fields

- `FP m_remainingEscapeTime`


## Methods

- `Boolean _StartSkill()`

- `Void _DoStartSkill()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SkillState : BasicState
{
	private FP m_remainingEscapeTime; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0__StartSkill; // 0x18
	private static DelegateBridge __Hotfix0__DoStartSkill; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1bf43b0 VA: 0x759420c3b0
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1bf4538 VA: 0x759420c538
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1bf472c VA: 0x759420c72c
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1bf4808 VA: 0x759420c808
	private Boolean _StartSkill() { }
	// RVA: 0x1bf49e4 VA: 0x759420c9e4
	private Void _DoStartSkill() { }
	// RVA: 0x1bf1034 VA: 0x7594209034
	public Void .ctor() { }
}
```