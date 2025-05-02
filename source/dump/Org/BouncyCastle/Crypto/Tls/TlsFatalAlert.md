# TlsFatalAlert

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsFatalAlert : IOException
{
	private readonly Byte alertDescription; // 0x8c

	public virtual Byte AlertDescription { get; }

	// RVA: 0x64d924c VA: 0x7598af124c
	public Void .ctor(Byte alertDescription) { }
	// RVA: 0x64ea83c VA: 0x7598b0283c
	public Void .ctor(Byte alertDescription, Exception alertCause) { }
	// RVA: 0x64f8988 VA: 0x7598b10988
	public virtual Byte get_AlertDescription() { }
}
```