# PrivateKeyInfo

**Namespace:** ` `


## Fields

- `Int32 _version`

- `String _algorithm`

- `ArrayList _list`


## Properties

- `String Algorithm`


## Methods

- `String get_Algorithm()`

- `Void Decode(Byte[])`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : 
public class PrivateKeyInfo
{
	private Int32 _version; // 0x10
	private String _algorithm; // 0x18
	private Byte[] _key; // 0x20
	private ArrayList _list; // 0x28

	public String Algorithm { get; }
	public Byte[] PrivateKey { get; }

	// RVA: 0x5eec90c VA: 0x759850490c
	public Void .ctor() { }
	// RVA: 0x5eec984 VA: 0x7598504984
	public Void .ctor(Byte[] data) { }
	// RVA: 0x5eecc2c VA: 0x7598504c2c
	public String get_Algorithm() { }
	// RVA: 0x5eecc34 VA: 0x7598504c34
	public Byte[] get_PrivateKey() { }
	// RVA: 0x5eec9ac VA: 0x75985049ac
	private Void Decode(Byte[] data) { }
	// RVA: 0x5eecca8 VA: 0x7598504ca8
	private static Byte[] RemoveLeadingZero(Byte[] bigInt) { }
	// RVA: 0x5eecd44 VA: 0x7598504d44
	private static Byte[] Normalize(Byte[] bigInt, Int32 length) { }
	// RVA: 0x5eecde4 VA: 0x7598504de4
	public static RSA DecodeRSA(Byte[] keypair) { }
	// RVA: 0x5eed24c VA: 0x759850524c
	public static Byte[] Encode(RSA rsa) { }
	// RVA: 0x5eed44c VA: 0x759850544c
	public static DSA DecodeDSA(Byte[] privateKey, DSAParameters dsaParameters) { }
	// RVA: 0x5eed584 VA: 0x7598505584
	public static Byte[] Encode(DSA dsa) { }
	// RVA: 0x5eed5d4 VA: 0x75985055d4
	public static Byte[] Encode(AsymmetricAlgorithm aa) { }
}
```