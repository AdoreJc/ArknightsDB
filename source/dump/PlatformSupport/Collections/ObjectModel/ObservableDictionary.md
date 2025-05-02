# ObservableDictionary

**Namespace:** `PlatformSupport.Collections.ObjectModel`


## Fields

- `NotifyCollectionChangedEventHandler CollectionChanged`

- `PropertyChangedEventHandler PropertyChanged`


## Properties

- `TValue Item`

- `Int32 Count`

- `Boolean IsReadOnly`


## Methods

- `Void Add(TKey, TValue)`

- `Boolean ContainsKey(TKey)`

- `Boolean Remove(TKey)`

- `Boolean TryGetValue(TKey, out)`

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Void Add(KeyValuePair`2)`

- `Void Clear()`

- `Boolean Contains(KeyValuePair`2)`

- `Void CopyTo(KeyValuePair`2[], Int32)`

- `Int32 get_Count()`

- `Boolean get_IsReadOnly()`

- `Boolean Remove(KeyValuePair`2)`

- `Void add_CollectionChanged(NotifyCollectionChangedEventHandler)`

- `Void remove_CollectionChanged(NotifyCollectionChangedEventHandler)`

- `Void add_PropertyChanged(PropertyChangedEventHandler)`

- `Void remove_PropertyChanged(PropertyChangedEventHandler)`

- `Void AddRange(IDictionary`2)`

- `Void Insert(TKey, TValue, Boolean)`

- `Void OnPropertyChanged()`

- `Void OnCollectionChanged()`

- `Void OnCollectionChanged(NotifyCollectionChangedAction, KeyValuePair`2)`

- `Void OnCollectionChanged(NotifyCollectionChangedAction, KeyValuePair`2, KeyValuePair`2)`

- `Void OnCollectionChanged(NotifyCollectionChangedAction, IList)`

- `Boolean <AddRange>b__41_0(TKey)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : PlatformSupport.Collections.ObjectModel
public class ObservableDictionary`2 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable, INotifyCollectionChanged, INotifyPropertyChanged
{
	private const String CountString; // 0x0
	private const String IndexerName; // 0x0
	private const String KeysName; // 0x0
	private const String ValuesName; // 0x0
	private IDictionary`2 _Dictionary; // 0x0
	private NotifyCollectionChangedEventHandler CollectionChanged; // 0x0
	private PropertyChangedEventHandler PropertyChanged; // 0x0

	protected IDictionary`2 Dictionary { get; }
	public ICollection`1 Keys { get; }
	public ICollection`1 Values { get; }
	public TValue Item { get; set; }
	public Int32 Count { get; }
	public Boolean IsReadOnly { get; }

	// RVA: 0x VA: 0x0
	protected IDictionary`2 get_Dictionary() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IDictionary`2 dictionary) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IDictionary`2 dictionary, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Keys() { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Values() { }
	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Add(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(KeyValuePair`2[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Void add_CollectionChanged(NotifyCollectionChangedEventHandler value) { }
	// RVA: 0x VA: 0x0
	public Void remove_CollectionChanged(NotifyCollectionChangedEventHandler value) { }
	// RVA: 0x VA: 0x0
	public Void add_PropertyChanged(PropertyChangedEventHandler value) { }
	// RVA: 0x VA: 0x0
	public Void remove_PropertyChanged(PropertyChangedEventHandler value) { }
	// RVA: 0x VA: 0x0
	public Void AddRange(IDictionary`2 items) { }
	// RVA: 0x VA: 0x0
	private Void Insert(TKey key, TValue value, Boolean add) { }
	// RVA: 0x VA: 0x0
	private Void OnPropertyChanged() { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnPropertyChanged(String propertyName) { }
	// RVA: 0x VA: 0x0
	private Void OnCollectionChanged() { }
	// RVA: 0x VA: 0x0
	private Void OnCollectionChanged(NotifyCollectionChangedAction action, KeyValuePair`2 changedItem) { }
	// RVA: 0x VA: 0x0
	private Void OnCollectionChanged(NotifyCollectionChangedAction action, KeyValuePair`2 newItem, KeyValuePair`2 oldItem) { }
	// RVA: 0x VA: 0x0
	private Void OnCollectionChanged(NotifyCollectionChangedAction action, IList newItems) { }
	// RVA: 0x VA: 0x0
	private Boolean <AddRange>b__41_0(TKey k) { }
}
```