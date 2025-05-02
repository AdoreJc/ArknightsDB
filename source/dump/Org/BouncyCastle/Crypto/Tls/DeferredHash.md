# DeferredHash

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `TlsContext mContext`

- `DigestInputBuffer mBuf`

- `IDictionary mHashes`

- `Int32 mPrfHashAlgorithm`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
internal class DeferredHash : TlsHandshakeHash, IDigest
{
	protected const Int32 BUFFERING_HASH_LIMIT; // 0x0
	protected TlsContext mContext; // 0x10
	private DigestInputBuffer mBuf; // 0x18
	private IDictionary mHashes; // 0x20
	private Int32 mPrfHashAlgorithm; // 0x28

	public virtual String AlgorithmName { get; }

	// RVA: 0x64e2bb4 VA: 0x7598afabb4
	internal Void .ctor() { }
	// RVA: 0x64e2c78 VA: 0x7598afac78
	private Void .ctor(Byte prfHashAlgorithm, IDigest prfHash) { }
	// RVA: 0x64e2dc8 VA: 0x7598afadc8
	public virtual Void Init(TlsContext context) { }
	// RVA: 0x64e2dd0 VA: 0x7598afadd0
	public virtual TlsHandshakeHash NotifyPrfDetermined() { }
	// RVA: 0x64e2fdc VA: 0x7598afafdc
	public virtual Void TrackHashAlgorithm(Byte hashAlgorithm) { }
	// RVA: 0x64e3048 VA: 0x7598afb048
	public virtual Void SealHashAlgorithms() { }
	// RVA: 0x64e3058 VA: 0x7598afb058
	public virtual TlsHandshakeHash StopTracking() { }
	// RVA: 0x64e321c VA: 0x7598afb21c
	public virtual IDigest ForkPrfHash() { }
	// RVA: 0x64e33d0 VA: 0x7598afb3d0
	public virtual Byte[] GetFinalHash(Byte hashAlgorithm) { }
	// RVA: 0x64e367c VA: 0x7598afb67c
	public virtual String get_AlgorithmName() { }
	// RVA: 0x64e36cc VA: 0x7598afb6cc
	public virtual Int32 GetByteLength() { }
	// RVA: 0x64e371c VA: 0x7598afb71c
	public virtual Int32 GetDigestSize() { }
	// RVA: 0x64e376c VA: 0x7598afb76c
	public virtual Void Update(Byte input) { }
	// RVA: 0x64e3bc4 VA: 0x7598afbbc4
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x64e4040 VA: 0x7598afc040
	public virtual Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x64e4090 VA: 0x7598afc090
	public virtual Void Reset() { }
	// RVA: 0x64e44d0 VA: 0x7598afc4d0
	protected virtual Void CheckStopBuffering() { }
	// RVA: 0x64e4944 VA: 0x7598afc944
	protected virtual Void CheckTrackingHash(Byte hashAlgorithm) { }
}
```