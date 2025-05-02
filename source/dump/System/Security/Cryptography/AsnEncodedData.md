# AsnEncodedData

**Namespace:** `System.Security.Cryptography`


## Properties

- `Oid Oid`


## Methods

- `Oid get_Oid()`

- `Void set_Oid(Oid)`

- `Void set_RawData(Byte[])`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography
public class AsnEncodedData
{
	internal Oid _oid; // 0x10
	internal Byte[] _raw; // 0x18

	public Oid Oid { get; set; }
	public Byte[] RawData { get; set; }

	// RVA: 0x639cb84 VA: 0x75989b4b84
	protected Void .ctor() { }
	// RVA: 0x639cb8c VA: 0x75989b4b8c
	public Void .ctor(String oid, Byte[] rawData) { }
	// RVA: 0x639cd14 VA: 0x75989b4d14
	public Void .ctor(Oid oid, Byte[] rawData) { }
	// RVA: 0x639cdd0 VA: 0x75989b4dd0
	public Void .ctor(AsnEncodedData asnEncodedData) { }
	// RVA: 0x639ceb0 VA: 0x75989b4eb0
	public Oid get_Oid() { }
	// RVA: 0x639cd50 VA: 0x75989b4d50
	public Void set_Oid(Oid value) { }
	// RVA: 0x639ceb8 VA: 0x75989b4eb8
	public Byte[] get_RawData() { }
	// RVA: 0x639cc1c VA: 0x75989b4c1c
	public Void set_RawData(Byte[] value) { }
	// RVA: 0x639cec0 VA: 0x75989b4ec0
	public virtual Void CopyFrom(AsnEncodedData asnEncodedData) { }
	// RVA: 0x639cfa0 VA: 0x75989b4fa0
	public virtual String Format(Boolean multiLine) { }
	// RVA: 0x639d144 VA: 0x75989b5144
	internal virtual String ToString(Boolean multiLine) { }
	// RVA: 0x639d030 VA: 0x75989b5030
	internal String Default(Boolean multiLine) { }
	// RVA: 0x639d2f4 VA: 0x75989b52f4
	internal String BasicConstraintsExtension(Boolean multiLine) { }
	// RVA: 0x639d400 VA: 0x75989b5400
	internal String EnhancedKeyUsageExtension(Boolean multiLine) { }
	// RVA: 0x639d50c VA: 0x75989b550c
	internal String KeyUsageExtension(Boolean multiLine) { }
	// RVA: 0x639d618 VA: 0x75989b5618
	internal String SubjectKeyIdentifierExtension(Boolean multiLine) { }
	// RVA: 0x639d724 VA: 0x75989b5724
	internal String SubjectAltName(Boolean multiLine) { }
	// RVA: 0x639dae4 VA: 0x75989b5ae4
	internal String NetscapeCertType(Boolean multiLine) { }
}
```