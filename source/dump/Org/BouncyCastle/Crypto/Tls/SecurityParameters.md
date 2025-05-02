# SecurityParameters

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Properties

- `Byte CompressionAlgorithm`


## Methods

- `Byte get_CompressionAlgorithm()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class SecurityParameters
{
	internal Int32 entity; // 0x10
	internal Int32 cipherSuite; // 0x14
	internal Byte compressionAlgorithm; // 0x18
	internal Int32 prfAlgorithm; // 0x1c
	internal Int32 verifyDataLength; // 0x20
	internal Byte[] masterSecret; // 0x28
	internal Byte[] clientRandom; // 0x30
	internal Byte[] serverRandom; // 0x38
	internal Byte[] sessionHash; // 0x40
	internal Byte[] pskIdentity; // 0x48
	internal Byte[] srpIdentity; // 0x50
	internal Int16 maxFragmentLength; // 0x58
	internal Boolean truncatedHMac; // 0x5a
	internal Boolean encryptThenMac; // 0x5b
	internal Boolean extendedMasterSecret; // 0x5c

	public virtual Int32 Entity { get; }
	public virtual Int32 CipherSuite { get; }
	public Byte CompressionAlgorithm { get; }
	public virtual Int32 PrfAlgorithm { get; }
	public virtual Int32 VerifyDataLength { get; }
	public virtual Byte[] MasterSecret { get; }
	public virtual Byte[] ClientRandom { get; }
	public virtual Byte[] ServerRandom { get; }
	public virtual Byte[] SessionHash { get; }
	public virtual Byte[] PskIdentity { get; }
	public virtual Byte[] SrpIdentity { get; }

	// RVA: 0x64e7714 VA: 0x7598aff714
	internal virtual Void Clear() { }
	// RVA: 0x64e774c VA: 0x7598aff74c
	public virtual Int32 get_Entity() { }
	// RVA: 0x64e7754 VA: 0x7598aff754
	public virtual Int32 get_CipherSuite() { }
	// RVA: 0x64e775c VA: 0x7598aff75c
	public Byte get_CompressionAlgorithm() { }
	// RVA: 0x64e7764 VA: 0x7598aff764
	public virtual Int32 get_PrfAlgorithm() { }
	// RVA: 0x64e776c VA: 0x7598aff76c
	public virtual Int32 get_VerifyDataLength() { }
	// RVA: 0x64e7774 VA: 0x7598aff774
	public virtual Byte[] get_MasterSecret() { }
	// RVA: 0x64e777c VA: 0x7598aff77c
	public virtual Byte[] get_ClientRandom() { }
	// RVA: 0x64e7784 VA: 0x7598aff784
	public virtual Byte[] get_ServerRandom() { }
	// RVA: 0x64e778c VA: 0x7598aff78c
	public virtual Byte[] get_SessionHash() { }
	// RVA: 0x64e7794 VA: 0x7598aff794
	public virtual Byte[] get_PskIdentity() { }
	// RVA: 0x64e779c VA: 0x7598aff79c
	public virtual Byte[] get_SrpIdentity() { }
	// RVA: 0x64e77a4 VA: 0x7598aff7a4
	public Void .ctor() { }
}
```