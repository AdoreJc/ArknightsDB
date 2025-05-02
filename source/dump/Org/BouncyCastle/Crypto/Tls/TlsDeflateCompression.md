# TlsDeflateCompression

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsDeflateCompression : TlsCompression
{
	public const Int32 LEVEL_NONE; // 0x0
	public const Int32 LEVEL_FASTEST; // 0x0
	public const Int32 LEVEL_SMALLEST; // 0x0
	public const Int32 LEVEL_DEFAULT; // 0x0
	protected readonly ZStream zIn; // 0x10
	protected readonly ZStream zOut; // 0x18


	// RVA: 0x64effb4 VA: 0x7598b07fb4
	public Void .ctor() { }
	// RVA: 0x64effbc VA: 0x7598b07fbc
	public Void .ctor(Int32 level) { }
	// RVA: 0x64f008c VA: 0x7598b0808c
	public virtual Stream Compress(Stream output) { }
	// RVA: 0x64f0160 VA: 0x7598b08160
	public virtual Stream Decompress(Stream output) { }
}
```