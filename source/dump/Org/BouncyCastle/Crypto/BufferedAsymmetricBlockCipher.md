# BufferedAsymmetricBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto`


## Fields

- `Int32 bufOff`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto
public class BufferedAsymmetricBlockCipher : BufferedCipherBase
{
	private readonly IAsymmetricBlockCipher cipher; // 0x10
	private Byte[] buffer; // 0x18
	private Int32 bufOff; // 0x20

	public override String AlgorithmName { get; }

	// RVA: 0x64d3934 VA: 0x7598aeb934
	public Void .ctor(IAsymmetricBlockCipher cipher) { }
	// RVA: 0x64d39a8 VA: 0x7598aeb9a8
	internal Int32 GetBufferPosition() { }
	// RVA: 0x64d39b0 VA: 0x7598aeb9b0
	public override String get_AlgorithmName() { }
	// RVA: 0x64d3a50 VA: 0x7598aeba50
	public override Int32 GetBlockSize() { }
	// RVA: 0x64d3af4 VA: 0x7598aebaf4
	public override Int32 GetOutputSize(Int32 length) { }
	// RVA: 0x64d3b98 VA: 0x7598aebb98
	public override Int32 GetUpdateOutputSize(Int32 length) { }
	// RVA: 0x64d3ba0 VA: 0x7598aebba0
	public override Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x64d3d18 VA: 0x7598aebd18
	public override Byte[] ProcessByte(Byte input) { }
	// RVA: 0x64d3dac VA: 0x7598aebdac
	public override Byte[] ProcessBytes(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x64d3e9c VA: 0x7598aebe9c
	public override Byte[] DoFinal() { }
	// RVA: 0x64d3fb8 VA: 0x7598aebfb8
	public override Byte[] DoFinal(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x64d3fe8 VA: 0x7598aebfe8
	public override Void Reset() { }
}
```