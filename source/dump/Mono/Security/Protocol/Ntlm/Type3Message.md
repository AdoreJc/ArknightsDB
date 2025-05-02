# Type3Message

**Namespace:** `Mono.Security.Protocol.Ntlm`


## Fields

- `NtlmAuthLevel _level`

- `String _host`

- `String _domain`

- `String _username`

- `String _password`

- `Type2Message _type2`


## Properties

- `String Domain`

- `String Password`

- `String Username`


## Methods

- `Void set_Domain(String)`

- `Void set_Password(String)`

- `Void set_Username(String)`

- `String DecodeString(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Protocol.Ntlm
public class Type3Message : MessageBase
{
	private NtlmAuthLevel _level; // 0x18
	private Byte[] _challenge; // 0x20
	private String _host; // 0x28
	private String _domain; // 0x30
	private String _username; // 0x38
	private String _password; // 0x40
	private Type2Message _type2; // 0x48
	private Byte[] _lm; // 0x50
	private Byte[] _nt; // 0x58

	public String Domain { set; }
	public String Password { set; }
	public String Username { set; }

	// RVA: 0x5ee8a98 VA: 0x7598500a98
	public Void .ctor(Type2Message type2) { }
	// RVA: 0x5ee8cdc VA: 0x7598500cdc
	protected override Void Finalize() { }
	// RVA: 0x5ee8dbc VA: 0x7598500dbc
	public Void set_Domain(String value) { }
	// RVA: 0x5ee8e44 VA: 0x7598500e44
	public Void set_Password(String value) { }
	// RVA: 0x5ee8e4c VA: 0x7598500e4c
	public Void set_Username(String value) { }
	// RVA: 0x5ee8e54 VA: 0x7598500e54
	protected override Void Decode(Byte[] message) { }
	// RVA: 0x5ee90c4 VA: 0x75985010c4
	private String DecodeString(Byte[] buffer, Int32 offset, Int32 len) { }
	// RVA: 0x5ee911c VA: 0x759850111c
	private Byte[] EncodeString(String text) { }
	// RVA: 0x5ee91ac VA: 0x75985011ac
	public override Byte[] GetBytes() { }
}
```