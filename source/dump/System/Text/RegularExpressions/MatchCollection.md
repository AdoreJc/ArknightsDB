# MatchCollection

**Namespace:** `System.Text.RegularExpressions`


## Fields

- `Boolean _done`

- `Int32 _startat`

- `Int32 _prevlen`


## Properties

- `Boolean IsReadOnly`

- `Int32 Count`

- `Boolean IsSynchronized`

- `Object SyncRoot`


## Methods

- `Boolean get_IsReadOnly()`

- `Int32 get_Count()`

- `IEnumerator GetEnumerator()`

- `Match GetMatch(Int32)`

- `Void EnsureInitialized()`

- `Boolean get_IsSynchronized()`

- `Object get_SyncRoot()`

- `Void CopyTo(Array, Int32)`

- `Void CopyTo(Match[], Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Text.RegularExpressions
public class MatchCollection : IList`1, ICollection`1, IEnumerable`1, IEnumerable, IReadOnlyList`1, IReadOnlyCollection`1, IList, ICollection
{
	private readonly Regex _regex; // 0x10
	private readonly List`1 _matches; // 0x18
	private Boolean _done; // 0x20
	private readonly String _input; // 0x28
	private readonly Int32 _beginning; // 0x30
	private readonly Int32 _length; // 0x34
	private Int32 _startat; // 0x38
	private Int32 _prevlen; // 0x3c

	public Boolean IsReadOnly { get; }
	public Int32 Count { get; }
	public virtual Match Item { get; }
	public Boolean IsSynchronized { get; }
	public Object SyncRoot { get; }
	private Match System.Collections.Generic.IList<System.Text.RegularExpressions.Match>.Item { get; set; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Object System.Collections.IList.Item { get; set; }

	// RVA: 0x63789c8 VA: 0x75989909c8
	internal Void .ctor(Regex regex, String input, Int32 beginning, Int32 length, Int32 startat) { }
	// RVA: 0x6378b20 VA: 0x7598990b20
	public Boolean get_IsReadOnly() { }
	// RVA: 0x6378b28 VA: 0x7598990b28
	public Int32 get_Count() { }
	// RVA: 0x6378b98 VA: 0x7598990b98
	public virtual Match get_Item(Int32 i) { }
	// RVA: 0x6378d74 VA: 0x7598990d74
	public IEnumerator GetEnumerator() { }
	// RVA: 0x6378e28 VA: 0x7598990e28
	private IEnumerator`1 System.Collections.Generic.IEnumerable<System.Text.RegularExpressions.Match>.GetEnumerator() { }
	// RVA: 0x6378bfc VA: 0x7598990bfc
	private Match GetMatch(Int32 i) { }
	// RVA: 0x6378b84 VA: 0x7598990b84
	private Void EnsureInitialized() { }
	// RVA: 0x6378ea0 VA: 0x7598990ea0
	public Boolean get_IsSynchronized() { }
	// RVA: 0x6378ea8 VA: 0x7598990ea8
	public Object get_SyncRoot() { }
	// RVA: 0x6378eac VA: 0x7598990eac
	public Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x6378f78 VA: 0x7598990f78
	public Void CopyTo(Match[] array, Int32 arrayIndex) { }
	// RVA: 0x6378ff4 VA: 0x7598990ff4
	private Int32 System.Collections.Generic.IList<System.Text.RegularExpressions.Match>.IndexOf(Match item) { }
	// RVA: 0x6379060 VA: 0x7598991060
	private Void System.Collections.Generic.IList<System.Text.RegularExpressions.Match>.Insert(Int32 index, Match item) { }
	// RVA: 0x63790b0 VA: 0x75989910b0
	private Void System.Collections.Generic.IList<System.Text.RegularExpressions.Match>.RemoveAt(Int32 index) { }
	// RVA: 0x6379100 VA: 0x7598991100
	private Match System.Collections.Generic.IList<System.Text.RegularExpressions.Match>.get_Item(Int32 index) { }
	// RVA: 0x6379110 VA: 0x7598991110
	private Void System.Collections.Generic.IList<System.Text.RegularExpressions.Match>.set_Item(Int32 index, Match value) { }
	// RVA: 0x6379160 VA: 0x7598991160
	private Void System.Collections.Generic.ICollection<System.Text.RegularExpressions.Match>.Add(Match item) { }
	// RVA: 0x63791b0 VA: 0x75989911b0
	private Void System.Collections.Generic.ICollection<System.Text.RegularExpressions.Match>.Clear() { }
	// RVA: 0x6379200 VA: 0x7598991200
	private Boolean System.Collections.Generic.ICollection<System.Text.RegularExpressions.Match>.Contains(Match item) { }
	// RVA: 0x637926c VA: 0x759899126c
	private Boolean System.Collections.Generic.ICollection<System.Text.RegularExpressions.Match>.Remove(Match item) { }
	// RVA: 0x63792bc VA: 0x75989912bc
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x637930c VA: 0x759899130c
	private Void System.Collections.IList.Clear() { }
	// RVA: 0x637935c VA: 0x759899135c
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x6379450 VA: 0x7598991450
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x6379544 VA: 0x7598991544
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x6379594 VA: 0x7598991594
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x637959c VA: 0x759899159c
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x63795ec VA: 0x75989915ec
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
	// RVA: 0x637963c VA: 0x759899163c
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x637964c VA: 0x759899164c
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x637969c VA: 0x759899169c
	internal Void .ctor() { }
}
```