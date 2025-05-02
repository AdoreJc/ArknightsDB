# ResponseState

**Namespace:** ` `


## Fields

- `FP m_costRequestRemainingTime`

- `CooperateGameMode mode`

- `Graphic mask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ResponseState : CostPanelState
{
	private FP m_costRequestRemainingTime; // 0x20
	private CooperateGameMode mode; // 0x28
	private Graphic mask; // 0x30


	// RVA: 0x20cc980 VA: 0x75946e4980
	public override Void Init(UICooperateCostHandlePanel getPanel) { }
	// RVA: 0x20ccab4 VA: 0x75946e4ab4
	public override Void OnEnter(CostState lastState) { }
	// RVA: 0x20ccc3c VA: 0x75946e4c3c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20cce54 VA: 0x75946e4e54
	public override Void OnExit(CostState newState) { }
	// RVA: 0x20caf80 VA: 0x75946e2f80
	public Void .ctor() { }
}
```