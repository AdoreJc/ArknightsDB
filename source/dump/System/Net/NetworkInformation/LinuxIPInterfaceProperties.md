# LinuxIPInterfaceProperties

**Namespace:** `System.Net.NetworkInformation`


## Methods

- `IPAddressCollection ParseRouteInfo(String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
internal class LinuxIPInterfaceProperties : UnixIPInterfaceProperties
{

	public override GatewayIPAddressInformationCollection GatewayAddresses { get; }

	// RVA: 0x6349064 VA: 0x7598961064
	public Void .ctor(LinuxNetworkInterface iface, List`1 addresses) { }
	// RVA: 0x63490d0 VA: 0x75989610d0
	private IPAddressCollection ParseRouteInfo(String iface) { }
	// RVA: 0x6349558 VA: 0x7598961558
	public override GatewayIPAddressInformationCollection get_GatewayAddresses() { }
}
```