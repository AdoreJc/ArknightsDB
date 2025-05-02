# X509Extension

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `Boolean _critical`


## Properties

- `Boolean Critical`


## Methods

- `Boolean get_Critical()`

- `Void set_Critical(Boolean)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public class X509Extension : AsnEncodedData
{
	private Boolean _critical; // 0x20

	public Boolean Critical { get; set; }

	// RVA: 0x639f7e4 VA: 0x75989b77e4
	protected Void .ctor() { }
	// RVA: 0x63ac958 VA: 0x75989c4958
	public Void .ctor(String oid, Byte[] rawData, Boolean critical) { }
	// RVA: 0x63ac97c VA: 0x75989c497c
	public Boolean get_Critical() { }
	// RVA: 0x63ac984 VA: 0x75989c4984
	public Void set_Critical(Boolean value) { }
	// RVA: 0x63ac990 VA: 0x75989c4990
	public override Void CopyFrom(AsnEncodedData asnEncodedData) { }
	// RVA: 0x63a0200 VA: 0x75989b8200
	internal String FormatUnkownData(Byte[] data) { }
}
```