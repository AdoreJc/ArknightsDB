# LinuxUnicastIPAddressInformation

**Namespace:** `System.Net.NetworkInformation`


## Fields

- `IPAddress address`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
internal class LinuxUnicastIPAddressInformation : UnicastIPAddressInformation
{
	private IPAddress address; // 0x10

	public override IPAddress Address { get; }

	// RVA: 0x634a95c VA: 0x759896295c
	public Void .ctor(IPAddress address) { }
	// RVA: 0x634a98c VA: 0x759896298c
	public override IPAddress get_Address() { }
}
```