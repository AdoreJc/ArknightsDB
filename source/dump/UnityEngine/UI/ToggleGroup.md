# ToggleGroup

**Namespace:** `UnityEngine.UI`


## Fields

- `Boolean m_AllowSwitchOff`


## Properties

- `Boolean allowSwitchOff`


## Methods

- `Boolean get_allowSwitchOff()`

- `Void set_allowSwitchOff(Boolean)`

- `Void ValidateToggleIsInGroup(Toggle)`

- `Void NotifyToggleOn(Toggle, Boolean)`

- `Void UnregisterToggle(Toggle)`

- `Void RegisterToggle(Toggle)`

- `Void EnsureValidState()`

- `Boolean AnyTogglesOn()`

- `Toggle GetFirstActiveToggle()`

- `Void SetAllTogglesOff(Boolean)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class ToggleGroup : UIBehaviour
{
	private Boolean m_AllowSwitchOff; // 0x18
	protected List`1 m_Toggles; // 0x20

	public Boolean allowSwitchOff { get; set; }

	// RVA: 0x6a6c0f0 VA: 0x75990840f0
	public Boolean get_allowSwitchOff() { }
	// RVA: 0x6a6c0f8 VA: 0x75990840f8
	public Void set_allowSwitchOff(Boolean value) { }
	// RVA: 0x6a6c104 VA: 0x7599084104
	protected Void .ctor() { }
	// RVA: 0x6a6c18c VA: 0x759908418c
	protected override Void Start() { }
	// RVA: 0x6a6c1a8 VA: 0x75990841a8
	protected override Void OnEnable() { }
	// RVA: 0x6a6c1c4 VA: 0x75990841c4
	private Void ValidateToggleIsInGroup(Toggle toggle) { }
	// RVA: 0x6a6bdf4 VA: 0x7599083df4
	public Void NotifyToggleOn(Toggle toggle, Boolean sendCallback) { }
	// RVA: 0x6a6bc7c VA: 0x7599083c7c
	public Void UnregisterToggle(Toggle toggle) { }
	// RVA: 0x6a6bd0c VA: 0x7599083d0c
	public Void RegisterToggle(Toggle toggle) { }
	// RVA: 0x6a6b5ac VA: 0x75990835ac
	public Void EnsureValidState() { }
	// RVA: 0x6a6bf20 VA: 0x7599083f20
	public Boolean AnyTogglesOn() { }
	// RVA: 0x6a6c31c VA: 0x759908431c
	public IEnumerable`1 ActiveToggles() { }
	// RVA: 0x6a6c420 VA: 0x7599084420
	public Toggle GetFirstActiveToggle() { }
	// RVA: 0x6a6c4a8 VA: 0x75990844a8
	public Void SetAllTogglesOff(Boolean sendCallback) { }
}
```