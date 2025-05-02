# HashSet

**Namespace:** `System.Collections.Generic`


## Fields

- `Int32 _count`

- `Int32 _lastIndex`

- `Int32 _freeList`

- `Int32 _version`

- `SerializationInfo _siInfo`


## Properties

- `Int32 Count`


## Methods

- `Void CopyFrom(HashSet`1)`

- `Void Clear()`

- `Boolean Contains(T)`

- `Void CopyTo(T[], Int32)`

- `Boolean Remove(T)`

- `Int32 get_Count()`

- `Enumerator GetEnumerator()`

- `Boolean Add(T)`

- `Void UnionWith(IEnumerable`1)`

- `Void SymmetricExceptWith(IEnumerable`1)`

- `Boolean IsSubsetOf(IEnumerable`1)`

- `Boolean SetEquals(IEnumerable`1)`

- `Void CopyTo(T[])`

- `Void CopyTo(T[], Int32, Int32)`

- `Int32 RemoveWhere(Predicate`1)`

- `Void TrimExcess()`

- `Int32 Initialize(Int32)`

- `Void IncreaseCapacity()`

- `Void SetCapacity(Int32)`

- `Boolean AddIfNotPresent(T)`

- `Void AddValue(Int32, Int32, T)`

- `Boolean ContainsAllElements(IEnumerable`1)`

- `Boolean IsSubsetOfHashSetWithSameEC(HashSet`1)`

- `Int32 InternalIndexOf(T)`

- `Void SymmetricExceptWithUniqueHashSet(HashSet`1)`

- `Void SymmetricExceptWithEnumerable(IEnumerable`1)`

- `Boolean AddOrGetLocation(T, out)`

- `ElementCount CheckUniqueAndUnfoundElements(IEnumerable`1, Boolean)`

- `Int32 InternalGetHashCode(T)`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Collections.Generic
public class HashSet`1 : ICollection`1, IEnumerable`1, IEnumerable, IReadOnlyCollection`1, ISerializable, IDeserializationCallback
{
	private const Int32 Lower31BitMask; // 0x0
	private const Int32 StackAllocThreshold; // 0x0
	private const Int32 ShrinkThreshold; // 0x0
	private const String CapacityName; // 0x0
	private const String ElementsName; // 0x0
	private const String ComparerName; // 0x0
	private const String VersionName; // 0x0
	private Int32[] _buckets; // 0x0
	private Slot[] _slots; // 0x0
	private Int32 _count; // 0x0
	private Int32 _lastIndex; // 0x0
	private Int32 _freeList; // 0x0
	private IEqualityComparer`1 _comparer; // 0x0
	private Int32 _version; // 0x0
	private SerializationInfo _siInfo; // 0x0

	public Int32 Count { get; }
	private Boolean System.Collections.Generic.ICollection<T>.IsReadOnly { get; }
	public IEqualityComparer`1 Comparer { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEnumerable`1 collection, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	private Void CopyFrom(HashSet`1 source) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<T>.Add(T item) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<T>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public Enumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<T>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	public virtual Void OnDeserialization(Object sender) { }
	// RVA: 0x VA: 0x0
	public Boolean Add(T item) { }
	// RVA: 0x VA: 0x0
	public Void UnionWith(IEnumerable`1 other) { }
	// RVA: 0x VA: 0x0
	public Void SymmetricExceptWith(IEnumerable`1 other) { }
	// RVA: 0x VA: 0x0
	public Boolean IsSubsetOf(IEnumerable`1 other) { }
	// RVA: 0x VA: 0x0
	public Boolean SetEquals(IEnumerable`1 other) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 arrayIndex, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Int32 RemoveWhere(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public IEqualityComparer`1 get_Comparer() { }
	// RVA: 0x VA: 0x0
	public Void TrimExcess() { }
	// RVA: 0x VA: 0x0
	private Int32 Initialize(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	private Void IncreaseCapacity() { }
	// RVA: 0x VA: 0x0
	private Void SetCapacity(Int32 newSize) { }
	// RVA: 0x VA: 0x0
	private Boolean AddIfNotPresent(T value) { }
	// RVA: 0x VA: 0x0
	private Void AddValue(Int32 index, Int32 hashCode, T value) { }
	// RVA: 0x VA: 0x0
	private Boolean ContainsAllElements(IEnumerable`1 other) { }
	// RVA: 0x VA: 0x0
	private Boolean IsSubsetOfHashSetWithSameEC(HashSet`1 other) { }
	// RVA: 0x VA: 0x0
	private Int32 InternalIndexOf(T item) { }
	// RVA: 0x VA: 0x0
	private Void SymmetricExceptWithUniqueHashSet(HashSet`1 other) { }
	// RVA: 0x VA: 0x0
	private Void SymmetricExceptWithEnumerable(IEnumerable`1 other) { }
	// RVA: 0x VA: 0x0
	private Boolean AddOrGetLocation(T value, out Int32 location) { }
	// RVA: 0x VA: 0x0
	private ElementCount CheckUniqueAndUnfoundElements(IEnumerable`1 other, Boolean returnIfUnfound) { }
	// RVA: 0x VA: 0x0
	private static Boolean AreEqualityComparersEqual(HashSet`1 set1, HashSet`1 set2) { }
	// RVA: 0x VA: 0x0
	private Int32 InternalGetHashCode(T item) { }
}
```