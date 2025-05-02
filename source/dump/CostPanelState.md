# CostPanelState

**Namespace:** ` `


## Fields

- `FP <data>k__BackingField`

- `UICooperateCostHandlePanel panel`


## Properties

- `FP data`


## Methods

- `FP get_data()`

- `Void set_data(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CostPanelState
{
	private FP <data>k__BackingField; // 0x10
	public UICooperateCostHandlePanel panel; // 0x18

	public FP data { get; set; }

	// RVA: 0x20cbe80 VA: 0x75946e3e80
	public FP get_data() { }
	// RVA: 0x20cbe88 VA: 0x75946e3e88
	public Void set_data(FP value) { }
	// RVA: 0x20cbe90 VA: 0x75946e3e90
	public virtual Void OnEnter(CostState lastState) { }
	// RVA: 0x20cbe94 VA: 0x75946e3e94
	public virtual Void OnTick(FP deltaTime) { }
	// RVA: 0x20cbe98 VA: 0x75946e3e98
	public virtual Void OnExit(CostState newState) { }
	// RVA: 0x20cbe9c VA: 0x75946e3e9c
	public virtual Void Init(UICooperateCostHandlePanel getPanel) { }
	// RVA: 0x20cbea4 VA: 0x75946e3ea4
	public Void .ctor() { }
}
```