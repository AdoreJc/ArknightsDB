# SyncSortedList

**Namespace:** ` `


## Fields

- `SortedList _list`

- `Object _root`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class SyncSortedList : SortedList
{
	private SortedList _list; // 0x48
	private Object _root; // 0x50

	public override Int32 Count { get; }
	public override Object SyncRoot { get; }
	public override Boolean IsReadOnly { get; }
	public override Boolean IsFixedSize { get; }
	public override Boolean IsSynchronized { get; }
	public override Object Item { get; set; }

	// RVA: 0x6080d6c VA: 0x7598698d6c
	internal Void .ctor(SortedList list) { }
	// RVA: 0x6080dd0 VA: 0x7598698dd0
	public override Int32 get_Count() { }
	// RVA: 0x6080eb4 VA: 0x7598698eb4
	public override Object get_SyncRoot() { }
	// RVA: 0x6080ebc VA: 0x7598698ebc
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x6080ee0 VA: 0x7598698ee0
	public override Boolean get_IsFixedSize() { }
	// RVA: 0x6080f04 VA: 0x7598698f04
	public override Boolean get_IsSynchronized() { }
	// RVA: 0x6080f0c VA: 0x7598698f0c
	public override Object get_Item(Object key) { }
	// RVA: 0x6080ff8 VA: 0x7598698ff8
	public override Void set_Item(Object key, Object value) { }
	// RVA: 0x60810dc VA: 0x75986990dc
	public override Void Add(Object key, Object value) { }
	// RVA: 0x60811c0 VA: 0x75986991c0
	public override Void Clear() { }
	// RVA: 0x6081294 VA: 0x7598699294
	public override Object Clone() { }
	// RVA: 0x6081378 VA: 0x7598699378
	public override Boolean Contains(Object key) { }
	// RVA: 0x6081464 VA: 0x7598699464
	public override Boolean ContainsValue(Object key) { }
	// RVA: 0x6081550 VA: 0x7598699550
	public override Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x6081634 VA: 0x7598699634
	public override Object GetByIndex(Int32 index) { }
	// RVA: 0x6081720 VA: 0x7598699720
	public override IDictionaryEnumerator GetEnumerator() { }
	// RVA: 0x6081804 VA: 0x7598699804
	public override Object GetKey(Int32 index) { }
	// RVA: 0x60818f0 VA: 0x75986998f0
	public override IList GetKeyList() { }
	// RVA: 0x60819d4 VA: 0x75986999d4
	public override IList GetValueList() { }
	// RVA: 0x6081ab8 VA: 0x7598699ab8
	public override Int32 IndexOfKey(Object key) { }
	// RVA: 0x6081c0c VA: 0x7598699c0c
	public override Int32 IndexOfValue(Object value) { }
	// RVA: 0x6081cf8 VA: 0x7598699cf8
	public override Void RemoveAt(Int32 index) { }
	// RVA: 0x6081dd4 VA: 0x7598699dd4
	public override Void Remove(Object key) { }
}
```