# BufferedAeadBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto
public class BufferedAeadBlockCipher : BufferedCipherBase
{
	private readonly IAeadBlockCipher cipher; // 0x10

	public override String AlgorithmName { get; }

	// RVA: 0x64d2d20 VA: 0x7598aead20
	public Void .ctor(IAeadBlockCipher cipher) { }
	// RVA: 0x64d2dec VA: 0x7598aeadec
	public override String get_AlgorithmName() { }
	// RVA: 0x64d2e8c VA: 0x7598aeae8c
	public override Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x64d2f90 VA: 0x7598aeaf90
	public override Int32 GetBlockSize() { }
	// RVA: 0x64d3034 VA: 0x7598aeb034
	public override Int32 GetUpdateOutputSize(Int32 length) { }
	// RVA: 0x64d30e0 VA: 0x7598aeb0e0
	public override Int32 GetOutputSize(Int32 length) { }
	// RVA: 0x64d318c VA: 0x7598aeb18c
	public override Int32 ProcessByte(Byte input, Byte[] output, Int32 outOff) { }
	// RVA: 0x64d3250 VA: 0x7598aeb250
	public override Byte[] ProcessByte(Byte input) { }
	// RVA: 0x64d3340 VA: 0x7598aeb340
	public override Byte[] ProcessBytes(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x64d34a8 VA: 0x7598aeb4a8
	public override Int32 ProcessBytes(Byte[] input, Int32 inOff, Int32 length, Byte[] output, Int32 outOff) { }
	// RVA: 0x64d3584 VA: 0x7598aeb584
	public override Byte[] DoFinal() { }
	// RVA: 0x64d3658 VA: 0x7598aeb658
	public override Byte[] DoFinal(Byte[] input, Int32 inOff, Int32 inLen) { }
	// RVA: 0x64d37d4 VA: 0x7598aeb7d4
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x64d3890 VA: 0x7598aeb890
	public override Void Reset() { }
}
```