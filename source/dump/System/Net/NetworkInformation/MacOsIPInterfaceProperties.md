# MacOsIPInterfaceProperties

**Namespace:** `System.Net.NetworkInformation`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
internal class MacOsIPInterfaceProperties : UnixIPInterfaceProperties
{

	public override GatewayIPAddressInformationCollection GatewayAddresses { get; }

	// RVA: 0x634a994 VA: 0x7598962994
	public Void .ctor(MacOsNetworkInterface iface, List`1 addresses) { }
	// RVA: 0x634aa00 VA: 0x7598962a00
	private static Boolean ParseRouteInfo_icall(String iface, out String[] gw_addr_list) { }
	// RVA: 0x634aa04 VA: 0x7598962a04
	public override GatewayIPAddressInformationCollection get_GatewayAddresses() { }
}
```