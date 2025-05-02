# RsaCoreEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `RsaKeyParameters key`

- `Boolean forEncryption`

- `Int32 bitSize`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
internal class RsaCoreEngine
{
	private RsaKeyParameters key; // 0x10
	private Boolean forEncryption; // 0x18
	private Int32 bitSize; // 0x1c


	// RVA: 0x6556a24 VA: 0x7598b6ea24
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6556b98 VA: 0x7598b6eb98
	public virtual Int32 GetInputBlockSize() { }
	// RVA: 0x6556bc4 VA: 0x7598b6ebc4
	public virtual Int32 GetOutputBlockSize() { }
	// RVA: 0x6556bf0 VA: 0x7598b6ebf0
	public virtual BigInteger ConvertInput(Byte[] inBuf, Int32 inOff, Int32 inLen) { }
	// RVA: 0x6556cf8 VA: 0x7598b6ecf8
	public virtual Byte[] ConvertOutput(BigInteger result) { }
	// RVA: 0x6556db4 VA: 0x7598b6edb4
	public virtual BigInteger ProcessBlock(BigInteger input) { }
	// RVA: 0x6556a1c VA: 0x7598b6ea1c
	public Void .ctor() { }
}
```