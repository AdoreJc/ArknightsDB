# TlsMac

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsMac
{
	protected readonly TlsContext context; // 0x10
	protected readonly Byte[] secret; // 0x18
	protected readonly IMac mac; // 0x20
	protected readonly Int32 digestBlockSize; // 0x28
	protected readonly Int32 digestOverhead; // 0x2c
	protected readonly Int32 macLength; // 0x30

	public virtual Byte[] MacSecret { get; }
	public virtual Int32 Size { get; }

	// RVA: 0x64eaf30 VA: 0x7598b02f30
	public Void .ctor(TlsContext context, IDigest digest, Byte[] key, Int32 keyOff, Int32 keyLen) { }
	// RVA: 0x64f8990 VA: 0x7598b10990
	public virtual Byte[] get_MacSecret() { }
	// RVA: 0x64f8998 VA: 0x7598b10998
	public virtual Int32 get_Size() { }
	// RVA: 0x64f89a0 VA: 0x7598b109a0
	public virtual Byte[] CalculateMac(Int64 seqNo, Byte type, Byte[] message, Int32 offset, Int32 length) { }
	// RVA: 0x64f8c9c VA: 0x7598b10c9c
	public virtual Byte[] CalculateMacConstantTime(Int64 seqNo, Byte type, Byte[] message, Int32 offset, Int32 length, Int32 fullLength, Byte[] dummyData) { }
	// RVA: 0x64f8f24 VA: 0x7598b10f24
	protected virtual Int32 GetDigestBlockCount(Int32 inputLength) { }
	// RVA: 0x64f8f34 VA: 0x7598b10f34
	protected virtual Byte[] Truncate(Byte[] bs) { }
}
```