# JsonData

**Namespace:** `LitJson`


## Fields

- `Boolean inst_boolean`

- `Double inst_double`

- `Int32 inst_int`

- `Int64 inst_long`

- `String inst_string`

- `String json`

- `JsonType type`


## Properties

- `Int32 Count`

- `Boolean IsArray`

- `Boolean IsBoolean`

- `Boolean IsDouble`

- `Boolean IsInt`

- `Boolean IsLong`

- `Boolean IsObject`

- `Boolean IsString`

- `JsonData Item`

- `JsonData Item`


## Methods

- `Int32 get_Count()`

- `Boolean get_IsArray()`

- `Boolean get_IsBoolean()`

- `Boolean get_IsDouble()`

- `Boolean get_IsInt()`

- `Boolean get_IsLong()`

- `Boolean get_IsObject()`

- `Boolean get_IsString()`

- `JsonData get_Item(String)`

- `Void set_Item(String, JsonData)`

- `JsonData get_Item(Int32)`

- `Void set_Item(Int32, JsonData)`

- `ICollection EnsureCollection()`

- `IDictionary EnsureDictionary()`

- `IList EnsureList()`

- `JsonData ToJsonData(Object)`

- `Int32 Add(Object)`

- `Void Clear()`

- `Boolean Equals(JsonData)`

- `JsonType GetJsonType()`

- `Void SetJsonType(JsonType)`

- `String ToJson()`

- `Void ToJson(JsonWriter)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : LitJson
public class JsonData : IJsonWrapper, IList, ICollection, IEnumerable, IOrderedDictionary, IDictionary, IEquatable`1
{
	private IList`1 inst_array; // 0x10
	private Boolean inst_boolean; // 0x18
	private Double inst_double; // 0x20
	private Int32 inst_int; // 0x28
	private Int64 inst_long; // 0x30
	private IDictionary`2 inst_object; // 0x38
	private String inst_string; // 0x40
	private String json; // 0x48
	private JsonType type; // 0x50
	private IList`1 object_list; // 0x58

	public Int32 Count { get; }
	public Boolean IsArray { get; }
	public Boolean IsBoolean { get; }
	public Boolean IsDouble { get; }
	public Boolean IsInt { get; }
	public Boolean IsLong { get; }
	public Boolean IsObject { get; }
	public Boolean IsString { get; }
	public ICollection`1 Keys { get; }
	private Int32 System.Collections.ICollection.Count { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private Boolean System.Collections.IDictionary.IsFixedSize { get; }
	private Boolean System.Collections.IDictionary.IsReadOnly { get; }
	private ICollection System.Collections.IDictionary.Keys { get; }
	private ICollection System.Collections.IDictionary.Values { get; }
	private Boolean LitJson.IJsonWrapper.IsArray { get; }
	private Boolean LitJson.IJsonWrapper.IsBoolean { get; }
	private Boolean LitJson.IJsonWrapper.IsDouble { get; }
	private Boolean LitJson.IJsonWrapper.IsInt { get; }
	private Boolean LitJson.IJsonWrapper.IsLong { get; }
	private Boolean LitJson.IJsonWrapper.IsObject { get; }
	private Boolean LitJson.IJsonWrapper.IsString { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Object System.Collections.IDictionary.Item { get; set; }
	private Object LitJson.IOrderedDictionary.Item { get; set; }
	private Object System.Collections.IList.Item { get; set; }
	public JsonData Item { get; set; }
	public JsonData Item { get; set; }

	// RVA: 0x65e247c VA: 0x7598bfa47c
	public Int32 get_Count() { }
	// RVA: 0x65e25fc VA: 0x7598bfa5fc
	public Boolean get_IsArray() { }
	// RVA: 0x65e260c VA: 0x7598bfa60c
	public Boolean get_IsBoolean() { }
	// RVA: 0x65e261c VA: 0x7598bfa61c
	public Boolean get_IsDouble() { }
	// RVA: 0x65e262c VA: 0x7598bfa62c
	public Boolean get_IsInt() { }
	// RVA: 0x65e263c VA: 0x7598bfa63c
	public Boolean get_IsLong() { }
	// RVA: 0x65e264c VA: 0x7598bfa64c
	public Boolean get_IsObject() { }
	// RVA: 0x65e265c VA: 0x7598bfa65c
	public Boolean get_IsString() { }
	// RVA: 0x65e266c VA: 0x7598bfa66c
	public ICollection`1 get_Keys() { }
	// RVA: 0x65e289c VA: 0x7598bfa89c
	private Int32 System.Collections.ICollection.get_Count() { }
	// RVA: 0x65e28a0 VA: 0x7598bfa8a0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x65e294c VA: 0x7598bfa94c
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x65e29f8 VA: 0x7598bfa9f8
	private Boolean System.Collections.IDictionary.get_IsFixedSize() { }
	// RVA: 0x65e2aa4 VA: 0x7598bfaaa4
	private Boolean System.Collections.IDictionary.get_IsReadOnly() { }
	// RVA: 0x65e2b50 VA: 0x7598bfab50
	private ICollection System.Collections.IDictionary.get_Keys() { }
	// RVA: 0x65e2f1c VA: 0x7598bfaf1c
	private ICollection System.Collections.IDictionary.get_Values() { }
	// RVA: 0x65e32e8 VA: 0x7598bfb2e8
	private Boolean LitJson.IJsonWrapper.get_IsArray() { }
	// RVA: 0x65e32f8 VA: 0x7598bfb2f8
	private Boolean LitJson.IJsonWrapper.get_IsBoolean() { }
	// RVA: 0x65e3308 VA: 0x7598bfb308
	private Boolean LitJson.IJsonWrapper.get_IsDouble() { }
	// RVA: 0x65e3318 VA: 0x7598bfb318
	private Boolean LitJson.IJsonWrapper.get_IsInt() { }
	// RVA: 0x65e3328 VA: 0x7598bfb328
	private Boolean LitJson.IJsonWrapper.get_IsLong() { }
	// RVA: 0x65e3338 VA: 0x7598bfb338
	private Boolean LitJson.IJsonWrapper.get_IsObject() { }
	// RVA: 0x65e3348 VA: 0x7598bfb348
	private Boolean LitJson.IJsonWrapper.get_IsString() { }
	// RVA: 0x65e3358 VA: 0x7598bfb358
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x65e3530 VA: 0x7598bfb530
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x65e35dc VA: 0x7598bfb5dc
	private Object System.Collections.IDictionary.get_Item(Object key) { }
	// RVA: 0x65e368c VA: 0x7598bfb68c
	private Void System.Collections.IDictionary.set_Item(Object key, Object value) { }
	// RVA: 0x65e3b88 VA: 0x7598bfbb88
	private Object LitJson.IOrderedDictionary.get_Item(Int32 idx) { }
	// RVA: 0x65e3c4c VA: 0x7598bfbc4c
	private Void LitJson.IOrderedDictionary.set_Item(Int32 idx, Object value) { }
	// RVA: 0x65e3e58 VA: 0x7598bfbe58
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x65e3f08 VA: 0x7598bfbf08
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x65e41e8 VA: 0x7598bfc1e8
	public JsonData get_Item(String prop_name) { }
	// RVA: 0x65e37f8 VA: 0x7598bfb7f8
	public Void set_Item(String prop_name, JsonData value) { }
	// RVA: 0x65e4298 VA: 0x7598bfc298
	public JsonData get_Item(Int32 index) { }
	// RVA: 0x65e3f40 VA: 0x7598bfbf40
	public Void set_Item(Int32 index, JsonData value) { }
	// RVA: 0x65e43e8 VA: 0x7598bfc3e8
	public Void .ctor() { }
	// RVA: 0x65e43f0 VA: 0x7598bfc3f0
	public Void .ctor(Boolean boolean) { }
	// RVA: 0x65e4420 VA: 0x7598bfc420
	public Void .ctor(Double number) { }
	// RVA: 0x65e4450 VA: 0x7598bfc450
	public Void .ctor(Int32 number) { }
	// RVA: 0x65e4480 VA: 0x7598bfc480
	public Void .ctor(Int64 number) { }
	// RVA: 0x65e44b0 VA: 0x7598bfc4b0
	public Void .ctor(Object obj) { }
	// RVA: 0x65e46e4 VA: 0x7598bfc6e4
	public Void .ctor(String str) { }
	// RVA: 0x65e471c VA: 0x7598bfc71c
	public static JsonData op_Implicit(Boolean data) { }
	// RVA: 0x65e478c VA: 0x7598bfc78c
	public static JsonData op_Implicit(Double data) { }
	// RVA: 0x65e4800 VA: 0x7598bfc800
	public static JsonData op_Implicit(Int32 data) { }
	// RVA: 0x65e486c VA: 0x7598bfc86c
	public static JsonData op_Implicit(Int64 data) { }
	// RVA: 0x65e48d8 VA: 0x7598bfc8d8
	public static JsonData op_Implicit(String data) { }
	// RVA: 0x65e4950 VA: 0x7598bfc950
	public static Boolean op_Explicit(JsonData data) { }
	// RVA: 0x65e49c0 VA: 0x7598bfc9c0
	public static Double op_Explicit(JsonData data) { }
	// RVA: 0x65e4a30 VA: 0x7598bfca30
	public static Int32 op_Explicit(JsonData data) { }
	// RVA: 0x65e4aa0 VA: 0x7598bfcaa0
	public static Int64 op_Explicit(JsonData data) { }
	// RVA: 0x65e4b10 VA: 0x7598bfcb10
	public static String op_Explicit(JsonData data) { }
	// RVA: 0x65e4b80 VA: 0x7598bfcb80
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x65e4c40 VA: 0x7598bfcc40
	private Void System.Collections.IDictionary.Add(Object key, Object value) { }
	// RVA: 0x65e4e0c VA: 0x7598bfce0c
	private Void System.Collections.IDictionary.Clear() { }
	// RVA: 0x65e4f40 VA: 0x7598bfcf40
	private Boolean System.Collections.IDictionary.Contains(Object key) { }
	// RVA: 0x65e4ff4 VA: 0x7598bfcff4
	private IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() { }
	// RVA: 0x65e5088 VA: 0x7598bfd088
	private Void System.Collections.IDictionary.Remove(Object key) { }
	// RVA: 0x65e5314 VA: 0x7598bfd314
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x65e53bc VA: 0x7598bfd3bc
	private Boolean LitJson.IJsonWrapper.GetBoolean() { }
	// RVA: 0x65e5424 VA: 0x7598bfd424
	private Double LitJson.IJsonWrapper.GetDouble() { }
	// RVA: 0x65e548c VA: 0x7598bfd48c
	private Int32 LitJson.IJsonWrapper.GetInt() { }
	// RVA: 0x65e54f4 VA: 0x7598bfd4f4
	private Int64 LitJson.IJsonWrapper.GetLong() { }
	// RVA: 0x65e555c VA: 0x7598bfd55c
	private String LitJson.IJsonWrapper.GetString() { }
	// RVA: 0x65e55c4 VA: 0x7598bfd5c4
	private Void LitJson.IJsonWrapper.SetBoolean(Boolean val) { }
	// RVA: 0x65e55e0 VA: 0x7598bfd5e0
	private Void LitJson.IJsonWrapper.SetDouble(Double val) { }
	// RVA: 0x65e55f8 VA: 0x7598bfd5f8
	private Void LitJson.IJsonWrapper.SetInt(Int32 val) { }
	// RVA: 0x65e5610 VA: 0x7598bfd610
	private Void LitJson.IJsonWrapper.SetLong(Int64 val) { }
	// RVA: 0x65e5628 VA: 0x7598bfd628
	private Void LitJson.IJsonWrapper.SetString(String val) { }
	// RVA: 0x65e5654 VA: 0x7598bfd654
	private String LitJson.IJsonWrapper.ToJson() { }
	// RVA: 0x65e572c VA: 0x7598bfd72c
	private Void LitJson.IJsonWrapper.ToJson(JsonWriter writer) { }
	// RVA: 0x65e5760 VA: 0x7598bfd760
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x65e5834 VA: 0x7598bfd834
	private Void System.Collections.IList.Clear() { }
	// RVA: 0x65e58f0 VA: 0x7598bfd8f0
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x65e59a4 VA: 0x7598bfd9a4
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x65e5a58 VA: 0x7598bfda58
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x65e5b2c VA: 0x7598bfdb2c
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x65e5bf0 VA: 0x7598bfdbf0
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
	// RVA: 0x65e5cb4 VA: 0x7598bfdcb4
	private IDictionaryEnumerator LitJson.IOrderedDictionary.GetEnumerator() { }
	// RVA: 0x65e5d9c VA: 0x7598bfdd9c
	private Void LitJson.IOrderedDictionary.Insert(Int32 idx, Object key, Object value) { }
	// RVA: 0x65e5ee8 VA: 0x7598bfdee8
	private Void LitJson.IOrderedDictionary.RemoveAt(Int32 idx) { }
	// RVA: 0x65e2528 VA: 0x7598bfa528
	private ICollection EnsureCollection() { }
	// RVA: 0x65e2718 VA: 0x7598bfa718
	private IDictionary EnsureDictionary() { }
	// RVA: 0x65e3404 VA: 0x7598bfb404
	private IList EnsureList() { }
	// RVA: 0x65e3768 VA: 0x7598bfb768
	private JsonData ToJsonData(Object obj) { }
	// RVA: 0x65e6094 VA: 0x7598bfe094
	private static Void WriteJson(IJsonWrapper obj, JsonWriter writer) { }
	// RVA: 0x65e5764 VA: 0x7598bfd764
	public Int32 Add(Object value) { }
	// RVA: 0x65e6ca8 VA: 0x7598bfeca8
	public Void Clear() { }
	// RVA: 0x65e6db8 VA: 0x7598bfedb8
	public Boolean Equals(JsonData x) { }
	// RVA: 0x65e6f10 VA: 0x7598bfef10
	public JsonType GetJsonType() { }
	// RVA: 0x65e6f18 VA: 0x7598bfef18
	public Void SetJsonType(JsonType type) { }
	// RVA: 0x65e5658 VA: 0x7598bfd658
	public String ToJson() { }
	// RVA: 0x65e5730 VA: 0x7598bfd730
	public Void ToJson(JsonWriter writer) { }
	// RVA: 0x65e70a4 VA: 0x7598bff0a4
	public override String ToString() { }
}
```