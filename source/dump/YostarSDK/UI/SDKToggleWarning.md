# SDKToggleWarning

**Namespace:** `YostarSDK.UI`


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
// Namespace : YostarSDK.UI
public class SDKToggleWarning : MonoBehaviour, IWarningHint
{
	private Toggle _toggle; // 0x18
	private Boolean _showOnStart; // 0x20
	private Func`2 m_onValidation; // 0x28

	public Boolean isShown { get; set; }
	public Boolean isValidatedOK { get; }

	// RVA: 0x257f084 VA: 0x7594b97084
	public Boolean get_isShown() { }
	// RVA: 0x257f0a4 VA: 0x7594b970a4
	private Void set_isShown(Boolean value) { }
	// RVA: 0x257f0c4 VA: 0x7594b970c4
	public Boolean get_isValidatedOK() { }
	// RVA: 0x257f0dc VA: 0x7594b970dc
	public Void RegisterOnValidation(Func`2 onValidation) { }
	// RVA: 0x257f0e4 VA: 0x7594b970e4
	public Boolean Validate(Boolean forceShowIfNotPass) { }
	// RVA: 0x257f16c VA: 0x7594b9716c
	private Void Start() { }
	// RVA: 0x257f118 VA: 0x7594b97118
	private Void _OnValidate(Boolean isOn) { }
	// RVA: 0x257f24c VA: 0x7594b9724c
	public Void .ctor() { }
}
```