# SDKInputWarning

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _input`

- `Boolean _doNotShowWhenEmpty`

- `Boolean m_setUpByOutside`


## Properties

- `Boolean isShown`

- `Boolean isValidatedOK`


## Methods

- `Boolean get_isShown()`

- `Void set_isShown(Boolean)`

- `Boolean get_isValidatedOK()`

- `Void RegisterOnValidation(Func`2)`

- `Boolean Validate(Boolean)`

- `Void SetWarningByResult()`

- `Void Start()`

- `Void _OnValidate(String)`

- `Void _OnValidate(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKInputWarning : MonoBehaviour, IWarningHint
{
	private InputField _input; // 0x18
	private Boolean _doNotShowWhenEmpty; // 0x20
	private Func`2 m_onValidation; // 0x28
	private Boolean m_setUpByOutside; // 0x30

	public Boolean isShown { get; set; }
	public Boolean isValidatedOK { get; }

	// RVA: 0x3751fc0 VA: 0x7595d69fc0
	public Boolean get_isShown() { }
	// RVA: 0x3751fe0 VA: 0x7595d69fe0
	private Void set_isShown(Boolean value) { }
	// RVA: 0x3752000 VA: 0x7595d6a000
	public Boolean get_isValidatedOK() { }
	// RVA: 0x3752044 VA: 0x7595d6a044
	public Void RegisterOnValidation(Func`2 onValidation) { }
	// RVA: 0x375204c VA: 0x7595d6a04c
	public Boolean Validate(Boolean forceShowIfNotPass) { }
	// RVA: 0x3752100 VA: 0x7595d6a100
	public Void SetWarningByResult() { }
	// RVA: 0x3752128 VA: 0x7595d6a128
	private Void Start() { }
	// RVA: 0x3752238 VA: 0x7595d6a238
	private Void _OnValidate(String content) { }
	// RVA: 0x375207c VA: 0x7595d6a07c
	private Void _OnValidate(String content, Boolean forceShowIfNotPass) { }
	// RVA: 0x375224c VA: 0x7595d6a24c
	public Void .ctor() { }
}
```