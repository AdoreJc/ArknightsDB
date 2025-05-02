# DigitallySigned

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class DigitallySigned
{
	protected readonly SignatureAndHashAlgorithm mAlgorithm; // 0x10
	protected readonly Byte[] mSignature; // 0x18

	public virtual SignatureAndHashAlgorithm Algorithm { get; }
	public virtual Byte[] Signature { get; }

	// RVA: 0x64e4c84 VA: 0x7598afcc84
	public Void .ctor(SignatureAndHashAlgorithm algorithm, Byte[] signature) { }
	// RVA: 0x64e4d18 VA: 0x7598afcd18
	public virtual SignatureAndHashAlgorithm get_Algorithm() { }
	// RVA: 0x64e4d20 VA: 0x7598afcd20
	public virtual Byte[] get_Signature() { }
	// RVA: 0x64e4d28 VA: 0x7598afcd28
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64e4da4 VA: 0x7598afcda4
	public static DigitallySigned Parse(TlsContext context, Stream input) { }
}
```