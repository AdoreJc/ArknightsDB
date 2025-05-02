# SicBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class SicBlockCipher : IBlockCipher
{
	private readonly IBlockCipher cipher; // 0x10
	private readonly Int32 blockSize; // 0x18
	private readonly Byte[] counter; // 0x20
	private readonly Byte[] counterOut; // 0x28
	private Byte[] IV; // 0x30

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x6521f54 VA: 0x7598b39f54
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x652b6d4 VA: 0x7598b436d4
	public virtual IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x652b6dc VA: 0x7598b436dc
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x652b998 VA: 0x7598b43998
	public virtual String get_AlgorithmName() { }
	// RVA: 0x652ba58 VA: 0x7598b43a58
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x652ba60 VA: 0x7598b43a60
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x652bb04 VA: 0x7598b43b04
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x652bcc0 VA: 0x7598b43cc0
	public virtual Void Reset() { }
}
```