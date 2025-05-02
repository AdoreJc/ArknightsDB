# MonoTlsConnectionInfo

**Namespace:** `Mono.Security.Interface`


## Fields

- `CipherSuiteCode <CipherSuiteCode>k__BackingField`

- `TlsProtocols <ProtocolVersion>k__BackingField`

- `String <PeerDomainName>k__BackingField`


## Properties

- `CipherSuiteCode CipherSuiteCode`

- `TlsProtocols ProtocolVersion`

- `String PeerDomainName`


## Methods

- `CipherSuiteCode get_CipherSuiteCode()`

- `Void set_CipherSuiteCode(CipherSuiteCode)`

- `TlsProtocols get_ProtocolVersion()`

- `Void set_ProtocolVersion(TlsProtocols)`

- `Void set_PeerDomainName(String)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Interface
public class MonoTlsConnectionInfo
{
	private CipherSuiteCode <CipherSuiteCode>k__BackingField; // 0x10
	private TlsProtocols <ProtocolVersion>k__BackingField; // 0x14
	private String <PeerDomainName>k__BackingField; // 0x18

	public CipherSuiteCode CipherSuiteCode { get; set; }
	public TlsProtocols ProtocolVersion { get; set; }
	public String PeerDomainName { set; }

	// RVA: 0x5ee9994 VA: 0x7598501994
	public CipherSuiteCode get_CipherSuiteCode() { }
	// RVA: 0x5ee999c VA: 0x759850199c
	public Void set_CipherSuiteCode(CipherSuiteCode value) { }
	// RVA: 0x5ee99a4 VA: 0x75985019a4
	public TlsProtocols get_ProtocolVersion() { }
	// RVA: 0x5ee99ac VA: 0x75985019ac
	public Void set_ProtocolVersion(TlsProtocols value) { }
	// RVA: 0x5ee99b4 VA: 0x75985019b4
	public Void set_PeerDomainName(String value) { }
	// RVA: 0x5ee99bc VA: 0x75985019bc
	public override String ToString() { }
	// RVA: 0x5ee9a78 VA: 0x7598501a78
	public Void .ctor() { }
}
```