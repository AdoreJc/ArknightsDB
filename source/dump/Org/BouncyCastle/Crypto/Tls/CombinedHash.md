# CombinedHash

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `TlsContext mContext`

- `IDigest mMd5`

- `IDigest mSha1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
internal class CombinedHash : TlsHandshakeHash, IDigest
{
	protected TlsContext mContext; // 0x10
	protected IDigest mMd5; // 0x18
	protected IDigest mSha1; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x64defbc VA: 0x7598af6fbc
	internal Void .ctor() { }
	// RVA: 0x64df04c VA: 0x7598af704c
	internal Void .ctor(CombinedHash t) { }
	// RVA: 0x64df104 VA: 0x7598af7104
	public virtual Void Init(TlsContext context) { }
	// RVA: 0x64df10c VA: 0x7598af710c
	public virtual TlsHandshakeHash NotifyPrfDetermined() { }
	// RVA: 0x64df110 VA: 0x7598af7110
	public virtual Void TrackHashAlgorithm(Byte hashAlgorithm) { }
	// RVA: 0x64df160 VA: 0x7598af7160
	public virtual Void SealHashAlgorithms() { }
	// RVA: 0x64df164 VA: 0x7598af7164
	public virtual TlsHandshakeHash StopTracking() { }
	// RVA: 0x64df1c4 VA: 0x7598af71c4
	public virtual IDigest ForkPrfHash() { }
	// RVA: 0x64df224 VA: 0x7598af7224
	public virtual Byte[] GetFinalHash(Byte hashAlgorithm) { }
	// RVA: 0x64df274 VA: 0x7598af7274
	public virtual String get_AlgorithmName() { }
	// RVA: 0x64df3a0 VA: 0x7598af73a0
	public virtual Int32 GetByteLength() { }
	// RVA: 0x64df4e8 VA: 0x7598af74e8
	public virtual Int32 GetDigestSize() { }
	// RVA: 0x64df5fc VA: 0x7598af75fc
	public virtual Void Update(Byte input) { }
	// RVA: 0x64df718 VA: 0x7598af7718
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x64df854 VA: 0x7598af7854
	public virtual Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x64dfa40 VA: 0x7598af7a40
	public virtual Void Reset() { }
	// RVA: 0x64dfb48 VA: 0x7598af7b48
	protected virtual Void Ssl3Complete(IDigest d, Byte[] ipad, Byte[] opad, Int32 padLength) { }
}
```