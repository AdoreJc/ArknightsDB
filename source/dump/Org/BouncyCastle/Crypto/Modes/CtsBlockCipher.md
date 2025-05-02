# CtsBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class CtsBlockCipher : BufferedBlockCipher
{
	private readonly Int32 blockSize; // 0x28


	// RVA: 0x65233d4 VA: 0x7598b3b3d4
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x65235b0 VA: 0x7598b3b5b0
	public override Int32 GetUpdateOutputSize(Int32 length) { }
	// RVA: 0x65235e8 VA: 0x7598b3b5e8
	public override Int32 GetOutputSize(Int32 length) { }
	// RVA: 0x65235f4 VA: 0x7598b3b5f4
	public override Int32 ProcessByte(Byte input, Byte[] output, Int32 outOff) { }
	// RVA: 0x6523740 VA: 0x7598b3b740
	public override Int32 ProcessBytes(Byte[] input, Int32 inOff, Int32 length, Byte[] output, Int32 outOff) { }
	// RVA: 0x6523a80 VA: 0x7598b3ba80
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
}
```