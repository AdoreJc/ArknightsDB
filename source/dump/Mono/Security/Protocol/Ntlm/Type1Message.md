# Type1Message

**Namespace:** `Mono.Security.Protocol.Ntlm`


## Fields

- `String _host`

- `String _domain`


## Properties

- `String Domain`

- `String Host`


## Methods

- `Void set_Domain(String)`

- `Void set_Host(String)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Protocol.Ntlm
public class Type1Message : MessageBase
{
	private String _host; // 0x18
	private String _domain; // 0x20

	public String Domain { set; }
	public String Host { set; }

	// RVA: 0x5ee81e8 VA: 0x75985001e8
	public Void .ctor() { }
	// RVA: 0x5ee8284 VA: 0x7598500284
	public Void set_Domain(String value) { }
	// RVA: 0x5ee830c VA: 0x759850030c
	public Void set_Host(String value) { }
	// RVA: 0x5ee8394 VA: 0x7598500394
	protected override Void Decode(Byte[] message) { }
	// RVA: 0x5ee849c VA: 0x759850049c
	public override Byte[] GetBytes() { }
}
```