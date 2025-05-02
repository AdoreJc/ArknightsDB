# AttributeCollection

**Namespace:** `System.ComponentModel`


## Fields

- `Int32 _index`


## Properties

- `Int32 Count`


## Methods

- `Int32 get_Count()`

- `Boolean Contains(Attribute)`

- `Boolean Contains(Attribute[])`

- `Attribute GetDefaultAttribute(Type)`

- `IEnumerator GetEnumerator()`

- `Boolean Matches(Attribute)`

- `Boolean Matches(Attribute[])`

- `Void CopyTo(Array, Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class AttributeCollection : ICollection, IEnumerable
{
	public static readonly AttributeCollection Empty; // 0x0
	private static Hashtable s_defaultAttributes; // 0x8
	private readonly Attribute[] _attributes; // 0x10
	private static readonly Object s_internalSyncObject; // 0x10
	private const Int32 FOUND_TYPES_LIMIT; // 0x0
	private AttributeEntry[] _foundAttributeTypes; // 0x18
	private Int32 _index; // 0x20

	protected virtual Attribute[] Attributes { get; }
	public Int32 Count { get; }
	public virtual Attribute Item { get; }
	public virtual Attribute Item { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private Int32 System.Collections.ICollection.Count { get; }

	// RVA: 0x63b44fc VA: 0x75989cc4fc
	public Void .ctor(Attribute[] attributes) { }
	// RVA: 0x63b4630 VA: 0x75989cc630
	protected Void .ctor() { }
	// RVA: 0x63b4638 VA: 0x75989cc638
	public static AttributeCollection FromExisting(AttributeCollection existing, Attribute[] newAttributes) { }
	// RVA: 0x63b4a48 VA: 0x75989cca48
	protected virtual Attribute[] get_Attributes() { }
	// RVA: 0x63b49b8 VA: 0x75989cc9b8
	public Int32 get_Count() { }
	// RVA: 0x63b4a50 VA: 0x75989cca50
	public virtual Attribute get_Item(Int32 index) { }
	// RVA: 0x63b4a90 VA: 0x75989cca90
	public virtual Attribute get_Item(Type attributeType) { }
	// RVA: 0x63b54d8 VA: 0x75989cd4d8
	public Boolean Contains(Attribute attribute) { }
	// RVA: 0x63b5538 VA: 0x75989cd538
	public Boolean Contains(Attribute[] attributes) { }
	// RVA: 0x63b4f80 VA: 0x75989ccf80
	protected Attribute GetDefaultAttribute(Type attributeType) { }
	// RVA: 0x63b55b0 VA: 0x75989cd5b0
	public IEnumerator GetEnumerator() { }
	// RVA: 0x63b55d4 VA: 0x75989cd5d4
	public Boolean Matches(Attribute attribute) { }
	// RVA: 0x63b5680 VA: 0x75989cd680
	public Boolean Matches(Attribute[] attributes) { }
	// RVA: 0x63b56fc VA: 0x75989cd6fc
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x63b5704 VA: 0x75989cd704
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x63b570c VA: 0x75989cd70c
	private Int32 System.Collections.ICollection.get_Count() { }
	// RVA: 0x63b5730 VA: 0x75989cd730
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x63b49dc VA: 0x75989cc9dc
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x63b5734 VA: 0x75989cd734
	private static Void .cctor() { }
}
```