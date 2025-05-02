# SyncHashtable

**Namespace:** ` `


## Fields

- `Hashtable _table`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class SyncHashtable : Hashtable, IEnumerable
{
	protected Hashtable _table; // 0x50

	public override Int32 Count { get; }
	public override Boolean IsReadOnly { get; }
	public override Boolean IsFixedSize { get; }
	public override Boolean IsSynchronized { get; }
	public override Object Item { get; set; }
	public override Object SyncRoot { get; }
	public override ICollection Keys { get; }
	public override ICollection Values { get; }

	// RVA: 0x6089ac8 VA: 0x75986a1ac8
	internal Void .ctor(Hashtable table) { }
	// RVA: 0x608ae0c VA: 0x75986a2e0c
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x608ae50 VA: 0x75986a2e50
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x608ae90 VA: 0x75986a2e90
	public override Int32 get_Count() { }
	// RVA: 0x608aeb4 VA: 0x75986a2eb4
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x608aed8 VA: 0x75986a2ed8
	public override Boolean get_IsFixedSize() { }
	// RVA: 0x608aefc VA: 0x75986a2efc
	public override Boolean get_IsSynchronized() { }
	// RVA: 0x608af04 VA: 0x75986a2f04
	public override Object get_Item(Object key) { }
	// RVA: 0x608af28 VA: 0x75986a2f28
	public override Void set_Item(Object key, Object value) { }
	// RVA: 0x608b028 VA: 0x75986a3028
	public override Object get_SyncRoot() { }
	// RVA: 0x608b04c VA: 0x75986a304c
	public override Void Add(Object key, Object value) { }
	// RVA: 0x608b14c VA: 0x75986a314c
	public override Void Clear() { }
	// RVA: 0x608b23c VA: 0x75986a323c
	public override Boolean Contains(Object key) { }
	// RVA: 0x608b260 VA: 0x75986a3260
	public override Boolean ContainsKey(Object key) { }
	// RVA: 0x608b2f0 VA: 0x75986a32f0
	public override Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x608b3f0 VA: 0x75986a33f0
	public override Object Clone() { }
	// RVA: 0x608b554 VA: 0x75986a3554
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x608b578 VA: 0x75986a3578
	public override IDictionaryEnumerator GetEnumerator() { }
	// RVA: 0x608b59c VA: 0x75986a359c
	public override ICollection get_Keys() { }
	// RVA: 0x608b69c VA: 0x75986a369c
	public override ICollection get_Values() { }
	// RVA: 0x608b79c VA: 0x75986a379c
	public override Void Remove(Object key) { }
	// RVA: 0x608b894 VA: 0x75986a3894
	public override Void OnDeserialization(Object sender) { }
}
```