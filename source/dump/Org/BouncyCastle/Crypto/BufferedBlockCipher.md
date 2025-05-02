# BufferedBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto
public class BufferedBlockCipher : BufferedCipherBase
{
	internal Byte[] buf; // 0x10
	internal Int32 bufOff; // 0x18
	internal Boolean forEncryption; // 0x1c
	internal IBlockCipher cipher; // 0x20

	public override String AlgorithmName { get; }

	// RVA: 0x64d4014 VA: 0x7598aec014
	protected Void .ctor() { }
	// RVA: 0x64d406c VA: 0x7598aec06c
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x64d41dc VA: 0x7598aec1dc
	public override String get_AlgorithmName() { }
	// RVA: 0x64d427c VA: 0x7598aec27c
	public override Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x64d439c VA: 0x7598aec39c
	public override Int32 GetBlockSize() { }
	// RVA: 0x64d4440 VA: 0x7598aec440
	public override Int32 GetUpdateOutputSize(Int32 length) { }
	// RVA: 0x64d446c VA: 0x7598aec46c
	public override Int32 GetOutputSize(Int32 length) { }
	// RVA: 0x64d4478 VA: 0x7598aec478
	public override Int32 ProcessByte(Byte input, Byte[] output, Int32 outOff) { }
	// RVA: 0x64d45f8 VA: 0x7598aec5f8
	public override Byte[] ProcessByte(Byte input) { }
	// RVA: 0x64d46e8 VA: 0x7598aec6e8
	public override Byte[] ProcessBytes(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x64d4850 VA: 0x7598aec850
	public override Int32 ProcessBytes(Byte[] input, Int32 inOff, Int32 length, Byte[] output, Int32 outOff) { }
	// RVA: 0x64d4c10 VA: 0x7598aecc10
	public override Byte[] DoFinal() { }
	// RVA: 0x64d4d30 VA: 0x7598aecd30
	public override Byte[] DoFinal(Byte[] input, Int32 inOff, Int32 inLen) { }
	// RVA: 0x64d4f00 VA: 0x7598aecf00
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x64d51a0 VA: 0x7598aed1a0
	public override Void Reset() { }
}
```