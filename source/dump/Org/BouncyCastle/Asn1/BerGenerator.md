# BerGenerator

**Namespace:** `Org.BouncyCastle.Asn1`


## Fields

- `Boolean _tagged`

- `Boolean _isExplicit`

- `Int32 _tagNo`


## Methods

- `Void WriteHdr(Int32)`

- `Void WriteBerHeader(Int32)`

- `Void WriteBerBody(Stream)`

- `Void WriteBerEnd()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class BerGenerator : Asn1Generator
{
	private Boolean _tagged; // 0x18
	private Boolean _isExplicit; // 0x19
	private Int32 _tagNo; // 0x1c


	// RVA: 0x6596afc VA: 0x7598baeafc
	protected Void .ctor(Stream outStream) { }
	// RVA: 0x6596b2c VA: 0x7598baeb2c
	public Void .ctor(Stream outStream, Int32 tagNo, Boolean isExplicit) { }
	// RVA: 0x6596b80 VA: 0x7598baeb80
	public override Void AddObject(Asn1Encodable obj) { }
	// RVA: 0x6596c0c VA: 0x7598baec0c
	public override Stream GetRawOutputStream() { }
	// RVA: 0x6596c14 VA: 0x7598baec14
	public override Void Close() { }
	// RVA: 0x6596cb0 VA: 0x7598baecb0
	private Void WriteHdr(Int32 tag) { }
	// RVA: 0x6596cf4 VA: 0x7598baecf4
	protected Void WriteBerHeader(Int32 tag) { }
	// RVA: 0x6596d4c VA: 0x7598baed4c
	protected Void WriteBerBody(Stream contentStream) { }
	// RVA: 0x6596c18 VA: 0x7598baec18
	protected Void WriteBerEnd() { }
}
```