# MacOsNetworkInterfaceAPI

**Namespace:** `System.Net.NetworkInformation`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
internal class MacOsNetworkInterfaceAPI : UnixNetworkInterfaceAPI
{
	protected readonly Int32 AF_INET6; // 0x10


	// RVA: 0x634ac30 VA: 0x7598962c30
	public Void .ctor() { }
	// RVA: 0x6348f90 VA: 0x7598960f90
	protected Void .ctor(Int32 AF_INET6) { }
	// RVA: 0x634ac50 VA: 0x7598962c50
	public override NetworkInterface[] GetAllNetworkInterfaces() { }
}
```