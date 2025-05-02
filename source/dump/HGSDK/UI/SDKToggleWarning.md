# SDKToggleWarning

**Namespace:** `HGSDK.UI`


## Fields

- `Toggle _toggle`

- `Boolean _showOnStart`


## Properties

- `Boolean isShown`

- `Boolean isValidatedOK`


## Methods

- `Boolean get_isShown()`

- `Void set_isShown(Boolean)`

- `Boolean get_isValidatedOK()`

- `Void RegisterOnValidation(Func`2)`

- `Boolean Validate(Boolean)`

- `Void Start()`

- `Void _OnValidate(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKToggleWarning : MonoBehaviour, IWarningHint
{
	private Toggle _toggle; // 0x18
	private Boolean _showOnStart; // 0x20
	private Func`2 m_onValidation; // 0x28

	public Boolean isShown { get; set; }
	public Boolean isValidatedOK { get; }

	// RVA: 0x37532d4 VA: 0x7595d6b2d4
	public Boolean get_isShown() { }
	// RVA: 0x37532f4 VA: 0x7595d6b2f4
	private Void set_isShown(Boolean value) { }
	// RVA: 0x3753314 VA: 0x7595d6b314
	public Boolean get_isValidatedOK() { }
	// RVA: 0x375332c VA: 0x7595d6b32c
	public Void RegisterOnValidation(Func`2 onValidation) { }
	// RVA: 0x3753334 VA: 0x7595d6b334
	public Boolean Validate(Boolean forceShowIfNotPass) { }
	// RVA: 0x37533bc VA: 0x7595d6b3bc
	private Void Start() { }
	// RVA: 0x3753368 VA: 0x7595d6b368
	private Void _OnValidate(Boolean isOn) { }
	// RVA: 0x375349c VA: 0x7595d6b49c
	public Void .ctor() { }
}
```