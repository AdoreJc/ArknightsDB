# SystemGatewayIPAddressInformation

**Namespace:** `System.Net.NetworkInformation`


## Fields

- `IPAddress address`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
internal class SystemGatewayIPAddressInformation : GatewayIPAddressInformation
{
	private IPAddress address; // 0x10


	// RVA: 0x6346f08 VA: 0x759895ef08
	internal Void .ctor(IPAddress address) { }
	// RVA: 0x6346f38 VA: 0x759895ef38
	internal static GatewayIPAddressInformationCollection ToGatewayIpAddressInformationCollection(IPAddressCollection addresses) { }
}
```