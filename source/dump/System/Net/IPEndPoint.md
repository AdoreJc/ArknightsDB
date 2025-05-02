# IPEndPoint

**Namespace:** `System.Net`


## Fields

- `IPAddress _address`

- `Int32 _port`


## Properties

- `IPAddress Address`

- `Int32 Port`


## Methods

- `IPAddress get_Address()`

- `Int32 get_Port()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class IPEndPoint : EndPoint
{
	public const Int32 MinPort; // 0x0
	public const Int32 MaxPort; // 0x0
	private IPAddress _address; // 0x10
	private Int32 _port; // 0x18
	internal const Int32 AnyPort; // 0x0
	internal static IPEndPoint Any; // 0x0
	internal static IPEndPoint IPv6Any; // 0x8

	public override AddressFamily AddressFamily { get; }
	public IPAddress Address { get; }
	public Int32 Port { get; }

	// RVA: 0x6418b3c VA: 0x7598a30b3c
	public override AddressFamily get_AddressFamily() { }
	// RVA: 0x6418b68 VA: 0x7598a30b68
	public Void .ctor(IPAddress address, Int32 port) { }
	// RVA: 0x6418c30 VA: 0x7598a30c30
	public IPAddress get_Address() { }
	// RVA: 0x6418c38 VA: 0x7598a30c38
	public Int32 get_Port() { }
	// RVA: 0x6418c40 VA: 0x7598a30c40
	public override String ToString() { }
	// RVA: 0x6418d00 VA: 0x7598a30d00
	public override SocketAddress Serialize() { }
	// RVA: 0x6418d70 VA: 0x7598a30d70
	public override EndPoint Create(SocketAddress socketAddress) { }
	// RVA: 0x6418f64 VA: 0x7598a30f64
	public override Boolean Equals(Object comparand) { }
	// RVA: 0x6419018 VA: 0x7598a31018
	public override Int32 GetHashCode() { }
	// RVA: 0x6419048 VA: 0x7598a31048
	private static Void .cctor() { }
}
```