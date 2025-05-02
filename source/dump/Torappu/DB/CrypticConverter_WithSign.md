# CrypticConverter_WithSign

**Namespace:** `Torappu.DB`


## Fields

- `String m_signPubKey`


## Methods

- `Boolean _CheckIfEnabled(CodeOpt)`

- `Void _CheckIfSignMatchOrThrow(Stream)`

- `Void _BaseDecodeInternalToDecrypt(Stream, Stream)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class CrypticConverter_WithSign : CrypticConverter_A
{
	private const Int32 SIGN_HEADER_LENGTH; // 0x0
	private String m_signPubKey; // 0x28


	// RVA: 0x37178bc VA: 0x7595d2f8bc
	public Void .ctor() { }
	// RVA: 0x3719d9c VA: 0x7595d31d9c
	protected virtual CodeOpt EnableCodeOpts() { }
	// RVA: 0x3719da4 VA: 0x7595d31da4
	private Boolean _CheckIfEnabled(CodeOpt opt) { }
	// RVA: 0x3719dd8 VA: 0x7595d31dd8
	protected override Byte[] EncodeInternal(Byte[] src) { }
	// RVA: 0x3719e28 VA: 0x7595d31e28
	private Byte[] _BaseEncodeInternalToEncrypt(Byte[] src) { }
	// RVA: 0x3719e74 VA: 0x7595d31e74
	protected override Void DecodeInternal(Stream src, Stream dst) { }
	// RVA: 0x3719fa0 VA: 0x7595d31fa0
	private Void _CheckIfSignMatchOrThrow(Stream src) { }
	// RVA: 0x371a1e8 VA: 0x7595d321e8
	private Void _BaseDecodeInternalToDecrypt(Stream src, Stream dst) { }
	// RVA: 0x371a278 VA: 0x7595d32278
	protected override Byte[] ReadContentBytes(Stream src) { }
}
```