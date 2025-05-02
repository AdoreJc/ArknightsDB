# Asn1EncodableVector

**Namespace:** `Org.BouncyCastle.Asn1`


## Fields

- `IList v`


## Properties

- `Asn1Encodable Item`

- `Int32 Size`

- `Int32 Count`


## Methods

- `Void Add(Asn1Encodable[])`

- `Void AddOptional(Asn1Encodable[])`

- `Asn1Encodable get_Item(Int32)`

- `Asn1Encodable Get(Int32)`

- `Int32 get_Size()`

- `Int32 get_Count()`

- `IEnumerator GetEnumerator()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class Asn1EncodableVector : IEnumerable
{
	private IList v; // 0x10

	public Asn1Encodable Item { get; }
	public Int32 Size { get; }
	public Int32 Count { get; }

	// RVA: 0x658d200 VA: 0x7598ba5200
	public static Asn1EncodableVector FromEnumerable(IEnumerable e) { }
	// RVA: 0x658d634 VA: 0x7598ba5634
	public Void .ctor(Asn1Encodable[] v) { }
	// RVA: 0x658d6bc VA: 0x7598ba56bc
	public Void Add(Asn1Encodable[] objs) { }
	// RVA: 0x658d7b8 VA: 0x7598ba57b8
	public Void AddOptional(Asn1Encodable[] objs) { }
	// RVA: 0x658d8b8 VA: 0x7598ba58b8
	public Asn1Encodable get_Item(Int32 index) { }
	// RVA: 0x658d9ac VA: 0x7598ba59ac
	public Asn1Encodable Get(Int32 index) { }
	// RVA: 0x658d9b0 VA: 0x7598ba59b0
	public Int32 get_Size() { }
	// RVA: 0x658da54 VA: 0x7598ba5a54
	public Int32 get_Count() { }
	// RVA: 0x658daf8 VA: 0x7598ba5af8
	public IEnumerator GetEnumerator() { }
}
```