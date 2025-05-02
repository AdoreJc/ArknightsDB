# X509Certificate

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `X509CertificateImpl impl`

- `String lazyIssuer`

- `String lazySubject`

- `String lazyKeyAlgorithm`

- `DateTime lazyNotBefore`

- `DateTime lazyNotAfter`


## Properties

- `String Issuer`

- `String Subject`


## Methods

- `String get_Issuer()`

- `String get_Subject()`

- `Void Dispose()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography.X509Certificates
public class X509Certificate : IDisposable, IDeserializationCallback, ISerializable
{
	private X509CertificateImpl impl; // 0x10
	private Byte[] lazyCertHash; // 0x18
	private Byte[] lazySerialNumber; // 0x20
	private String lazyIssuer; // 0x28
	private String lazySubject; // 0x30
	private String lazyKeyAlgorithm; // 0x38
	private Byte[] lazyKeyAlgorithmParameters; // 0x40
	private Byte[] lazyPublicKey; // 0x48
	private DateTime lazyNotBefore; // 0x50
	private DateTime lazyNotAfter; // 0x58
	internal const X509KeyStorageFlags KeyStorageFlagsAll; // 0x0

	public String Issuer { get; }
	public String Subject { get; }
	internal X509CertificateImpl Impl { get; }
	internal Boolean IsValid { get; }

	// RVA: 0x5f76978 VA: 0x759858e978
	public virtual Void Reset() { }
	// RVA: 0x5f76b00 VA: 0x759858eb00
	public Void .ctor() { }
	// RVA: 0x5f76b74 VA: 0x759858eb74
	public Void .ctor(Byte[] data) { }
	// RVA: 0x5f76cd4 VA: 0x759858ecd4
	internal Void .ctor(X509CertificateImpl impl) { }
	// RVA: 0x5f76d94 VA: 0x759858ed94
	public Void .ctor(X509Certificate cert) { }
	// RVA: 0x5f76f2c VA: 0x759858ef2c
	public Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f76f70 VA: 0x759858ef70
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f76fb0 VA: 0x759858efb0
	private Void System.Runtime.Serialization.IDeserializationCallback.OnDeserialization(Object sender) { }
	// RVA: 0x5f76ff0 VA: 0x759858eff0
	public String get_Issuer() { }
	// RVA: 0x5f7705c VA: 0x759858f05c
	public String get_Subject() { }
	// RVA: 0x5f770c0 VA: 0x759858f0c0
	public Void Dispose() { }
	// RVA: 0x5f770d0 VA: 0x759858f0d0
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x5f770e4 VA: 0x759858f0e4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x5f77178 VA: 0x759858f178
	public virtual Boolean Equals(X509Certificate other) { }
	// RVA: 0x5f772c4 VA: 0x759858f2c4
	public virtual Byte[] GetCertHash() { }
	// RVA: 0x5f77344 VA: 0x759858f344
	public virtual String GetCertHashString() { }
	// RVA: 0x5f772e8 VA: 0x759858f2e8
	private Byte[] GetRawCertHash() { }
	// RVA: 0x5f77368 VA: 0x759858f368
	public virtual Byte[] GetRawCertData() { }
	// RVA: 0x5f7739c VA: 0x759858f39c
	public override Int32 GetHashCode() { }
	// RVA: 0x5f77414 VA: 0x759858f414
	public virtual String GetKeyAlgorithm() { }
	// RVA: 0x5f7747c VA: 0x759858f47c
	public virtual Byte[] GetKeyAlgorithmParameters() { }
	// RVA: 0x5f774e8 VA: 0x759858f4e8
	public virtual Byte[] GetPublicKey() { }
	// RVA: 0x5f77554 VA: 0x759858f554
	public virtual Byte[] GetSerialNumber() { }
	// RVA: 0x5f775bc VA: 0x759858f5bc
	public virtual String GetSerialNumberString() { }
	// RVA: 0x5f77264 VA: 0x759858f264
	private Byte[] GetRawSerialNumber() { }
	// RVA: 0x5f775e0 VA: 0x759858f5e0
	public override String ToString() { }
	// RVA: 0x5f775f4 VA: 0x759858f5f4
	public virtual String ToString(Boolean fVerbose) { }
	// RVA: 0x5f77b30 VA: 0x759858fb30
	internal DateTime GetNotAfter() { }
	// RVA: 0x5f7794c VA: 0x759858f94c
	internal DateTime GetNotBefore() { }
	// RVA: 0x5f779e8 VA: 0x759858f9e8
	protected static String FormatDate(DateTime date) { }
	// RVA: 0x5f77bcc VA: 0x759858fbcc
	internal Void ImportHandle(X509CertificateImpl impl) { }
	// RVA: 0x5f77c04 VA: 0x759858fc04
	internal X509CertificateImpl get_Impl() { }
	// RVA: 0x5f77c0c VA: 0x759858fc0c
	internal Boolean get_IsValid() { }
	// RVA: 0x5f77054 VA: 0x759858f054
	internal Void ThrowIfInvalid() { }
}
```