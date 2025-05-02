# AuthenticodeBase

**Namespace:** `Mono.Security.Authenticode`


## Fields

- `Stream fs`

- `Int32 blockNo`

- `Int32 blockLength`

- `Int32 peOffset`

- `Int32 dirSecurityOffset`

- `Int32 dirSecuritySize`

- `Int32 coffSymbolTableOffset`

- `Boolean pe64`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Authenticode
public class AuthenticodeBase
{
	private Byte[] fileblock; // 0x10
	private Stream fs; // 0x18
	private Int32 blockNo; // 0x20
	private Int32 blockLength; // 0x24
	private Int32 peOffset; // 0x28
	private Int32 dirSecurityOffset; // 0x2c
	private Int32 dirSecuritySize; // 0x30
	private Int32 coffSymbolTableOffset; // 0x34
	private Boolean pe64; // 0x38

	internal Int32 PEOffset { get; }

	// RVA: 0x5ef06a0 VA: 0x75985086a0
	public Void .ctor() { }
	// RVA: 0x5ef0704 VA: 0x7598508704
	internal Int32 get_PEOffset() { }
	// RVA: 0x5ef0804 VA: 0x7598508804
	internal Void Open(String filename) { }
	// RVA: 0x5ef08e0 VA: 0x75985088e0
	internal Void Open(Byte[] rawdata) { }
	// RVA: 0x5ef08a4 VA: 0x75985088a4
	internal Void Close() { }
	// RVA: 0x5ef072c VA: 0x759850872c
	internal Void ReadFirstBlock() { }
	// RVA: 0x5ef0978 VA: 0x7598508978
	internal Int32 ProcessFirstBlock() { }
	// RVA: 0x5ef0bb8 VA: 0x7598508bb8
	internal Byte[] GetSecurityEntry() { }
	// RVA: 0x5ef0c88 VA: 0x7598508c88
	internal Byte[] GetHash(HashAlgorithm hash) { }
}
```