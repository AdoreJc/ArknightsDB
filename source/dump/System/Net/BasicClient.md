# BasicClient

**Namespace:** `System.Net`


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
internal class BasicClient : IAuthenticationModule
{

	public String AuthenticationType { get; }

	// RVA: 0x63225d4 VA: 0x759893a5d4
	public Authorization Authenticate(String challenge, WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x6322a88 VA: 0x759893aa88
	private static Byte[] GetBytes(String str) { }
	// RVA: 0x6322680 VA: 0x759893a680
	private static Authorization InternalAuthenticate(WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x6322b30 VA: 0x759893ab30
	public Authorization PreAuthenticate(WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x6322b3c VA: 0x759893ab3c
	public String get_AuthenticationType() { }
	// RVA: 0x6322b7c VA: 0x759893ab7c
	public Void .ctor() { }
}
```