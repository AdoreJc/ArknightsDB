# ChallengeResponse

**Namespace:** `Mono.Security.Protocol.Ntlm`


## Fields

- `Boolean _disposed`


## Properties

- `String Password`


## Methods

- `Void set_Password(String)`

- `Void set_Challenge(Byte[])`

- `Void Dispose()`

- `Void Dispose(Boolean)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Protocol.Ntlm
public class ChallengeResponse : IDisposable
{
	private static Byte[] magic; // 0x0
	private static Byte[] nullEncMagic; // 0x8
	private Boolean _disposed; // 0x10
	private Byte[] _challenge; // 0x18
	private Byte[] _lmpwd; // 0x20
	private Byte[] _ntpwd; // 0x28

	public String Password { set; }
	public Byte[] Challenge { set; }
	public Byte[] LM { get; }
	public Byte[] NT { get; }

	// RVA: 0x5ee586c VA: 0x75984fd86c
	public Void .ctor() { }
	// RVA: 0x5ee58f0 VA: 0x75984fd8f0
	public Void .ctor(String password, Byte[] challenge) { }
	// RVA: 0x5ee5e74 VA: 0x75984fde74
	protected override Void Finalize() { }
	// RVA: 0x5ee5928 VA: 0x75984fd928
	public Void set_Password(String value) { }
	// RVA: 0x5ee5d3c VA: 0x75984fdd3c
	public Void set_Challenge(Byte[] value) { }
	// RVA: 0x5ee60bc VA: 0x75984fe0bc
	public Byte[] get_LM() { }
	// RVA: 0x5ee6408 VA: 0x75984fe408
	public Byte[] get_NT() { }
	// RVA: 0x5ee5f14 VA: 0x75984fdf14
	public Void Dispose() { }
	// RVA: 0x5ee646c VA: 0x75984fe46c
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x5ee6120 VA: 0x75984fe120
	private Byte[] GetResponse(Byte[] pwd) { }
	// RVA: 0x5ee64d8 VA: 0x75984fe4d8
	private Byte[] PrepareDESKey(Byte[] key56bits, Int32 position) { }
	// RVA: 0x5ee5f78 VA: 0x75984fdf78
	private Byte[] PasswordToKey(String password, Int32 position) { }
	// RVA: 0x5ee66d0 VA: 0x75984fe6d0
	private static Void .cctor() { }
}
```