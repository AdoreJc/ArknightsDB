# ValidationResult

**Namespace:** `Mono.Security.Interface`


## Fields

- `Boolean trusted`

- `Boolean user_denied`

- `Int32 error_code`


## Properties

- `Boolean Trusted`

- `Boolean UserDenied`


## Methods

- `Boolean get_Trusted()`

- `Boolean get_UserDenied()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Interface
public class ValidationResult
{
	private Boolean trusted; // 0x10
	private Boolean user_denied; // 0x11
	private Int32 error_code; // 0x14
	private Nullable`1 policy_errors; // 0x18

	public Boolean Trusted { get; }
	public Boolean UserDenied { get; }

	// RVA: 0x5ee993c VA: 0x759850193c
	public Void .ctor(Boolean trusted, Boolean user_denied, Int32 error_code, Nullable`1 policy_errors) { }
	// RVA: 0x5ee9984 VA: 0x7598501984
	public Boolean get_Trusted() { }
	// RVA: 0x5ee998c VA: 0x759850198c
	public Boolean get_UserDenied() { }
}
```