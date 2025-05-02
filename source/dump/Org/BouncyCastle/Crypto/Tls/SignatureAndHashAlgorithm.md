# SignatureAndHashAlgorithm

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class SignatureAndHashAlgorithm
{
	protected readonly Byte mHash; // 0x10
	protected readonly Byte mSignature; // 0x11

	public virtual Byte Hash { get; }
	public virtual Byte Signature { get; }

	// RVA: 0x64e92b4 VA: 0x7598b012b4
	public Void .ctor(Byte hash, Byte signature) { }
	// RVA: 0x64e9418 VA: 0x7598b01418
	public virtual Byte get_Hash() { }
	// RVA: 0x64e9420 VA: 0x7598b01420
	public virtual Byte get_Signature() { }
	// RVA: 0x64e9428 VA: 0x7598b01428
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64e94f8 VA: 0x7598b014f8
	public override Int32 GetHashCode() { }
	// RVA: 0x64e953c VA: 0x7598b0153c
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64e4e7c VA: 0x7598afce7c
	public static SignatureAndHashAlgorithm Parse(Stream input) { }
}
```