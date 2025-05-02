# DigestSession

**Namespace:** `System.Net`


## Fields

- `DateTime lastUse`

- `Int32 _nc`

- `HashAlgorithm hash`

- `DigestHeaderParser parser`

- `String _cnonce`


## Properties

- `String Algorithm`

- `String Realm`

- `String Nonce`

- `String Opaque`

- `String QOP`

- `String CNonce`

- `DateTime LastUse`


## Methods

- `String get_Algorithm()`

- `String get_Realm()`

- `String get_Nonce()`

- `String get_Opaque()`

- `String get_QOP()`

- `String get_CNonce()`

- `Boolean Parse(String)`

- `String HashToHexString(String)`

- `String HA1(String, String)`

- `String HA2(HttpWebRequest)`

- `String Response(String, String, HttpWebRequest)`

- `Authorization Authenticate(WebRequest, ICredentials)`

- `DateTime get_LastUse()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class DigestSession
{
	private static RandomNumberGenerator rng; // 0x0
	private DateTime lastUse; // 0x10
	private Int32 _nc; // 0x18
	private HashAlgorithm hash; // 0x20
	private DigestHeaderParser parser; // 0x28
	private String _cnonce; // 0x30

	public String Algorithm { get; }
	public String Realm { get; }
	public String Nonce { get; }
	public String Opaque { get; }
	public String QOP { get; }
	public String CNonce { get; }
	public DateTime LastUse { get; }

	// RVA: 0x6323db8 VA: 0x759893bdb8
	private static Void .cctor() { }
	// RVA: 0x6323e14 VA: 0x759893be14
	public Void .ctor() { }
	// RVA: 0x6323e84 VA: 0x759893be84
	public String get_Algorithm() { }
	// RVA: 0x6323e9c VA: 0x759893be9c
	public String get_Realm() { }
	// RVA: 0x6323eb4 VA: 0x759893beb4
	public String get_Nonce() { }
	// RVA: 0x6323ecc VA: 0x759893becc
	public String get_Opaque() { }
	// RVA: 0x6323ee4 VA: 0x759893bee4
	public String get_QOP() { }
	// RVA: 0x6323efc VA: 0x759893befc
	public String get_CNonce() { }
	// RVA: 0x6323ffc VA: 0x759893bffc
	public Boolean Parse(String challenge) { }
	// RVA: 0x63240fc VA: 0x759893c0fc
	private String HashToHexString(String toBeHashed) { }
	// RVA: 0x632424c VA: 0x759893c24c
	private String HA1(String username, String password) { }
	// RVA: 0x6324370 VA: 0x759893c370
	private String HA2(HttpWebRequest webRequest) { }
	// RVA: 0x6324440 VA: 0x759893c440
	private String Response(String username, String password, HttpWebRequest webRequest) { }
	// RVA: 0x63245a0 VA: 0x759893c5a0
	public Authorization Authenticate(WebRequest webRequest, ICredentials credentials) { }
	// RVA: 0x6324b80 VA: 0x759893cb80
	public DateTime get_LastUse() { }
}
```