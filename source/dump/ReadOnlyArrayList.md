# ReadOnlyArrayList

**Namespace:** ` `


## Fields

- `ArrayList _list`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class ReadOnlyArrayList : ArrayList
{
	private ArrayList _list; // 0x28

	public override Int32 Count { get; }
	public override Boolean IsReadOnly { get; }
	public override Boolean IsFixedSize { get; }
	public override Boolean IsSynchronized { get; }
	public override Object Item { get; set; }
	public override Object SyncRoot { get; }
	public override Int32 Capacity { set; }

	// RVA: 0x6084918 VA: 0x759869c918
	internal Void .ctor(ArrayList l) { }
	// RVA: 0x6086f80 VA: 0x759869ef80
	public override Int32 get_Count() { }
	// RVA: 0x6086fa4 VA: 0x759869efa4
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x6086fac VA: 0x759869efac
	public override Boolean get_IsFixedSize() { }
	// RVA: 0x6086fb4 VA: 0x759869efb4
	public override Boolean get_IsSynchronized() { }
	// RVA: 0x6086fd8 VA: 0x759869efd8
	public override Object get_Item(Int32 index) { }
	// RVA: 0x6086ffc VA: 0x759869effc
	public override Void set_Item(Int32 index, Object value) { }
	// RVA: 0x608704c VA: 0x759869f04c
	public override Object get_SyncRoot() { }
	// RVA: 0x6087070 VA: 0x759869f070
	public override Int32 Add(Object obj) { }
	// RVA: 0x60870c0 VA: 0x759869f0c0
	public override Void AddRange(ICollection c) { }
	// RVA: 0x6087110 VA: 0x759869f110
	public override Void set_Capacity(Int32 value) { }
	// RVA: 0x6087160 VA: 0x759869f160
	public override Void Clear() { }
	// RVA: 0x60871b0 VA: 0x759869f1b0
	public override Object Clone() { }
	// RVA: 0x60872c8 VA: 0x759869f2c8
	public override Boolean Contains(Object obj) { }
	// RVA: 0x60872ec VA: 0x759869f2ec
	public override Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x6087310 VA: 0x759869f310
	public override Void CopyTo(Int32 index, Array array, Int32 arrayIndex, Int32 count) { }
	// RVA: 0x6087334 VA: 0x759869f334
	public override IEnumerator GetEnumerator() { }
	// RVA: 0x6087358 VA: 0x759869f358
	public override Int32 IndexOf(Object value) { }
	// RVA: 0x608737c VA: 0x759869f37c
	public override Void Insert(Int32 index, Object obj) { }
	// RVA: 0x60873cc VA: 0x759869f3cc
	public override Void InsertRange(Int32 index, ICollection c) { }
	// RVA: 0x608741c VA: 0x759869f41c
	public override Void Remove(Object value) { }
	// RVA: 0x608746c VA: 0x759869f46c
	public override Void RemoveAt(Int32 index) { }
	// RVA: 0x60874bc VA: 0x759869f4bc
	public override Void RemoveRange(Int32 index, Int32 count) { }
	// RVA: 0x608750c VA: 0x759869f50c
	public override Void Reverse(Int32 index, Int32 count) { }
	// RVA: 0x608755c VA: 0x759869f55c
	public override Void Sort(Int32 index, Int32 count, IComparer comparer) { }
	// RVA: 0x60875ac VA: 0x759869f5ac
	public override Object[] ToArray() { }
	// RVA: 0x60875d0 VA: 0x759869f5d0
	public override Array ToArray(Type type) { }
}
```