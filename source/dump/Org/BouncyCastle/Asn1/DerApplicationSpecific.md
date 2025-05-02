# DerApplicationSpecific

**Namespace:** `Org.BouncyCastle.Asn1`


## Properties

- `Int32 ApplicationTag`


## Methods

- `Int32 GetLengthOfHeader(Byte[])`

- `Boolean IsConstructed()`

- `Int32 get_ApplicationTag()`

- `Asn1Object GetObject()`

- `Asn1Object GetObject(Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerApplicationSpecific : Asn1Object
{
	private readonly Boolean isConstructed; // 0x10
	private readonly Int32 tag; // 0x14
	private readonly Byte[] octets; // 0x18

	public Int32 ApplicationTag { get; }

	// RVA: 0x658e338 VA: 0x7598ba6338
	internal Void .ctor(Boolean isConstructed, Int32 tag, Byte[] octets) { }
	// RVA: 0x659a424 VA: 0x7598bb2424
	public Void .ctor(Int32 tag, Byte[] octets) { }
	// RVA: 0x659a460 VA: 0x7598bb2460
	public Void .ctor(Int32 tag, Asn1Encodable obj) { }
	// RVA: 0x659a470 VA: 0x7598bb2470
	public Void .ctor(Boolean isExplicit, Int32 tag, Asn1Encodable obj) { }
	// RVA: 0x65962b8 VA: 0x7598bae2b8
	public Void .ctor(Int32 tagNo, Asn1EncodableVector vec) { }
	// RVA: 0x659a574 VA: 0x7598bb2574
	private Int32 GetLengthOfHeader(Byte[] data) { }
	// RVA: 0x659a63c VA: 0x7598bb263c
	public Boolean IsConstructed() { }
	// RVA: 0x659a644 VA: 0x7598bb2644
	public Byte[] GetContents() { }
	// RVA: 0x659a64c VA: 0x7598bb264c
	public Int32 get_ApplicationTag() { }
	// RVA: 0x659a654 VA: 0x7598bb2654
	public Asn1Object GetObject() { }
	// RVA: 0x659a65c VA: 0x7598bb265c
	public Asn1Object GetObject(Int32 derTagNo) { }
	// RVA: 0x659a85c VA: 0x7598bb285c
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659a8e4 VA: 0x7598bb28e4
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659a9a0 VA: 0x7598bb29a0
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x659a710 VA: 0x7598bb2710
	private Byte[] ReplaceTagNumber(Int32 newTag, Byte[] input) { }
}
```