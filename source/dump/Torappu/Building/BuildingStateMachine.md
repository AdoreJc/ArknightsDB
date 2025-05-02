# BuildingStateMachine

**Namespace:** `Torappu.Building`


## Fields

- `Boolean m_isTransiting`

- `BuildingController <controller>k__BackingField`


## Properties

- `IBuildingMode currentMode`

- `BuildingModel model`

- `BuildingController controller`

- `Boolean isTransiting`


## Methods

- `IBuildingMode get_currentMode()`

- `BuildingModel get_model()`

- `BuildingController get_controller()`

- `Void set_controller(BuildingController)`

- `Boolean get_isTransiting()`

- `Void RegisterState(IBuildingMode, Boolean)`

- `Void SwitchMode(TransitionParam)`

- `T GetMode()`

- `Void Start()`

- `Void SetDefaultMode()`

- `IEnumerator _DoModeTransition(TransitionParam, IBuildingMode, IBuildingMode)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingStateMachine : TypeStateMachine
{
	private Boolean m_isTransiting; // 0x60
	private BuildingController <controller>k__BackingField; // 0x68

	public IBuildingMode currentMode { get; }
	public BuildingModel model { get; }
	protected BuildingController controller { get; set; }
	public Boolean isTransiting { get; }

	// RVA: 0x377a408 VA: 0x7595d92408
	public IBuildingMode get_currentMode() { }
	// RVA: 0x377cc20 VA: 0x7595d94c20
	public BuildingModel get_model() { }
	// RVA: 0x377cc9c VA: 0x7595d94c9c
	protected BuildingController get_controller() { }
	// RVA: 0x377cca4 VA: 0x7595d94ca4
	private Void set_controller(BuildingController value) { }
	// RVA: 0x377ccac VA: 0x7595d94cac
	public Boolean get_isTransiting() { }
	// RVA: 0x377b1a0 VA: 0x7595d931a0
	public Void .ctor(BuildingController controller) { }
	// RVA: 0x377b1e8 VA: 0x7595d931e8
	public Void RegisterState(IBuildingMode stateNode, Boolean asDefault) { }
	// RVA: 0x VA: 0x0
	public Void SwitchMode(TransitionParam param) { }
	// RVA: 0x VA: 0x0
	public T GetMode() { }
	// RVA: 0x VA: 0x0
	public Void Start() { }
	// RVA: 0x VA: 0x0
	public Void SetDefaultMode() { }
	// RVA: 0x377ccb4 VA: 0x7595d94cb4
	private IEnumerator _DoModeTransition(TransitionParam param, IBuildingMode fromMode, IBuildingMode toMode) { }
}
```