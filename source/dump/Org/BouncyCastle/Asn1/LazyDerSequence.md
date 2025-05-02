# LazyDerSequence

**Namespace:** `Org.BouncyCastle.Asn1`


## Methods

- `Void Parse()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
internal class LazyDerSequence : DerSequence
{
	private Byte[] encoded; // 0x18

	public override Asn1Encodable Item { get; }
	public override Int32 Count { get; }

	// RVA: 0x65a4708 VA: 0x7598bbc708
	internal Void .ctor(Byte[] encoded) { }
	// RVA: 0x65a4868 VA: 0x7598bbc868
	private Void Parse() { }
	// RVA: 0x65a49b8 VA: 0x7598bbc9b8
	public override Asn1Encodable get_Item(Int32 index) { }
	// RVA: 0x65a49e4 VA: 0x7598bbc9e4
	public override IEnumerator GetEnumerator() { }
	// RVA: 0x65a4a00 VA: 0x7598bbca00
	public override Int32 get_Count() { }
	// RVA: 0x65a4a1c VA: 0x7598bbca1c
	internal override Void Encode(DerOutputStream derOut) { }
}
```