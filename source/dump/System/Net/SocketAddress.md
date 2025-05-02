# SocketAddress

**Namespace:** `System.Net`


## Fields

- `Boolean m_changed`

- `Int32 m_hash`


## Properties

- `AddressFamily Family`

- `Int32 Size`

- `Byte Item`


## Methods

- `AddressFamily get_Family()`

- `Int32 get_Size()`

- `Byte get_Item(Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class SocketAddress
{
	internal Int32 m_Size; // 0x10
	internal Byte[] m_Buffer; // 0x18
	private Boolean m_changed; // 0x20
	private Int32 m_hash; // 0x24

	public AddressFamily Family { get; }
	public Int32 Size { get; }
	public Byte Item { get; }

	// RVA: 0x642aad4 VA: 0x7598a42ad4
	public AddressFamily get_Family() { }
	// RVA: 0x642ab0c VA: 0x7598a42b0c
	public Int32 get_Size() { }
	// RVA: 0x642ab14 VA: 0x7598a42b14
	public Byte get_Item(Int32 offset) { }
	// RVA: 0x642ab90 VA: 0x7598a42b90
	public Void .ctor(AddressFamily family, Int32 size) { }
	// RVA: 0x642acc0 VA: 0x7598a42cc0
	internal Void .ctor(IPAddress ipAddress) { }
	// RVA: 0x642af48 VA: 0x7598a42f48
	internal Void .ctor(IPAddress ipaddress, Int32 port) { }
	// RVA: 0x642afa4 VA: 0x7598a42fa4
	internal IPAddress GetIPAddress() { }
	// RVA: 0x642b198 VA: 0x7598a43198
	internal IPEndPoint GetIPEndPoint() { }
	// RVA: 0x642b240 VA: 0x7598a43240
	public override Boolean Equals(Object comparand) { }
	// RVA: 0x642b32c VA: 0x7598a4332c
	public override Int32 GetHashCode() { }
	// RVA: 0x642b45c VA: 0x7598a4345c
	public override String ToString() { }
}
```