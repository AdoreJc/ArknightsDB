# Type2Message

**Namespace:** `Mono.Security.Protocol.Ntlm`


## Fields

- `String _targetName`


## Properties

- `String TargetName`


## Methods

- `String get_TargetName()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Protocol.Ntlm
public class Type2Message : MessageBase
{
	private Byte[] _nonce; // 0x18
	private String _targetName; // 0x20
	private Byte[] _targetInfo; // 0x28

	public Byte[] Nonce { get; }
	public String TargetName { get; }
	public Byte[] TargetInfo { get; }

	// RVA: 0x5ee86e8 VA: 0x75985006e8
	public Void .ctor(Byte[] message) { }
	// RVA: 0x5ee8798 VA: 0x7598500798
	protected override Void Finalize() { }
	// RVA: 0x5ee7750 VA: 0x75984ff750
	public Byte[] get_Nonce() { }
	// RVA: 0x5ee8840 VA: 0x7598500840
	public String get_TargetName() { }
	// RVA: 0x5ee76d8 VA: 0x75984ff6d8
	public Byte[] get_TargetInfo() { }
	// RVA: 0x5ee8848 VA: 0x7598500848
	protected override Void Decode(Byte[] message) { }
	// RVA: 0x5ee89e0 VA: 0x75985009e0
	public override Byte[] GetBytes() { }
}
```