# NtlmClient

**Namespace:** `System.Net`


## Fields

- `IAuthenticationModule authObject`


## Properties

- `String AuthenticationType`


## Methods

- `Authorization Authenticate(String, WebRequest, ICredentials)`

- `Authorization PreAuthenticate(WebRequest, ICredentials)`

- `String get_AuthenticationType()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class NtlmClient : IAuthenticationModule
{
	private IAuthenticationModule authObject; // 0x10

	public String AuthenticationType { get; }

	// RVA: 0x6330790 VA: 0x7598948790
	public Void .ctor() { }
	// RVA: 0x6330804 VA: 0x7598948804
	public Authorization Authenticate(String challenge, WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x63308d4 VA: 0x75989488d4
	public Authorization PreAuthenticate(WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x63308dc VA: 0x75989488dc
	public String get_AuthenticationType() { }
}
```