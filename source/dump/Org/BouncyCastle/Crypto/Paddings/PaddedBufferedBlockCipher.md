# PaddedBufferedBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Paddings`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Paddings
public class PaddedBufferedBlockCipher : BufferedBlockCipher
{
	private readonly IBlockCipherPadding padding; // 0x28


	// RVA: 0x651b064 VA: 0x7598b33064
	public Void .ctor(IBlockCipher cipher, IBlockCipherPadding padding) { }
	// RVA: 0x651b17c VA: 0x7598b3317c
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x651b1f8 VA: 0x7598b331f8
	public override Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x651b39c VA: 0x7598b3339c
	public override Int32 GetOutputSize(Int32 length) { }
	// RVA: 0x651b3e8 VA: 0x7598b333e8
	public override Int32 GetUpdateOutputSize(Int32 length) { }
	// RVA: 0x651b420 VA: 0x7598b33420
	public override Int32 ProcessByte(Byte input, Byte[] output, Int32 outOff) { }
	// RVA: 0x651b548 VA: 0x7598b33548
	public override Int32 ProcessBytes(Byte[] input, Int32 inOff, Int32 length, Byte[] output, Int32 outOff) { }
	// RVA: 0x651b7fc VA: 0x7598b337fc
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
}
```