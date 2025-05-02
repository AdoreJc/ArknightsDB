# DigestClient

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
internal class DigestClient : IAuthenticationModule
{
	private static readonly Hashtable cache; // 0x0

	private static Hashtable Cache { get; }
	public String AuthenticationType { get; }

	// RVA: 0x6324b88 VA: 0x759893cb88
	private static Hashtable get_Cache() { }
	// RVA: 0x6324cf0 VA: 0x759893ccf0
	private static Void CheckExpired(Int32 count) { }
	// RVA: 0x6325564 VA: 0x759893d564
	public Authorization Authenticate(String challenge, WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x632580c VA: 0x759893d80c
	public Authorization PreAuthenticate(WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x63259a0 VA: 0x759893d9a0
	public String get_AuthenticationType() { }
	// RVA: 0x63259e0 VA: 0x759893d9e0
	public Void .ctor() { }
	// RVA: 0x63259e8 VA: 0x759893d9e8
	private static Void .cctor() { }
}
```