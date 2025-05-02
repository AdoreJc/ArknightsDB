# Grouping

**Namespace:** ` `


## Properties

- `TKey Key`


## Methods

- `TKey get_Key()`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : 
internal class Grouping : IGrouping`2, IEnumerable`1, IEnumerable, IList`1, ICollection`1
{
	internal TKey key; // 0x0
	internal Int32 hashCode; // 0x0
	internal TElement[] elements; // 0x0
	internal Int32 count; // 0x0
	internal Grouping hashNext; // 0x0
	internal Grouping next; // 0x0

	public TKey Key { get; }
	private Int32 System.Collections.Generic.ICollection<TElement>.Count { get; }
	private Boolean System.Collections.Generic.ICollection<TElement>.IsReadOnly { get; }
	private TElement System.Collections.Generic.IList<TElement>.Item { get; set; }

	// RVA: 0x VA: 0x0
	internal Void Add(TElement element) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public TKey get_Key() { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.Generic.ICollection<TElement>.get_Count() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<TElement>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<TElement>.Add(TElement item) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<TElement>.Clear() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<TElement>.Contains(TElement item) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<TElement>.CopyTo(TElement[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<TElement>.Remove(TElement item) { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.Generic.IList<TElement>.IndexOf(TElement item) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.IList<TElement>.Insert(Int32 index, TElement item) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.IList<TElement>.RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	private TElement System.Collections.Generic.IList<TElement>.get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.IList<TElement>.set_Item(Int32 index, TElement value) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```