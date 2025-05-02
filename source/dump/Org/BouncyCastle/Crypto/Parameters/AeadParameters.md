# AeadParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class AeadParameters : ICipherParameters
{
	private readonly Byte[] associatedText; // 0x10
	private readonly Byte[] nonce; // 0x18
	private readonly KeyParameter key; // 0x20
	private readonly Int32 macSize; // 0x28

	public virtual KeyParameter Key { get; }
	public virtual Int32 MacSize { get; }

	// RVA: 0x65145e0 VA: 0x7598b2c5e0
	public Void .ctor(KeyParameter key, Int32 macSize, Byte[] nonce) { }
	// RVA: 0x65145e8 VA: 0x7598b2c5e8
	public Void .ctor(KeyParameter key, Int32 macSize, Byte[] nonce, Byte[] associatedText) { }
	// RVA: 0x6514650 VA: 0x7598b2c650
	public virtual KeyParameter get_Key() { }
	// RVA: 0x6514658 VA: 0x7598b2c658
	public virtual Int32 get_MacSize() { }
	// RVA: 0x6514660 VA: 0x7598b2c660
	public virtual Byte[] GetAssociatedText() { }
	// RVA: 0x6514668 VA: 0x7598b2c668
	public virtual Byte[] GetNonce() { }
}
```