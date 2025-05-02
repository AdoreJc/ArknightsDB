# IListWrapper

**Namespace:** ` `


## Fields

- `IList _list`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class IListWrapper : ArrayList
{
	private IList _list; // 0x28

	public override Int32 Capacity { set; }
	public override Int32 Count { get; }
	public override Boolean IsReadOnly { get; }
	public override Boolean IsFixedSize { get; }
	public override Boolean IsSynchronized { get; }
	public override Object Item { get; set; }
	public override Object SyncRoot { get; }

	// RVA: 0x6083e7c VA: 0x759869be7c
	internal Void .ctor(IList list) { }
	// RVA: 0x608506c VA: 0x759869d06c
	public override Void set_Capacity(Int32 value) { }
	// RVA: 0x6085100 VA: 0x759869d100
	public override Int32 get_Count() { }
	// RVA: 0x60851a4 VA: 0x759869d1a4
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x6085248 VA: 0x759869d248
	public override Boolean get_IsFixedSize() { }
	// RVA: 0x60852ec VA: 0x759869d2ec
	public override Boolean get_IsSynchronized() { }
	// RVA: 0x6085390 VA: 0x759869d390
	public override Object get_Item(Int32 index) { }
	// RVA: 0x6085438 VA: 0x759869d438
	public override Void set_Item(Int32 index, Object value) { }
	// RVA: 0x6085504 VA: 0x759869d504
	public override Object get_SyncRoot() { }
	// RVA: 0x60855a8 VA: 0x759869d5a8
	public override Int32 Add(Object obj) { }
	// RVA: 0x6085664 VA: 0x759869d664
	public override Void AddRange(ICollection c) { }
	// RVA: 0x60856ac VA: 0x759869d6ac
	public override Void Clear() { }
	// RVA: 0x6085814 VA: 0x759869d814
	public override Object Clone() { }
	// RVA: 0x6085888 VA: 0x759869d888
	public override Boolean Contains(Object obj) { }
	// RVA: 0x6085934 VA: 0x759869d934
	public override Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x60859ec VA: 0x759869d9ec
	public override Void CopyTo(Int32 index, Array array, Int32 arrayIndex, Int32 count) { }
	// RVA: 0x6085d34 VA: 0x759869dd34
	public override IEnumerator GetEnumerator() { }
	// RVA: 0x6085dd4 VA: 0x759869ddd4
	public override Int32 IndexOf(Object value) { }
	// RVA: 0x6085e80 VA: 0x759869de80
	public override Void Insert(Int32 index, Object obj) { }
	// RVA: 0x6085f4c VA: 0x759869df4c
	public override Void InsertRange(Int32 index, ICollection c) { }
	// RVA: 0x608631c VA: 0x759869e31c
	public override Void Remove(Object value) { }
	// RVA: 0x608635c VA: 0x759869e35c
	public override Void RemoveAt(Int32 index) { }
	// RVA: 0x6086418 VA: 0x759869e418
	public override Void RemoveRange(Int32 index, Int32 count) { }
	// RVA: 0x6086638 VA: 0x759869e638
	public override Void Reverse(Int32 index, Int32 count) { }
	// RVA: 0x60869a8 VA: 0x759869e9a8
	public override Void Sort(Int32 index, Int32 count, IComparer comparer) { }
	// RVA: 0x6086c6c VA: 0x759869ec6c
	public override Object[] ToArray() { }
	// RVA: 0x6086dc8 VA: 0x759869edc8
	public override Array ToArray(Type type) { }
}
```