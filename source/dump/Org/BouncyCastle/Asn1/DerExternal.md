# DerExternal

**Namespace:** `Org.BouncyCastle.Asn1`


## Fields

- `DerObjectIdentifier directReference`

- `DerInteger indirectReference`

- `Asn1Object dataValueDescriptor`

- `Int32 encoding`

- `Asn1Object externalContent`


## Properties

- `Asn1Object DataValueDescriptor`

- `DerObjectIdentifier DirectReference`

- `Int32 Encoding`

- `Asn1Object ExternalContent`

- `DerInteger IndirectReference`


## Methods

- `Asn1Object get_DataValueDescriptor()`

- `Void set_DataValueDescriptor(Asn1Object)`

- `DerObjectIdentifier get_DirectReference()`

- `Void set_DirectReference(DerObjectIdentifier)`

- `Int32 get_Encoding()`

- `Void set_Encoding(Int32)`

- `Asn1Object get_ExternalContent()`

- `Void set_ExternalContent(Asn1Object)`

- `DerInteger get_IndirectReference()`

- `Void set_IndirectReference(DerInteger)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerExternal : Asn1Object
{
	private DerObjectIdentifier directReference; // 0x10
	private DerInteger indirectReference; // 0x18
	private Asn1Object dataValueDescriptor; // 0x20
	private Int32 encoding; // 0x28
	private Asn1Object externalContent; // 0x30

	public Asn1Object DataValueDescriptor { get; set; }
	public DerObjectIdentifier DirectReference { get; set; }
	public Int32 Encoding { get; set; }
	public Asn1Object ExternalContent { get; set; }
	public DerInteger IndirectReference { get; set; }

	// RVA: 0x658e62c VA: 0x7598ba662c
	public Void .ctor(Asn1EncodableVector vector) { }
	// RVA: 0x659c320 VA: 0x7598bb4320
	public Void .ctor(DerObjectIdentifier directReference, DerInteger indirectReference, Asn1Object dataValueDescriptor, DerTaggedObject externalData) { }
	// RVA: 0x659c380 VA: 0x7598bb4380
	public Void .ctor(DerObjectIdentifier directReference, DerInteger indirectReference, Asn1Object dataValueDescriptor, Int32 encoding, Asn1Object externalData) { }
	// RVA: 0x659c424 VA: 0x7598bb4424
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659c584 VA: 0x7598bb4584
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x659c608 VA: 0x7598bb4608
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659c6f8 VA: 0x7598bb46f8
	public Asn1Object get_DataValueDescriptor() { }
	// RVA: 0x659c700 VA: 0x7598bb4700
	public Void set_DataValueDescriptor(Asn1Object value) { }
	// RVA: 0x659c708 VA: 0x7598bb4708
	public DerObjectIdentifier get_DirectReference() { }
	// RVA: 0x659c710 VA: 0x7598bb4710
	public Void set_DirectReference(DerObjectIdentifier value) { }
	// RVA: 0x659c718 VA: 0x7598bb4718
	public Int32 get_Encoding() { }
	// RVA: 0x659c294 VA: 0x7598bb4294
	public Void set_Encoding(Int32 value) { }
	// RVA: 0x659c720 VA: 0x7598bb4720
	public Asn1Object get_ExternalContent() { }
	// RVA: 0x659c728 VA: 0x7598bb4728
	public Void set_ExternalContent(Asn1Object value) { }
	// RVA: 0x659c730 VA: 0x7598bb4730
	public DerInteger get_IndirectReference() { }
	// RVA: 0x659c738 VA: 0x7598bb4738
	public Void set_IndirectReference(DerInteger value) { }
	// RVA: 0x659c1ec VA: 0x7598bb41ec
	private static Asn1Object GetObjFromVector(Asn1EncodableVector v, Int32 index) { }
	// RVA: 0x659c538 VA: 0x7598bb4538
	private static Void WriteEncodable(MemoryStream ms, Asn1Encodable e) { }
}
```