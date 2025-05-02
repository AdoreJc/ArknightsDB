# LazyDerSet

**Namespace:** `Org.BouncyCastle.Asn1`


## Methods

- `Void Parse()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
internal class LazyDerSet : DerSet
{
	private Byte[] encoded; // 0x18

	public override Asn1Encodable Item { get; }
	public override Int32 Count { get; }

	// RVA: 0x65a47f4 VA: 0x7598bbc7f4
	internal Void .ctor(Byte[] encoded) { }
	// RVA: 0x65a4b08 VA: 0x7598bbcb08
	private Void Parse() { }
	// RVA: 0x65a4c58 VA: 0x7598bbcc58
	public override Asn1Encodable get_Item(Int32 index) { }
	// RVA: 0x65a4c84 VA: 0x7598bbcc84
	public override IEnumerator GetEnumerator() { }
	// RVA: 0x65a4ca0 VA: 0x7598bbcca0
	public override Int32 get_Count() { }
	// RVA: 0x65a4cbc VA: 0x7598bbccbc
	internal override Void Encode(DerOutputStream derOut) { }
}
```