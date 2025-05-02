# BufferedIesCipher

**Namespace:** `Org.BouncyCastle.Crypto`


## Fields

- `Boolean forEncryption`

- `MemoryStream buffer`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto
public class BufferedIesCipher : BufferedCipherBase
{
	private readonly IesEngine engine; // 0x10
	private Boolean forEncryption; // 0x18
	private MemoryStream buffer; // 0x20

	public override String AlgorithmName { get; }

	// RVA: 0x64d55f4 VA: 0x7598aed5f4
	public Void .ctor(IesEngine engine) { }
	// RVA: 0x64d56f8 VA: 0x7598aed6f8
	public override String get_AlgorithmName() { }
	// RVA: 0x64d5738 VA: 0x7598aed738
	public override Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x64d5784 VA: 0x7598aed784
	public override Int32 GetBlockSize() { }
	// RVA: 0x64d578c VA: 0x7598aed78c
	public override Int32 GetOutputSize(Int32 inputLen) { }
	// RVA: 0x64d582c VA: 0x7598aed82c
	public override Int32 GetUpdateOutputSize(Int32 inputLen) { }
	// RVA: 0x64d5834 VA: 0x7598aed834
	public override Byte[] ProcessByte(Byte input) { }
	// RVA: 0x64d5860 VA: 0x7598aed860
	public override Byte[] ProcessBytes(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x64d5974 VA: 0x7598aed974
	public override Byte[] DoFinal() { }
	// RVA: 0x64d59e0 VA: 0x7598aed9e0
	public override Byte[] DoFinal(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x64d5a10 VA: 0x7598aeda10
	public override Void Reset() { }
}
```