# CrypticConverter_A

**Namespace:** `Torappu.DB`


## Fields

- `String m_token`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class CrypticConverter_A : CrypticConverter
{
	private const Int32 KEY_LENGTH; // 0x0
	private const Int32 IV_LENGTH; // 0x0
	private String m_token; // 0x20


	// RVA: 0x37177d0 VA: 0x7595d2f7d0
	public Void .ctor() { }
	// RVA: 0x3718af8 VA: 0x7595d30af8
	protected override Byte[] EncodeInternal(Byte[] src) { }
	// RVA: 0x37191f8 VA: 0x7595d311f8
	protected override Void DecodeInternal(Stream src, Stream dst) { }
	// RVA: 0x3719738 VA: 0x7595d31738
	protected virtual Byte[] ReadContentBytes(Stream src) { }
}
```