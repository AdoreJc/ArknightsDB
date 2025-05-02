# HMac

**Namespace:** `Org.BouncyCastle.Crypto.Macs`


## Fields

- `IMemoable ipadState`

- `IMemoable opadState`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Macs
public class HMac : IMac
{
	private const Byte IPAD; // 0x0
	private const Byte OPAD; // 0x0
	private readonly IDigest digest; // 0x10
	private readonly Int32 digestSize; // 0x18
	private readonly Int32 blockLength; // 0x1c
	private IMemoable ipadState; // 0x20
	private IMemoable opadState; // 0x28
	private readonly Byte[] inputPad; // 0x30
	private readonly Byte[] outputBuf; // 0x38

	public virtual String AlgorithmName { get; }

	// RVA: 0x65322f8 VA: 0x7598b4a2f8
	public Void .ctor(IDigest digest) { }
	// RVA: 0x6532474 VA: 0x7598b4a474
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6532534 VA: 0x7598b4a534
	public virtual IDigest GetUnderlyingDigest() { }
	// RVA: 0x653253c VA: 0x7598b4a53c
	public virtual Void Init(ICipherParameters parameters) { }
	// RVA: 0x6532ae8 VA: 0x7598b4aae8
	public virtual Int32 GetMacSize() { }
	// RVA: 0x6532af0 VA: 0x7598b4aaf0
	public virtual Void Update(Byte input) { }
	// RVA: 0x6532b9c VA: 0x7598b4ab9c
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x6532c60 VA: 0x7598b4ac60
	public virtual Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6533114 VA: 0x7598b4b114
	public virtual Void Reset() { }
	// RVA: 0x6532a98 VA: 0x7598b4aa98
	private static Void XorPad(Byte[] pad, Int32 len, Byte n) { }
}
```