# AixIPInterfaceProperties

**Namespace:** `System.Net.NetworkInformation`


## Fields

- `Int32 _mtu`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
internal class AixIPInterfaceProperties : UnixIPInterfaceProperties
{
	private Int32 _mtu; // 0x20

	public override GatewayIPAddressInformationCollection GatewayAddresses { get; }

	// RVA: 0x63475b4 VA: 0x759895f5b4
	public Void .ctor(AixNetworkInterface iface, List`1 addresses, Int32 mtu) { }
	// RVA: 0x6347678 VA: 0x759895f678
	private static Boolean ParseRouteInfo_icall(String iface, out String[] gw_addr_list) { }
	// RVA: 0x63476bc VA: 0x759895f6bc
	public override GatewayIPAddressInformationCollection get_GatewayAddresses() { }
}
```