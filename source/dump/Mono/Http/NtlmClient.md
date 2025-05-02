# NtlmClient

**Namespace:** `Mono.Http`


## Properties

- `String AuthenticationType`


## Methods

- `Authorization Authenticate(String, WebRequest, ICredentials)`

- `Authorization PreAuthenticate(WebRequest, ICredentials)`

- `String get_AuthenticationType()`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono.Http
internal class NtlmClient : IAuthenticationModule
{
	private static readonly ConditionalWeakTable`2 cache; // 0x0

	public String AuthenticationType { get; }

	// RVA: 0x626290c VA: 0x759887a90c
	public Authorization Authenticate(String challenge, WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x6262c9c VA: 0x759887ac9c
	public Authorization PreAuthenticate(WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x6262ca4 VA: 0x759887aca4
	public String get_AuthenticationType() { }
	// RVA: 0x6262ce4 VA: 0x759887ace4
	public Void .ctor() { }
	// RVA: 0x6262cec VA: 0x759887acec
	private static Void .cctor() { }
}
```