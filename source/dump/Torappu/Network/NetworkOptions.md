# NetworkOptions

**Namespace:** `Torappu.Network`


## Fields

- `ServerType serverType`

- `Configuration DEV_SERVER`

- `Configuration STORYTEST_SERVER`

- `Configuration STAGING_SERVER`

- `Configuration BUSINESS_SERVER`

- `Configuration PRODUCTION_SERVER`

- `Configuration DATA_DESIGN`

- `Configuration MOCK_SERVER`


## Properties

- `Configuration configuration`


## Methods

- `String GetActiveRouterUrl()`

- `Configuration get_configuration()`

- `Configuration GetConfigByType(ServerType)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public class NetworkOptions : SingletonScriptableObject`1
{
	public ServerType serverType; // 0x18
	public List`1 routers; // 0x20
	public Configuration DEV_SERVER; // 0x28
	public Configuration STORYTEST_SERVER; // 0x90
	public Configuration STAGING_SERVER; // 0xf8
	public Configuration BUSINESS_SERVER; // 0x160
	public Configuration PRODUCTION_SERVER; // 0x1c8
	public Configuration DATA_DESIGN; // 0x230
	public Configuration MOCK_SERVER; // 0x298

	public Configuration configuration { get; }

	// RVA: 0x67b4628 VA: 0x7598dcc628
	public String GetActiveRouterUrl() { }
	// RVA: 0x67ade18 VA: 0x7598dc5e18
	public Configuration get_configuration() { }
	// RVA: 0x67b4734 VA: 0x7598dcc734
	public Configuration GetConfigByType(ServerType type) { }
	// RVA: 0x67b4830 VA: 0x7598dcc830
	public Void .ctor() { }
}
```