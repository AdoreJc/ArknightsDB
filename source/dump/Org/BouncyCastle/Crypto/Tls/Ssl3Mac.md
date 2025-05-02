# Ssl3Mac

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class Ssl3Mac : IMac
{
	private const Byte IPAD_BYTE; // 0x0
	private const Byte OPAD_BYTE; // 0x0
	internal static readonly Byte[] IPAD; // 0x0
	internal static readonly Byte[] OPAD; // 0x8
	private readonly IDigest digest; // 0x10
	private readonly Int32 padLength; // 0x18
	private Byte[] secret; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x64e980c VA: 0x7598b0180c
	public Void .ctor(IDigest digest) { }
	// RVA: 0x64e98e4 VA: 0x7598b018e4
	public virtual String get_AlgorithmName() { }
	// RVA: 0x64e99a4 VA: 0x7598b019a4
	public virtual Void Init(ICipherParameters parameters) { }
	// RVA: 0x64e9a58 VA: 0x7598b01a58
	public virtual Int32 GetMacSize() { }
	// RVA: 0x64e9afc VA: 0x7598b01afc
	public virtual Void Update(Byte input) { }
	// RVA: 0x64e9ba8 VA: 0x7598b01ba8
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x64e9c6c VA: 0x7598b01c6c
	public virtual Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x64e9fe8 VA: 0x7598b01fe8
	public virtual Void Reset() { }
	// RVA: 0x64ea1bc VA: 0x7598b021bc
	private static Byte[] GenPad(Byte b, Int32 count) { }
	// RVA: 0x64ea228 VA: 0x7598b02228
	private static Void .cctor() { }
}
```