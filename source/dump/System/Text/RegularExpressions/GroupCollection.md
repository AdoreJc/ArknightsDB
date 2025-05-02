# GroupCollection

**Namespace:** `System.Text.RegularExpressions`


## Properties

- `Boolean IsReadOnly`

- `Int32 Count`

- `Group Item`

- `Group Item`

- `Boolean IsSynchronized`

- `Object SyncRoot`


## Methods

- `Boolean get_IsReadOnly()`

- `Int32 get_Count()`

- `Group get_Item(Int32)`

- `Group get_Item(String)`

- `IEnumerator GetEnumerator()`

- `Group GetGroup(Int32)`

- `Group GetGroupImpl(Int32)`

- `Boolean get_IsSynchronized()`

- `Object get_SyncRoot()`

- `Void CopyTo(Array, Int32)`

- `Void CopyTo(Group[], Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Text.RegularExpressions
public class GroupCollection : IList`1, ICollection`1, IEnumerable`1, IEnumerable, IReadOnlyList`1, IReadOnlyCollection`1, IList, ICollection
{
	private readonly Match _match; // 0x10
	private readonly Hashtable _captureMap; // 0x18
	private Group[] _groups; // 0x20

	public Boolean IsReadOnly { get; }
	public Int32 Count { get; }
	public Group Item { get; }
	public Group Item { get; }
	public Boolean IsSynchronized { get; }
	public Object SyncRoot { get; }
	private Group System.Collections.Generic.IList<System.Text.RegularExpressions.Group>.Item { get; set; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Object System.Collections.IList.Item { get; set; }

	// RVA: 0x6376744 VA: 0x759898e744
	internal Void .ctor(Match match, Hashtable caps) { }
	// RVA: 0x6376788 VA: 0x759898e788
	public Boolean get_IsReadOnly() { }
	// RVA: 0x6376790 VA: 0x759898e790
	public Int32 get_Count() { }
	// RVA: 0x63767b4 VA: 0x759898e7b4
	public Group get_Item(Int32 groupnum) { }
	// RVA: 0x63768bc VA: 0x759898e8bc
	public Group get_Item(String groupname) { }
	// RVA: 0x6376a98 VA: 0x759898ea98
	public IEnumerator GetEnumerator() { }
	// RVA: 0x6376b4c VA: 0x759898eb4c
	private IEnumerator`1 System.Collections.Generic.IEnumerable<System.Text.RegularExpressions.Group>.GetEnumerator() { }
	// RVA: 0x63767b8 VA: 0x759898e7b8
	private Group GetGroup(Int32 groupnum) { }
	// RVA: 0x6376bc4 VA: 0x759898ebc4
	private Group GetGroupImpl(Int32 groupnum) { }
	// RVA: 0x6376f1c VA: 0x759898ef1c
	public Boolean get_IsSynchronized() { }
	// RVA: 0x6376f24 VA: 0x759898ef24
	public Object get_SyncRoot() { }
	// RVA: 0x6376f2c VA: 0x759898ef2c
	public Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x6376fec VA: 0x759898efec
	public Void CopyTo(Group[] array, Int32 arrayIndex) { }
	// RVA: 0x6377178 VA: 0x759898f178
	private Int32 System.Collections.Generic.IList<System.Text.RegularExpressions.Group>.IndexOf(Group item) { }
	// RVA: 0x6377230 VA: 0x759898f230
	private Void System.Collections.Generic.IList<System.Text.RegularExpressions.Group>.Insert(Int32 index, Group item) { }
	// RVA: 0x6377280 VA: 0x759898f280
	private Void System.Collections.Generic.IList<System.Text.RegularExpressions.Group>.RemoveAt(Int32 index) { }
	// RVA: 0x63772d0 VA: 0x759898f2d0
	private Group System.Collections.Generic.IList<System.Text.RegularExpressions.Group>.get_Item(Int32 index) { }
	// RVA: 0x63772d4 VA: 0x759898f2d4
	private Void System.Collections.Generic.IList<System.Text.RegularExpressions.Group>.set_Item(Int32 index, Group value) { }
	// RVA: 0x6377324 VA: 0x759898f324
	private Void System.Collections.Generic.ICollection<System.Text.RegularExpressions.Group>.Add(Group item) { }
	// RVA: 0x6377374 VA: 0x759898f374
	private Void System.Collections.Generic.ICollection<System.Text.RegularExpressions.Group>.Clear() { }
	// RVA: 0x63773c4 VA: 0x759898f3c4
	private Boolean System.Collections.Generic.ICollection<System.Text.RegularExpressions.Group>.Contains(Group item) { }
	// RVA: 0x6377478 VA: 0x759898f478
	private Boolean System.Collections.Generic.ICollection<System.Text.RegularExpressions.Group>.Remove(Group item) { }
	// RVA: 0x63774c8 VA: 0x759898f4c8
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x6377518 VA: 0x759898f518
	private Void System.Collections.IList.Clear() { }
	// RVA: 0x6377568 VA: 0x759898f568
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x637765c VA: 0x759898f65c
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x6377750 VA: 0x759898f750
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x63777a0 VA: 0x759898f7a0
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x63777a8 VA: 0x759898f7a8
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x63777f8 VA: 0x759898f7f8
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
	// RVA: 0x6377848 VA: 0x759898f848
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x637784c VA: 0x759898f84c
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x637789c VA: 0x759898f89c
	internal Void .ctor() { }
}
```