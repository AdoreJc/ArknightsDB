# SDKInputWarning

**Namespace:** `YostarSDK.UI`


## Fields

- `InputField _input`

- `Boolean _doNotShowWhenEmpty`


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

- `Void _OnValidate(String)`

- `Void _OnValidate(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKInputWarning : MonoBehaviour, IWarningHint
{
	private InputField _input; // 0x18
	private Boolean _doNotShowWhenEmpty; // 0x20
	private Func`2 m_onValidation; // 0x28

	public Boolean isShown { get; set; }
	public Boolean isValidatedOK { get; }

	// RVA: 0x257ee5c VA: 0x7594b96e5c
	public Boolean get_isShown() { }
	// RVA: 0x257ee7c VA: 0x7594b96e7c
	private Void set_isShown(Boolean value) { }
	// RVA: 0x257ee9c VA: 0x7594b96e9c
	public Boolean get_isValidatedOK() { }
	// RVA: 0x257eee0 VA: 0x7594b96ee0
	public Void RegisterOnValidation(Func`2 onValidation) { }
	// RVA: 0x257e98c VA: 0x7594b9698c
	public Boolean Validate(Boolean forceShowIfNotPass) { }
	// RVA: 0x257ef5c VA: 0x7594b96f5c
	private Void Start() { }
	// RVA: 0x257f06c VA: 0x7594b9706c
	private Void _OnValidate(String content) { }
	// RVA: 0x257eee8 VA: 0x7594b96ee8
	private Void _OnValidate(String content, Boolean forceShowIfNotPass) { }
	// RVA: 0x257f074 VA: 0x7594b97074
	public Void .ctor() { }
}
```