# PropertyDescriptorCollection

**Namespace:** `System.ComponentModel`


## Fields

- `IDictionary _cachedFoundProperties`

- `Boolean _cachedIgnoreCase`

- `Boolean _propsOwned`

- `Boolean _needSort`

- `Boolean _readOnly`

- `Int32 <Count>k__BackingField`


## Properties

- `Int32 Count`


## Methods

- `Int32 get_Count()`

- `Void set_Count(Int32)`

- `Int32 Add(PropertyDescriptor)`

- `Void Clear()`

- `Boolean Contains(PropertyDescriptor)`

- `Void CopyTo(Array, Int32)`

- `Void EnsurePropsOwned()`

- `Void EnsureSize(Int32)`

- `Int32 IndexOf(PropertyDescriptor)`

- `Void Insert(Int32, PropertyDescriptor)`

- `Void Remove(PropertyDescriptor)`

- `Void RemoveAt(Int32)`

- `Void InternalSort(String[])`

- `Void InternalSort(IComparer)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class PropertyDescriptorCollection : ICollection, IEnumerable, IList, IDictionary
{
	public static readonly PropertyDescriptorCollection Empty; // 0x0
	private IDictionary _cachedFoundProperties; // 0x10
	private Boolean _cachedIgnoreCase; // 0x18
	private PropertyDescriptor[] _properties; // 0x20
	private readonly String[] _namedSort; // 0x28
	private readonly IComparer _comparer; // 0x30
	private Boolean _propsOwned; // 0x38
	private Boolean _needSort; // 0x39
	private Boolean _readOnly; // 0x3a
	private readonly Object _internalSyncObject; // 0x40
	private Int32 <Count>k__BackingField; // 0x48

	public Int32 Count { get; set; }
	public virtual PropertyDescriptor Item { get; }
	public virtual PropertyDescriptor Item { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private Int32 System.Collections.ICollection.Count { get; }
	private Boolean System.Collections.IDictionary.IsFixedSize { get; }
	private Boolean System.Collections.IDictionary.IsReadOnly { get; }
	private Object System.Collections.IDictionary.Item { get; set; }
	private ICollection System.Collections.IDictionary.Keys { get; }
	private ICollection System.Collections.IDictionary.Values { get; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Object System.Collections.IList.Item { get; set; }

	// RVA: 0x63d228c VA: 0x75989ea28c
	public Void .ctor(PropertyDescriptor[] properties) { }
	// RVA: 0x63d239c VA: 0x75989ea39c
	public Void .ctor(PropertyDescriptor[] properties, Boolean readOnly) { }
	// RVA: 0x63d23c0 VA: 0x75989ea3c0
	private Void .ctor(PropertyDescriptor[] properties, Int32 propCount, String[] namedSort, IComparer comparer) { }
	// RVA: 0x63d2514 VA: 0x75989ea514
	public Int32 get_Count() { }
	// RVA: 0x63d251c VA: 0x75989ea51c
	private Void set_Count(Int32 value) { }
	// RVA: 0x63d2524 VA: 0x75989ea524
	public virtual PropertyDescriptor get_Item(Int32 index) { }
	// RVA: 0x63d266c VA: 0x75989ea66c
	public virtual PropertyDescriptor get_Item(String name) { }
	// RVA: 0x63d2680 VA: 0x75989ea680
	public Int32 Add(PropertyDescriptor value) { }
	// RVA: 0x63d2878 VA: 0x75989ea878
	public Void Clear() { }
	// RVA: 0x63d28d4 VA: 0x75989ea8d4
	public Boolean Contains(PropertyDescriptor value) { }
	// RVA: 0x63d294c VA: 0x75989ea94c
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x63d25b0 VA: 0x75989ea5b0
	private Void EnsurePropsOwned() { }
	// RVA: 0x63d2758 VA: 0x75989ea758
	private Void EnsureSize(Int32 sizeNeeded) { }
	// RVA: 0x63d2bfc VA: 0x75989eabfc
	public virtual PropertyDescriptor Find(String name, Boolean ignoreCase) { }
	// RVA: 0x63d28ec VA: 0x75989ea8ec
	public Int32 IndexOf(PropertyDescriptor value) { }
	// RVA: 0x63d313c VA: 0x75989eb13c
	public Void Insert(Int32 index, PropertyDescriptor value) { }
	// RVA: 0x63d3234 VA: 0x75989eb234
	public Void Remove(PropertyDescriptor value) { }
	// RVA: 0x63d32a4 VA: 0x75989eb2a4
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x63d3368 VA: 0x75989eb368
	public virtual PropertyDescriptorCollection Sort() { }
	// RVA: 0x63d33e8 VA: 0x75989eb3e8
	public virtual PropertyDescriptorCollection Sort(String[] names) { }
	// RVA: 0x63d346c VA: 0x75989eb46c
	public virtual PropertyDescriptorCollection Sort(String[] names, IComparer comparer) { }
	// RVA: 0x63d34f0 VA: 0x75989eb4f0
	public virtual PropertyDescriptorCollection Sort(IComparer comparer) { }
	// RVA: 0x63d2988 VA: 0x75989ea988
	protected Void InternalSort(String[] names) { }
	// RVA: 0x63d3574 VA: 0x75989eb574
	protected Void InternalSort(IComparer sorter) { }
	// RVA: 0x63d35ec VA: 0x75989eb5ec
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x63d3688 VA: 0x75989eb688
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x63d3690 VA: 0x75989eb690
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x63d3698 VA: 0x75989eb698
	private Int32 System.Collections.ICollection.get_Count() { }
	// RVA: 0x63d36a0 VA: 0x75989eb6a0
	private Void System.Collections.IList.Clear() { }
	// RVA: 0x63d36a4 VA: 0x75989eb6a4
	private Void System.Collections.IDictionary.Clear() { }
	// RVA: 0x63d36a8 VA: 0x75989eb6a8
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x63d36b8 VA: 0x75989eb6b8
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
	// RVA: 0x63d36bc VA: 0x75989eb6bc
	private Void System.Collections.IDictionary.Add(Object key, Object value) { }
	// RVA: 0x63d3784 VA: 0x75989eb784
	private Boolean System.Collections.IDictionary.Contains(Object key) { }
	// RVA: 0x63d3804 VA: 0x75989eb804
	private IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() { }
	// RVA: 0x63d38b4 VA: 0x75989eb8b4
	private Boolean System.Collections.IDictionary.get_IsFixedSize() { }
	// RVA: 0x63d38bc VA: 0x75989eb8bc
	private Boolean System.Collections.IDictionary.get_IsReadOnly() { }
	// RVA: 0x63d38c4 VA: 0x75989eb8c4
	private Object System.Collections.IDictionary.get_Item(Object key) { }
	// RVA: 0x63d3940 VA: 0x75989eb940
	private Void System.Collections.IDictionary.set_Item(Object key, Object value) { }
	// RVA: 0x63d3d10 VA: 0x75989ebd10
	private ICollection System.Collections.IDictionary.get_Keys() { }
	// RVA: 0x63d3e20 VA: 0x75989ebe20
	private ICollection System.Collections.IDictionary.get_Values() { }
	// RVA: 0x63d3ef8 VA: 0x75989ebef8
	private Void System.Collections.IDictionary.Remove(Object key) { }
	// RVA: 0x63d3fec VA: 0x75989ebfec
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x63d4070 VA: 0x75989ec070
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x63d4100 VA: 0x75989ec100
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x63d4184 VA: 0x75989ec184
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x63d4218 VA: 0x75989ec218
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x63d4220 VA: 0x75989ec220
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x63d4228 VA: 0x75989ec228
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x63d42ac VA: 0x75989ec2ac
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x63d42bc VA: 0x75989ec2bc
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x63d44a0 VA: 0x75989ec4a0
	private static Void .cctor() { }
}
```