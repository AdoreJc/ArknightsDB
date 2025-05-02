# VisualElementPanelActivator

**Namespace:** `UnityEngine.UIElements`


## Fields

- `IVisualElementPanelActivatable m_Activatable`

- `Boolean <isActive>k__BackingField`

- `Boolean <isDetaching>k__BackingField`


## Properties

- `Boolean isActive`

- `Boolean isDetaching`


## Methods

- `Boolean get_isActive()`

- `Void set_isActive(Boolean)`

- `Boolean get_isDetaching()`

- `Void set_isDetaching(Boolean)`

- `Void SetActive(Boolean)`

- `Void SendActivation()`

- `Void SendDeactivation()`

- `Void OnEnter(AttachToPanelEvent)`

- `Void OnLeave(DetachFromPanelEvent)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualElementPanelActivator
{
	private IVisualElementPanelActivatable m_Activatable; // 0x10
	private Boolean <isActive>k__BackingField; // 0x18
	private Boolean <isDetaching>k__BackingField; // 0x19

	public Boolean isActive { get; set; }
	public Boolean isDetaching { get; set; }

	// RVA: 0x6996558 VA: 0x7598fae558
	public Boolean get_isActive() { }
	// RVA: 0x6996560 VA: 0x7598fae560
	private Void set_isActive(Boolean value) { }
	// RVA: 0x699656c VA: 0x7598fae56c
	public Boolean get_isDetaching() { }
	// RVA: 0x6996574 VA: 0x7598fae574
	private Void set_isDetaching(Boolean value) { }
	// RVA: 0x6996580 VA: 0x7598fae580
	public Void .ctor(IVisualElementPanelActivatable activatable) { }
	// RVA: 0x69965b0 VA: 0x7598fae5b0
	public Void SetActive(Boolean action) { }
	// RVA: 0x69968ec VA: 0x7598fae8ec
	public Void SendActivation() { }
	// RVA: 0x6996a04 VA: 0x7598faea04
	public Void SendDeactivation() { }
	// RVA: 0x6996b1c VA: 0x7598faeb1c
	private Void OnEnter(AttachToPanelEvent evt) { }
	// RVA: 0x6996b2c VA: 0x7598faeb2c
	private Void OnLeave(DetachFromPanelEvent evt) { }
}
```