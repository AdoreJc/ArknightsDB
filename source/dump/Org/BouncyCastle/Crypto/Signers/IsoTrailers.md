# IsoTrailers

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class IsoTrailers
{
	public const Int32 TRAILER_IMPLICIT; // 0x0
	public const Int32 TRAILER_RIPEMD160; // 0x0
	public const Int32 TRAILER_RIPEMD128; // 0x0
	public const Int32 TRAILER_SHA1; // 0x0
	public const Int32 TRAILER_SHA256; // 0x0
	public const Int32 TRAILER_SHA512; // 0x0
	public const Int32 TRAILER_SHA384; // 0x0
	public const Int32 TRAILER_WHIRLPOOL; // 0x0
	public const Int32 TRAILER_SHA224; // 0x0
	public const Int32 TRAILER_SHA512_224; // 0x0
	public const Int32 TRAILER_SHA512_256; // 0x0
	private static readonly IDictionary trailerMap; // 0x0


	// RVA: 0x650f7c0 VA: 0x7598b277c0
	private static IDictionary CreateTrailerMap() { }
	// RVA: 0x650ded0 VA: 0x7598b25ed0
	public static Int32 GetTrailer(IDigest digest) { }
	// RVA: 0x650dd7c VA: 0x7598b25d7c
	public static Boolean NoTrailerAvailable(IDigest digest) { }
	// RVA: 0x650fe34 VA: 0x7598b27e34
	public Void .ctor() { }
	// RVA: 0x650fe3c VA: 0x7598b27e3c
	private static Void .cctor() { }
}
```