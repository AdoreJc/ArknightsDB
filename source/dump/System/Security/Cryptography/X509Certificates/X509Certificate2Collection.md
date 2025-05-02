# X509Certificate2Collection

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Properties

- `X509Certificate2 Item`


## Methods

- `X509Certificate2 get_Item(Int32)`

- `Int32 Add(X509Certificate2)`

- `Void AddRange(X509Certificate2Collection)`

- `Boolean Contains(X509Certificate2)`

- `String GetKeyIdentifier(X509Certificate2)`

- `X509Certificate2Collection Find(X509FindType, Object, Boolean)`

- `X509Certificate2Enumerator GetEnumerator()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public class X509Certificate2Collection : X509CertificateCollection
{
	private static String[] newline_split; // 0x0

	public X509Certificate2 Item { get; }

	// RVA: 0x63a25c0 VA: 0x75989ba5c0
	public Void .ctor() { }
	// RVA: 0x63a25d0 VA: 0x75989ba5d0
	public Void .ctor(X509Certificate2Collection certificates) { }
	// RVA: 0x63a2670 VA: 0x75989ba670
	public X509Certificate2 get_Item(Int32 index) { }
	// RVA: 0x63a279c VA: 0x75989ba79c
	public Int32 Add(X509Certificate2 certificate) { }
	// RVA: 0x63a25fc VA: 0x75989ba5fc
	public Void AddRange(X509Certificate2Collection certificates) { }
	// RVA: 0x63a2810 VA: 0x75989ba810
	public Boolean Contains(X509Certificate2 certificate) { }
	// RVA: 0x63a2b94 VA: 0x75989bab94
	private String GetKeyIdentifier(X509Certificate2 x) { }
	// RVA: 0x63a347c VA: 0x75989bb47c
	public X509Certificate2Collection Find(X509FindType findType, Object findValue, Boolean validOnly) { }
	// RVA: 0x63a4620 VA: 0x75989bc620
	public X509Certificate2Enumerator GetEnumerator() { }
	// RVA: 0x63a473c VA: 0x75989bc73c
	private static Void .cctor() { }
}
```