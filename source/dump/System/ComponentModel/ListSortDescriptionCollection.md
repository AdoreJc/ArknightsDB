# ListSortDescriptionCollection

**Namespace:** `System.ComponentModel`


## Fields

- `ArrayList _sorts`


## Properties

- `ListSortDescription Item`

- `Int32 Count`


## Methods

- `ListSortDescription get_Item(Int32)`

- `Void set_Item(Int32, ListSortDescription)`

- `Boolean Contains(Object)`

- `Int32 IndexOf(Object)`

- `Int32 get_Count()`

- `Void CopyTo(Array, Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class ListSortDescriptionCollection : IList, ICollection, IEnumerable
{
	private ArrayList _sorts; // 0x10

	public ListSortDescription Item { get; set; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Object System.Collections.IList.Item { get; set; }
	public Int32 Count { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }

	// RVA: 0x63c74fc VA: 0x75989df4fc
	public Void .ctor() { }
	// RVA: 0x63c7570 VA: 0x75989df570
	public Void .ctor(ListSortDescription[] sorts) { }
	// RVA: 0x63c764c VA: 0x75989df64c
	public ListSortDescription get_Item(Int32 index) { }
	// RVA: 0x63c76e4 VA: 0x75989df6e4
	public Void set_Item(Int32 index, ListSortDescription value) { }
	// RVA: 0x63c7734 VA: 0x75989df734
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x63c773c VA: 0x75989df73c
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x63c7744 VA: 0x75989df744
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x63c7748 VA: 0x75989df748
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x63c7798 VA: 0x75989df798
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x63c77e8 VA: 0x75989df7e8
	private Void System.Collections.IList.Clear() { }
	// RVA: 0x63c7838 VA: 0x75989df838
	public Boolean Contains(Object value) { }
	// RVA: 0x63c78e4 VA: 0x75989df8e4
	public Int32 IndexOf(Object value) { }
	// RVA: 0x63c7990 VA: 0x75989df990
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x63c79e0 VA: 0x75989df9e0
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x63c7a30 VA: 0x75989dfa30
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
	// RVA: 0x63c7a80 VA: 0x75989dfa80
	public Int32 get_Count() { }
	// RVA: 0x63c7aa4 VA: 0x75989dfaa4
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x63c7aac VA: 0x75989dfaac
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x63c7ab0 VA: 0x75989dfab0
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x63c7ad4 VA: 0x75989dfad4
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```