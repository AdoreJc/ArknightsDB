# CaptureCollection

**Namespace:** `System.Text.RegularExpressions`


## Properties

- `Boolean IsReadOnly`

- `Int32 Count`

- `Capture Item`

- `Boolean IsSynchronized`

- `Object SyncRoot`


## Methods

- `Boolean get_IsReadOnly()`

- `Int32 get_Count()`

- `Capture get_Item(Int32)`

- `IEnumerator GetEnumerator()`

- `Capture GetCapture(Int32)`

- `Boolean get_IsSynchronized()`

- `Object get_SyncRoot()`

- `Void CopyTo(Array, Int32)`

- `Void CopyTo(Capture[], Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Text.RegularExpressions
public class CaptureCollection : IList`1, ICollection`1, IEnumerable`1, IEnumerable, IReadOnlyList`1, IReadOnlyCollection`1, IList, ICollection
{
	private readonly Group _group; // 0x10
	private readonly Int32 _capcount; // 0x18
	private Capture[] _captures; // 0x20

	public Boolean IsReadOnly { get; }
	public Int32 Count { get; }
	public Capture Item { get; }
	public Boolean IsSynchronized { get; }
	public Object SyncRoot { get; }
	private Capture System.Collections.Generic.IList<System.Text.RegularExpressions.Capture>.Item { get; set; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Object System.Collections.IList.Item { get; set; }

	// RVA: 0x63756a4 VA: 0x759898d6a4
	internal Void .ctor(Group group) { }
	// RVA: 0x63756f0 VA: 0x759898d6f0
	public Boolean get_IsReadOnly() { }
	// RVA: 0x63756f8 VA: 0x759898d6f8
	public Int32 get_Count() { }
	// RVA: 0x6375700 VA: 0x759898d700
	public Capture get_Item(Int32 i) { }
	// RVA: 0x63757cc VA: 0x759898d7cc
	public IEnumerator GetEnumerator() { }
	// RVA: 0x6375880 VA: 0x759898d880
	private IEnumerator`1 System.Collections.Generic.IEnumerable<System.Text.RegularExpressions.Capture>.GetEnumerator() { }
	// RVA: 0x6375704 VA: 0x759898d704
	private Capture GetCapture(Int32 i) { }
	// RVA: 0x63758f8 VA: 0x759898d8f8
	internal Void ForceInitialized() { }
	// RVA: 0x6375a90 VA: 0x759898da90
	public Boolean get_IsSynchronized() { }
	// RVA: 0x6375a98 VA: 0x759898da98
	public Object get_SyncRoot() { }
	// RVA: 0x6375aa0 VA: 0x759898daa0
	public Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x6375b5c VA: 0x759898db5c
	public Void CopyTo(Capture[] array, Int32 arrayIndex) { }
	// RVA: 0x6375cd4 VA: 0x759898dcd4
	private Int32 System.Collections.Generic.IList<System.Text.RegularExpressions.Capture>.IndexOf(Capture item) { }
	// RVA: 0x6375d84 VA: 0x759898dd84
	private Void System.Collections.Generic.IList<System.Text.RegularExpressions.Capture>.Insert(Int32 index, Capture item) { }
	// RVA: 0x6375dd4 VA: 0x759898ddd4
	private Void System.Collections.Generic.IList<System.Text.RegularExpressions.Capture>.RemoveAt(Int32 index) { }
	// RVA: 0x6375e24 VA: 0x759898de24
	private Capture System.Collections.Generic.IList<System.Text.RegularExpressions.Capture>.get_Item(Int32 index) { }
	// RVA: 0x6375e28 VA: 0x759898de28
	private Void System.Collections.Generic.IList<System.Text.RegularExpressions.Capture>.set_Item(Int32 index, Capture value) { }
	// RVA: 0x6375e78 VA: 0x759898de78
	private Void System.Collections.Generic.ICollection<System.Text.RegularExpressions.Capture>.Add(Capture item) { }
	// RVA: 0x6375ec8 VA: 0x759898dec8
	private Void System.Collections.Generic.ICollection<System.Text.RegularExpressions.Capture>.Clear() { }
	// RVA: 0x6375f18 VA: 0x759898df18
	private Boolean System.Collections.Generic.ICollection<System.Text.RegularExpressions.Capture>.Contains(Capture item) { }
	// RVA: 0x6375fcc VA: 0x759898dfcc
	private Boolean System.Collections.Generic.ICollection<System.Text.RegularExpressions.Capture>.Remove(Capture item) { }
	// RVA: 0x637601c VA: 0x759898e01c
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x637606c VA: 0x759898e06c
	private Void System.Collections.IList.Clear() { }
	// RVA: 0x63760bc VA: 0x759898e0bc
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x63761b0 VA: 0x759898e1b0
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x63762a4 VA: 0x759898e2a4
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x63762f4 VA: 0x759898e2f4
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x63762fc VA: 0x759898e2fc
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x637634c VA: 0x759898e34c
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
	// RVA: 0x637639c VA: 0x759898e39c
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x63763a0 VA: 0x759898e3a0
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
}
```