# MessageDictionary

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `IDictionary _internalProperties`

- `IMethodMessage _message`

- `Boolean _ownProperties`


## Properties

- `Boolean IsFixedSize`

- `Boolean IsReadOnly`

- `Object Item`

- `ICollection Keys`

- `ICollection Values`

- `Int32 Count`

- `Boolean IsSynchronized`

- `Object SyncRoot`


## Methods

- `Void set_MethodKeys(String[])`

- `IDictionary GetInternalProperties()`

- `Boolean IsOverridenKey(String)`

- `Boolean get_IsFixedSize()`

- `Boolean get_IsReadOnly()`

- `Object get_Item(Object)`

- `Void set_Item(Object, Object)`

- `ICollection get_Keys()`

- `ICollection get_Values()`

- `Void Add(Object, Object)`

- `Void Clear()`

- `Boolean Contains(Object)`

- `Void Remove(Object)`

- `Int32 get_Count()`

- `Boolean get_IsSynchronized()`

- `Object get_SyncRoot()`

- `Void CopyTo(Array, Int32)`

- `IDictionaryEnumerator GetEnumerator()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class MessageDictionary : IDictionary, ICollection, IEnumerable
{
	private IDictionary _internalProperties; // 0x10
	protected IMethodMessage _message; // 0x18
	private String[] _methodKeys; // 0x20
	private Boolean _ownProperties; // 0x28

	internal IDictionary InternalDictionary { get; }
	public String[] MethodKeys { set; }
	public Boolean IsFixedSize { get; }
	public Boolean IsReadOnly { get; }
	public Object Item { get; set; }
	public ICollection Keys { get; }
	public ICollection Values { get; }
	public Int32 Count { get; }
	public Boolean IsSynchronized { get; }
	public Object SyncRoot { get; }

	// RVA: 0x5fa53a4 VA: 0x75985bd3a4
	public Void .ctor(IMethodMessage message) { }
	// RVA: 0x5fa2064 VA: 0x75985ba064
	internal Boolean HasUserData() { }
	// RVA: 0x5fa2160 VA: 0x75985ba160
	internal IDictionary get_InternalDictionary() { }
	// RVA: 0x5fa7dac VA: 0x75985bfdac
	public Void set_MethodKeys(String[] value) { }
	// RVA: 0x5fa7db4 VA: 0x75985bfdb4
	protected virtual IDictionary AllocInternalProperties() { }
	// RVA: 0x5fa4444 VA: 0x75985bc444
	public IDictionary GetInternalProperties() { }
	// RVA: 0x5fa7e1c VA: 0x75985bfe1c
	private Boolean IsOverridenKey(String key) { }
	// RVA: 0x5fa7ea8 VA: 0x75985bfea8
	public Boolean get_IsFixedSize() { }
	// RVA: 0x5fa7eb0 VA: 0x75985bfeb0
	public Boolean get_IsReadOnly() { }
	// RVA: 0x5fa7eb8 VA: 0x75985bfeb8
	public Object get_Item(Object key) { }
	// RVA: 0x5fa8004 VA: 0x75985c0004
	public Void set_Item(Object key, Object value) { }
	// RVA: 0x5fa5780 VA: 0x75985bd780
	protected virtual Object GetMethodProperty(String key) { }
	// RVA: 0x5fa5f2c VA: 0x75985bdf2c
	protected virtual Void SetMethodProperty(String key, Object value) { }
	// RVA: 0x5fa8188 VA: 0x75985c0188
	public ICollection get_Keys() { }
	// RVA: 0x5fa85bc VA: 0x75985c05bc
	public ICollection get_Values() { }
	// RVA: 0x5fa8008 VA: 0x75985c0008
	public Void Add(Object key, Object value) { }
	// RVA: 0x5fa89dc VA: 0x75985c09dc
	public Void Clear() { }
	// RVA: 0x5fa8a88 VA: 0x75985c0a88
	public Boolean Contains(Object key) { }
	// RVA: 0x5fa8bd0 VA: 0x75985c0bd0
	public Void Remove(Object key) { }
	// RVA: 0x5fa8d58 VA: 0x75985c0d58
	public Int32 get_Count() { }
	// RVA: 0x5fa8e20 VA: 0x75985c0e20
	public Boolean get_IsSynchronized() { }
	// RVA: 0x5fa8e28 VA: 0x75985c0e28
	public Object get_SyncRoot() { }
	// RVA: 0x5fa8e2c VA: 0x75985c0e2c
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x5fa8eec VA: 0x75985c0eec
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x5fa9050 VA: 0x75985c1050
	public IDictionaryEnumerator GetEnumerator() { }
}
```