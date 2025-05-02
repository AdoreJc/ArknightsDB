# HeaderAuthenticator

**Namespace:** `BestHTTP.SignalR.Authentication`


## Fields

- `String <User>k__BackingField`

- `String <Roles>k__BackingField`

- `OnAuthenticationSuccededDelegate OnAuthenticationSucceded`

- `OnAuthenticationFailedDelegate OnAuthenticationFailed`


## Properties

- `String User`

- `String Roles`

- `Boolean IsPreAuthRequired`


## Methods

- `String get_User()`

- `Void set_User(String)`

- `String get_Roles()`

- `Void set_Roles(String)`

- `Boolean get_IsPreAuthRequired()`

- `Void add_OnAuthenticationSucceded(OnAuthenticationSuccededDelegate)`

- `Void remove_OnAuthenticationSucceded(OnAuthenticationSuccededDelegate)`

- `Void add_OnAuthenticationFailed(OnAuthenticationFailedDelegate)`

- `Void remove_OnAuthenticationFailed(OnAuthenticationFailedDelegate)`

- `Void StartAuthentication()`

- `Void PrepareRequest(HTTPRequest, RequestTypes)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.SignalR.Authentication
internal class HeaderAuthenticator : IAuthenticationProvider
{
	private String <User>k__BackingField; // 0x10
	private String <Roles>k__BackingField; // 0x18
	private OnAuthenticationSuccededDelegate OnAuthenticationSucceded; // 0x20
	private OnAuthenticationFailedDelegate OnAuthenticationFailed; // 0x28

	public String User { get; set; }
	public String Roles { get; set; }
	public Boolean IsPreAuthRequired { get; }

	// RVA: 0x665f850 VA: 0x7598c77850
	public String get_User() { }
	// RVA: 0x665f858 VA: 0x7598c77858
	private Void set_User(String value) { }
	// RVA: 0x665f860 VA: 0x7598c77860
	public String get_Roles() { }
	// RVA: 0x665f868 VA: 0x7598c77868
	private Void set_Roles(String value) { }
	// RVA: 0x665f870 VA: 0x7598c77870
	public Boolean get_IsPreAuthRequired() { }
	// RVA: 0x665f878 VA: 0x7598c77878
	public Void add_OnAuthenticationSucceded(OnAuthenticationSuccededDelegate value) { }
	// RVA: 0x665f914 VA: 0x7598c77914
	public Void remove_OnAuthenticationSucceded(OnAuthenticationSuccededDelegate value) { }
	// RVA: 0x665f9b0 VA: 0x7598c779b0
	public Void add_OnAuthenticationFailed(OnAuthenticationFailedDelegate value) { }
	// RVA: 0x665fa4c VA: 0x7598c77a4c
	public Void remove_OnAuthenticationFailed(OnAuthenticationFailedDelegate value) { }
	// RVA: 0x665fae8 VA: 0x7598c77ae8
	public Void .ctor(String user, String roles) { }
	// RVA: 0x665fb2c VA: 0x7598c77b2c
	public Void StartAuthentication() { }
	// RVA: 0x665fb30 VA: 0x7598c77b30
	public Void PrepareRequest(HTTPRequest request, RequestTypes type) { }
}
```