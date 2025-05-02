# Hashtable

**Namespace:** `System.Collections`


## Fields

- `Int32 _count`

- `Int32 _occupancy`

- `Int32 _loadsize`

- `Single _loadFactor`

- `Int32 _version`

- `Boolean _isWriterInProgress`

- `ICollection _keys`

- `ICollection _values`

- `IEqualityComparer _keycomparer`

- `Object _syncRoot`


## Methods

- `UInt32 InitHash(Object, Int32, out, out)`

- `Void CopyKeys(Array, Int32)`

- `Void CopyEntries(Array, Int32)`

- `Void CopyValues(Array, Int32)`

- `Void expand()`

- `Void rehash()`

- `Void UpdateVersion()`

- `Void rehash(Int32)`

- `Void Insert(Object, Object, Boolean)`

- `Void putEntry(bucket[], Object, Object, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections
public class Hashtable : IDictionary, ICollection, IEnumerable, ISerializable, IDeserializationCallback, ICloneable
{
	internal const Int32 HashPrime; // 0x0
	private const Int32 InitialSize; // 0x0
	private const String LoadFactorName; // 0x0
	private const String VersionName; // 0x0
	private const String ComparerName; // 0x0
	private const String HashCodeProviderName; // 0x0
	private const String HashSizeName; // 0x0
	private const String KeysName; // 0x0
	private const String ValuesName; // 0x0
	private const String KeyComparerName; // 0x0
	private bucket[] _buckets; // 0x10
	private Int32 _count; // 0x18
	private Int32 _occupancy; // 0x1c
	private Int32 _loadsize; // 0x20
	private Single _loadFactor; // 0x24
	private Int32 _version; // 0x28
	private Boolean _isWriterInProgress; // 0x2c
	private ICollection _keys; // 0x30
	private ICollection _values; // 0x38
	private IEqualityComparer _keycomparer; // 0x40
	private Object _syncRoot; // 0x48
	private static ConditionalWeakTable`2 s_serializationInfoTable; // 0x0

	private static ConditionalWeakTable`2 SerializationInfoTable { get; }
	public virtual Object Item { get; set; }
	public virtual Boolean IsReadOnly { get; }
	public virtual Boolean IsFixedSize { get; }
	public virtual Boolean IsSynchronized { get; }
	public virtual ICollection Keys { get; }
	public virtual ICollection Values { get; }
	public virtual Object SyncRoot { get; }
	public virtual Int32 Count { get; }

	// RVA: 0x6087a04 VA: 0x759869fa04
	private static ConditionalWeakTable`2 get_SerializationInfoTable() { }
	// RVA: 0x6087a60 VA: 0x759869fa60
	internal Void .ctor(Boolean trash) { }
	// RVA: 0x6087a68 VA: 0x759869fa68
	public Void .ctor() { }
	// RVA: 0x6087d2c VA: 0x759869fd2c
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x6087a74 VA: 0x759869fa74
	public Void .ctor(Int32 capacity, Single loadFactor) { }
	// RVA: 0x6087d34 VA: 0x759869fd34
	public Void .ctor(Int32 capacity, Single loadFactor, IEqualityComparer equalityComparer) { }
	// RVA: 0x6087d60 VA: 0x759869fd60
	public Void .ctor(IEqualityComparer equalityComparer) { }
	// RVA: 0x6087d94 VA: 0x759869fd94
	public Void .ctor(Int32 capacity, IEqualityComparer equalityComparer) { }
	// RVA: 0x6087dc4 VA: 0x759869fdc4
	public Void .ctor(IDictionary d) { }
	// RVA: 0x6087dd0 VA: 0x759869fdd0
	public Void .ctor(IDictionary d, Single loadFactor) { }
	// RVA: 0x6087dd8 VA: 0x759869fdd8
	public Void .ctor(IDictionary d, Single loadFactor, IEqualityComparer equalityComparer) { }
	// RVA: 0x6088108 VA: 0x75986a0108
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6088170 VA: 0x75986a0170
	private UInt32 InitHash(Object key, Int32 hashsize, out UInt32 seed, out UInt32 incr) { }
	// RVA: 0x60881c4 VA: 0x75986a01c4
	public virtual Void Add(Object key, Object value) { }
	// RVA: 0x6088638 VA: 0x75986a0638
	public virtual Void Clear() { }
	// RVA: 0x6088738 VA: 0x75986a0738
	public virtual Object Clone() { }
	// RVA: 0x608885c VA: 0x75986a085c
	public virtual Boolean Contains(Object key) { }
	// RVA: 0x608886c VA: 0x75986a086c
	public virtual Boolean ContainsKey(Object key) { }
	// RVA: 0x60889d4 VA: 0x75986a09d4
	private Void CopyKeys(Array array, Int32 arrayIndex) { }
	// RVA: 0x6088a78 VA: 0x75986a0a78
	private Void CopyEntries(Array array, Int32 arrayIndex) { }
	// RVA: 0x6088ba0 VA: 0x75986a0ba0
	public virtual Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x6088d50 VA: 0x75986a0d50
	private Void CopyValues(Array array, Int32 arrayIndex) { }
	// RVA: 0x6088e00 VA: 0x75986a0e00
	public virtual Object get_Item(Object key) { }
	// RVA: 0x6089024 VA: 0x75986a1024
	public virtual Void set_Item(Object key, Object value) { }
	// RVA: 0x608902c VA: 0x75986a102c
	private Void expand() { }
	// RVA: 0x60891d4 VA: 0x75986a11d4
	private Void rehash() { }
	// RVA: 0x608870c VA: 0x75986a070c
	private Void UpdateVersion() { }
	// RVA: 0x6089098 VA: 0x75986a1098
	private Void rehash(Int32 newsize) { }
	// RVA: 0x60892f0 VA: 0x75986a12f0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x60893b8 VA: 0x75986a13b8
	public virtual IDictionaryEnumerator GetEnumerator() { }
	// RVA: 0x608941c VA: 0x75986a141c
	protected virtual Int32 GetHash(Object key) { }
	// RVA: 0x60894e4 VA: 0x75986a14e4
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x60894ec VA: 0x75986a14ec
	public virtual Boolean get_IsFixedSize() { }
	// RVA: 0x60894f4 VA: 0x75986a14f4
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x60894fc VA: 0x75986a14fc
	protected virtual Boolean KeyEquals(Object item, Object key) { }
	// RVA: 0x6089604 VA: 0x75986a1604
	public virtual ICollection get_Keys() { }
	// RVA: 0x60896c0 VA: 0x75986a16c0
	public virtual ICollection get_Values() { }
	// RVA: 0x60881cc VA: 0x75986a01cc
	private Void Insert(Object key, Object nvalue, Boolean add) { }
	// RVA: 0x60891f0 VA: 0x75986a11f0
	private Void putEntry(bucket[] newBuckets, Object key, Object nvalue, Int32 hashcode) { }
	// RVA: 0x608977c VA: 0x75986a177c
	public virtual Void Remove(Object key) { }
	// RVA: 0x6089988 VA: 0x75986a1988
	public virtual Object get_SyncRoot() { }
	// RVA: 0x6089a00 VA: 0x75986a1a00
	public virtual Int32 get_Count() { }
	// RVA: 0x6089a08 VA: 0x75986a1a08
	public static Hashtable Synchronized(Hashtable table) { }
	// RVA: 0x6089af8 VA: 0x75986a1af8
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x608a034 VA: 0x75986a2034
	public virtual Void OnDeserialization(Object sender) { }
}
```