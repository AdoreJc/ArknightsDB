# RequestState

**Namespace:** ` `


## Fields

- `FP m_costRequestRemainingTime`

- `CooperateGameMode mode`


## Methods

- `Void <OnExit>b__5_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RequestState : CostPanelState
{
	private FP m_costRequestRemainingTime; // 0x20
	private CooperateGameMode mode; // 0x28


	// RVA: 0x20cc470 VA: 0x75946e4470
	public override Void Init(UICooperateCostHandlePanel getPanel) { }
	// RVA: 0x20cc5a4 VA: 0x75946e45a4
	public override Void OnEnter(CostState lastState) { }
	// RVA: 0x20cc658 VA: 0x75946e4658
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20cc860 VA: 0x75946e4860
	public override Void OnExit(CostState newState) { }
	// RVA: 0x20caf18 VA: 0x75946e2f18
	public Void .ctor() { }
	// RVA: 0x20cc95c VA: 0x75946e495c
	private Void <OnExit>b__5_0() { }
}
```