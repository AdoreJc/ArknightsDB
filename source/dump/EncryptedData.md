# EncryptedData

**Namespace:** ` `


## Fields

- `Byte _version`

- `ContentInfo _content`

- `ContentInfo _encryptionAlgorithm`


## Properties

- `ContentInfo EncryptionAlgorithm`


## Methods

- `ContentInfo get_EncryptionAlgorithm()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : 
public class EncryptedData
{
	private Byte _version; // 0x10
	private ContentInfo _content; // 0x18
	private ContentInfo _encryptionAlgorithm; // 0x20
	private Byte[] _encrypted; // 0x28

	public ContentInfo EncryptionAlgorithm { get; }
	public Byte[] EncryptedContent { get; }

	// RVA: 0x5ed56c8 VA: 0x75984ed6c8
	public Void .ctor() { }
	// RVA: 0x5ed56e4 VA: 0x75984ed6e4
	public Void .ctor(ASN1 asn1) { }
	// RVA: 0x5ed5a0c VA: 0x75984eda0c
	public ContentInfo get_EncryptionAlgorithm() { }
	// RVA: 0x5ed5a14 VA: 0x75984eda14
	public Byte[] get_EncryptedContent() { }
}
```