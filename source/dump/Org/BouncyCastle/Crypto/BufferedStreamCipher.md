# BufferedStreamCipher

**Namespace:** `Org.BouncyCastle.Crypto`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto
public class BufferedStreamCipher : BufferedCipherBase
{
	private readonly IStreamCipher cipher; // 0x10

	public override String AlgorithmName { get; }

	// RVA: 0x64d5a38 VA: 0x7598aeda38
	public Void .ctor(IStreamCipher cipher) { }
	// RVA: 0x64d5afc VA: 0x7598aedafc
	public override String get_AlgorithmName() { }
	// RVA: 0x64d5b9c VA: 0x7598aedb9c
	public override Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x64d5ca0 VA: 0x7598aedca0
	public override Int32 GetBlockSize() { }
	// RVA: 0x64d5ca8 VA: 0x7598aedca8
	public override Int32 GetOutputSize(Int32 inputLen) { }
	// RVA: 0x64d5cb0 VA: 0x7598aedcb0
	public override Int32 GetUpdateOutputSize(Int32 inputLen) { }
	// RVA: 0x64d5cb8 VA: 0x7598aedcb8
	public override Byte[] ProcessByte(Byte input) { }
	// RVA: 0x64d5dac VA: 0x7598aeddac
	public override Int32 ProcessByte(Byte input, Byte[] output, Int32 outOff) { }
	// RVA: 0x64d5ee4 VA: 0x7598aedee4
	public override Byte[] ProcessBytes(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x64d5fec VA: 0x7598aedfec
	public override Int32 ProcessBytes(Byte[] input, Int32 inOff, Int32 length, Byte[] output, Int32 outOff) { }
	// RVA: 0x64d60e0 VA: 0x7598aee0e0
	public override Byte[] DoFinal() { }
	// RVA: 0x64d6150 VA: 0x7598aee150
	public override Byte[] DoFinal(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x64d6208 VA: 0x7598aee208
	public override Void Reset() { }
}
```