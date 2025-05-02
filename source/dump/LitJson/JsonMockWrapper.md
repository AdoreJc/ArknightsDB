# JsonMockWrapper

**Namespace:** `LitJson`


## Properties

- `Boolean IsArray`

- `Boolean IsBoolean`

- `Boolean IsDouble`

- `Boolean IsInt`

- `Boolean IsLong`

- `Boolean IsObject`

- `Boolean IsString`


## Methods

- `Boolean get_IsArray()`

- `Boolean get_IsBoolean()`

- `Boolean get_IsDouble()`

- `Boolean get_IsInt()`

- `Boolean get_IsLong()`

- `Boolean get_IsObject()`

- `Boolean get_IsString()`

- `Boolean GetBoolean()`

- `Double GetDouble()`

- `Int32 GetInt()`

- `JsonType GetJsonType()`

- `Int64 GetLong()`

- `String GetString()`

- `Void SetBoolean(Boolean)`

- `Void SetDouble(Double)`

- `Void SetInt(Int32)`

- `Void SetJsonType(JsonType)`

- `Void SetLong(Int64)`

- `Void SetString(String)`

- `String ToJson()`

- `Void ToJson(JsonWriter)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : LitJson
public class JsonMockWrapper : IJsonWrapper, IList, ICollection, IEnumerable, IOrderedDictionary, IDictionary
{

	public Boolean IsArray { get; }
	public Boolean IsBoolean { get; }
	public Boolean IsDouble { get; }
	public Boolean IsInt { get; }
	public Boolean IsLong { get; }
	public Boolean IsObject { get; }
	public Boolean IsString { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Object System.Collections.IList.Item { get; set; }
	private Int32 System.Collections.ICollection.Count { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private Boolean System.Collections.IDictionary.IsFixedSize { get; }
	private Boolean System.Collections.IDictionary.IsReadOnly { get; }
	private ICollection System.Collections.IDictionary.Keys { get; }
	private ICollection System.Collections.IDictionary.Values { get; }
	private Object System.Collections.IDictionary.Item { get; set; }
	private Object LitJson.IOrderedDictionary.Item { get; set; }

	// RVA: 0x65f1394 VA: 0x7598c09394
	public Boolean get_IsArray() { }
	// RVA: 0x65f139c VA: 0x7598c0939c
	public Boolean get_IsBoolean() { }
	// RVA: 0x65f13a4 VA: 0x7598c093a4
	public Boolean get_IsDouble() { }
	// RVA: 0x65f13ac VA: 0x7598c093ac
	public Boolean get_IsInt() { }
	// RVA: 0x65f13b4 VA: 0x7598c093b4
	public Boolean get_IsLong() { }
	// RVA: 0x65f13bc VA: 0x7598c093bc
	public Boolean get_IsObject() { }
	// RVA: 0x65f13c4 VA: 0x7598c093c4
	public Boolean get_IsString() { }
	// RVA: 0x65f13cc VA: 0x7598c093cc
	public Boolean GetBoolean() { }
	// RVA: 0x65f13d4 VA: 0x7598c093d4
	public Double GetDouble() { }
	// RVA: 0x65f13dc VA: 0x7598c093dc
	public Int32 GetInt() { }
	// RVA: 0x65f13e4 VA: 0x7598c093e4
	public JsonType GetJsonType() { }
	// RVA: 0x65f13ec VA: 0x7598c093ec
	public Int64 GetLong() { }
	// RVA: 0x65f13f4 VA: 0x7598c093f4
	public String GetString() { }
	// RVA: 0x65f1434 VA: 0x7598c09434
	public Void SetBoolean(Boolean val) { }
	// RVA: 0x65f1438 VA: 0x7598c09438
	public Void SetDouble(Double val) { }
	// RVA: 0x65f143c VA: 0x7598c0943c
	public Void SetInt(Int32 val) { }
	// RVA: 0x65f1440 VA: 0x7598c09440
	public Void SetJsonType(JsonType type) { }
	// RVA: 0x65f1444 VA: 0x7598c09444
	public Void SetLong(Int64 val) { }
	// RVA: 0x65f1448 VA: 0x7598c09448
	public Void SetString(String val) { }
	// RVA: 0x65f144c VA: 0x7598c0944c
	public String ToJson() { }
	// RVA: 0x65f148c VA: 0x7598c0948c
	public Void ToJson(JsonWriter writer) { }
	// RVA: 0x65f1490 VA: 0x7598c09490
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x65f1498 VA: 0x7598c09498
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x65f14a0 VA: 0x7598c094a0
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x65f14a8 VA: 0x7598c094a8
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x65f14ac VA: 0x7598c094ac
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x65f14b4 VA: 0x7598c094b4
	private Void System.Collections.IList.Clear() { }
	// RVA: 0x65f14b8 VA: 0x7598c094b8
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x65f14c0 VA: 0x7598c094c0
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x65f14c8 VA: 0x7598c094c8
	private Void System.Collections.IList.Insert(Int32 i, Object v) { }
	// RVA: 0x65f14cc VA: 0x7598c094cc
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x65f14d0 VA: 0x7598c094d0
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
	// RVA: 0x65f14d4 VA: 0x7598c094d4
	private Int32 System.Collections.ICollection.get_Count() { }
	// RVA: 0x65f14dc VA: 0x7598c094dc
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x65f14e4 VA: 0x7598c094e4
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x65f14ec VA: 0x7598c094ec
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x65f14f0 VA: 0x7598c094f0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x65f14f8 VA: 0x7598c094f8
	private Boolean System.Collections.IDictionary.get_IsFixedSize() { }
	// RVA: 0x65f1500 VA: 0x7598c09500
	private Boolean System.Collections.IDictionary.get_IsReadOnly() { }
	// RVA: 0x65f1508 VA: 0x7598c09508
	private ICollection System.Collections.IDictionary.get_Keys() { }
	// RVA: 0x65f1510 VA: 0x7598c09510
	private ICollection System.Collections.IDictionary.get_Values() { }
	// RVA: 0x65f1518 VA: 0x7598c09518
	private Object System.Collections.IDictionary.get_Item(Object key) { }
	// RVA: 0x65f1520 VA: 0x7598c09520
	private Void System.Collections.IDictionary.set_Item(Object key, Object value) { }
	// RVA: 0x65f1524 VA: 0x7598c09524
	private Void System.Collections.IDictionary.Add(Object k, Object v) { }
	// RVA: 0x65f1528 VA: 0x7598c09528
	private Void System.Collections.IDictionary.Clear() { }
	// RVA: 0x65f152c VA: 0x7598c0952c
	private Boolean System.Collections.IDictionary.Contains(Object key) { }
	// RVA: 0x65f1534 VA: 0x7598c09534
	private Void System.Collections.IDictionary.Remove(Object key) { }
	// RVA: 0x65f1538 VA: 0x7598c09538
	private IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() { }
	// RVA: 0x65f1540 VA: 0x7598c09540
	private Object LitJson.IOrderedDictionary.get_Item(Int32 idx) { }
	// RVA: 0x65f1548 VA: 0x7598c09548
	private Void LitJson.IOrderedDictionary.set_Item(Int32 idx, Object value) { }
	// RVA: 0x65f154c VA: 0x7598c0954c
	private IDictionaryEnumerator LitJson.IOrderedDictionary.GetEnumerator() { }
	// RVA: 0x65f1554 VA: 0x7598c09554
	private Void LitJson.IOrderedDictionary.Insert(Int32 i, Object k, Object v) { }
	// RVA: 0x65f1558 VA: 0x7598c09558
	private Void LitJson.IOrderedDictionary.RemoveAt(Int32 i) { }
	// RVA: 0x65f0180 VA: 0x7598c08180
	public Void .ctor() { }
}
```