# IPAddress

**Namespace:** `System.Net`


## Fields

- `UInt32 _addressOrScopeId`

- `String _toString`

- `Int32 _hashCode`


## Properties

- `Boolean IsIPv4`

- `Boolean IsIPv6`

- `UInt32 PrivateAddress`

- `UInt32 PrivateScopeId`

- `AddressFamily AddressFamily`

- `Int64 ScopeId`

- `Boolean IsIPv6Multicast`


## Methods

- `Boolean get_IsIPv4()`

- `Boolean get_IsIPv6()`

- `UInt32 get_PrivateAddress()`

- `Void set_PrivateAddress(UInt32)`

- `UInt32 get_PrivateScopeId()`

- `Void set_PrivateScopeId(UInt32)`

- `Boolean TryWriteBytes(Span`1, out)`

- `Void WriteIPv6Bytes(Span`1)`

- `Void WriteIPv4Bytes(Span`1)`

- `AddressFamily get_AddressFamily()`

- `Int64 get_ScopeId()`

- `Boolean get_IsIPv6Multicast()`

- `IPAddress MapToIPv6()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class IPAddress
{
	public static readonly IPAddress Any; // 0x0
	public static readonly IPAddress Loopback; // 0x8
	public static readonly IPAddress Broadcast; // 0x10
	public static readonly IPAddress None; // 0x18
	internal const Int64 LoopbackMask; // 0x0
	public static readonly IPAddress IPv6Any; // 0x20
	public static readonly IPAddress IPv6Loopback; // 0x28
	public static readonly IPAddress IPv6None; // 0x30
	private UInt32 _addressOrScopeId; // 0x10
	private readonly UInt16[] _numbers; // 0x18
	private String _toString; // 0x20
	private Int32 _hashCode; // 0x28
	internal const Int32 NumberOfLabels; // 0x0

	private Boolean IsIPv4 { get; }
	private Boolean IsIPv6 { get; }
	private UInt32 PrivateAddress { get; set; }
	private UInt32 PrivateScopeId { get; set; }
	public AddressFamily AddressFamily { get; }
	public Int64 ScopeId { get; }
	public Boolean IsIPv6Multicast { get; }

	// RVA: 0x6416a9c VA: 0x7598a2ea9c
	private Boolean get_IsIPv4() { }
	// RVA: 0x6416aac VA: 0x7598a2eaac
	private Boolean get_IsIPv6() { }
	// RVA: 0x6416abc VA: 0x7598a2eabc
	private UInt32 get_PrivateAddress() { }
	// RVA: 0x6416ac4 VA: 0x7598a2eac4
	private Void set_PrivateAddress(UInt32 value) { }
	// RVA: 0x6416af8 VA: 0x7598a2eaf8
	private UInt32 get_PrivateScopeId() { }
	// RVA: 0x6416b00 VA: 0x7598a2eb00
	private Void set_PrivateScopeId(UInt32 value) { }
	// RVA: 0x6416b34 VA: 0x7598a2eb34
	public Void .ctor(Int64 newAddress) { }
	// RVA: 0x6416bc4 VA: 0x7598a2ebc4
	public Void .ctor(Byte[] address, Int64 scopeid) { }
	// RVA: 0x6416c90 VA: 0x7598a2ec90
	public Void .ctor(ReadOnlySpan`1 address, Int64 scopeid) { }
	// RVA: 0x6416e34 VA: 0x7598a2ee34
	internal Void .ctor(UInt16* numbers, Int32 numbersLength, UInt32 scopeid) { }
	// RVA: 0x6416f08 VA: 0x7598a2ef08
	private Void .ctor(UInt16[] numbers, UInt32 scopeid) { }
	// RVA: 0x6416f58 VA: 0x7598a2ef58
	public Void .ctor(Byte[] address) { }
	// RVA: 0x6416fc4 VA: 0x7598a2efc4
	public Void .ctor(ReadOnlySpan`1 address) { }
	// RVA: 0x6417130 VA: 0x7598a2f130
	public static Boolean TryParse(String ipString, out IPAddress address) { }
	// RVA: 0x64173b8 VA: 0x7598a2f3b8
	public static IPAddress Parse(String ipString) { }
	// RVA: 0x6417454 VA: 0x7598a2f454
	public Boolean TryWriteBytes(Span`1 destination, out Int32 bytesWritten) { }
	// RVA: 0x641756c VA: 0x7598a2f56c
	private Void WriteIPv6Bytes(Span`1 destination) { }
	// RVA: 0x64175f8 VA: 0x7598a2f5f8
	private Void WriteIPv4Bytes(Span`1 destination) { }
	// RVA: 0x6417644 VA: 0x7598a2f644
	public Byte[] GetAddressBytes() { }
	// RVA: 0x6417798 VA: 0x7598a2f798
	public AddressFamily get_AddressFamily() { }
	// RVA: 0x64177b0 VA: 0x7598a2f7b0
	public Int64 get_ScopeId() { }
	// RVA: 0x6417808 VA: 0x7598a2f808
	public override String ToString() { }
	// RVA: 0x641792c VA: 0x7598a2f92c
	public static Int32 HostToNetworkOrder(Int32 host) { }
	// RVA: 0x6417994 VA: 0x7598a2f994
	public static Int32 NetworkToHostOrder(Int32 network) { }
	// RVA: 0x64179e8 VA: 0x7598a2f9e8
	public static Boolean IsLoopback(IPAddress address) { }
	// RVA: 0x6417ab0 VA: 0x7598a2fab0
	public Boolean get_IsIPv6Multicast() { }
	// RVA: 0x6417ae4 VA: 0x7598a2fae4
	internal Boolean Equals(Object comparandObj, Boolean compareScopeId) { }
	// RVA: 0x6417c18 VA: 0x7598a2fc18
	public override Boolean Equals(Object comparand) { }
	// RVA: 0x6417c20 VA: 0x7598a2fc20
	public override Int32 GetHashCode() { }
	// RVA: 0x6418088 VA: 0x7598a30088
	public IPAddress MapToIPv6() { }
	// RVA: 0x6416c40 VA: 0x7598a2ec40
	private static Byte[] ThrowAddressNullException() { }
	// RVA: 0x6418160 VA: 0x7598a30160
	private static Void .cctor() { }
}
```