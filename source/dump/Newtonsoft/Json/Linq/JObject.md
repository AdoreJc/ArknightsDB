# JObject

**Namespace:** `Newtonsoft.Json.Linq`


## Fields

- `PropertyChangedEventHandler PropertyChanged`

- `PropertyChangingEventHandler PropertyChanging`


## Properties

- `JToken Item`


## Methods

- `Void add_PropertyChanged(PropertyChangedEventHandler)`

- `Void remove_PropertyChanged(PropertyChangedEventHandler)`

- `JProperty Property(String)`

- `JToken get_Item(String)`

- `Void set_Item(String, JToken)`

- `JToken GetValue(String)`

- `JToken GetValue(String, StringComparison)`

- `Void Add(String, JToken)`

- `Boolean Remove(String)`

- `Boolean TryGetValue(String, out)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq
public class JObject : JContainer, IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable, INotifyPropertyChanged, ICustomTypeDescriptor, INotifyPropertyChanging
{
	private readonly JPropertyKeyedCollection _properties; // 0x50
	private PropertyChangedEventHandler PropertyChanged; // 0x58
	private PropertyChangingEventHandler PropertyChanging; // 0x60

	protected override IList`1 ChildrenTokens { get; }
	public override JTokenType Type { get; }
	public override JToken Item { get; }
	public JToken Item { get; set; }
	private ICollection`1 System.Collections.Generic.IDictionary<System.String,Newtonsoft.Json.Linq.JToken>.Keys { get; }
	private ICollection`1 System.Collections.Generic.IDictionary<System.String,Newtonsoft.Json.Linq.JToken>.Values { get; }
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<System.String,Newtonsoft.Json.Linq.JToken>>.IsReadOnly { get; }

	// RVA: 0x618ea88 VA: 0x75987a6a88
	protected override IList`1 get_ChildrenTokens() { }
	// RVA: 0x618ea90 VA: 0x75987a6a90
	public Void add_PropertyChanged(PropertyChangedEventHandler value) { }
	// RVA: 0x618eb2c VA: 0x75987a6b2c
	public Void remove_PropertyChanged(PropertyChangedEventHandler value) { }
	// RVA: 0x618e034 VA: 0x75987a6034
	public Void .ctor() { }
	// RVA: 0x618ebc8 VA: 0x75987a6bc8
	public Void .ctor(JObject other) { }
	// RVA: 0x618ec44 VA: 0x75987a6c44
	internal override Boolean DeepEquals(JToken node) { }
	// RVA: 0x618ece0 VA: 0x75987a6ce0
	internal override Int32 IndexOfItem(JToken item) { }
	// RVA: 0x618ecf8 VA: 0x75987a6cf8
	internal override Void InsertItem(Int32 index, JToken item, Boolean skipParentCheck) { }
	// RVA: 0x618ed60 VA: 0x75987a6d60
	internal override Void ValidateToken(JToken o, JToken existing) { }
	// RVA: 0x618ef78 VA: 0x75987a6f78
	internal Void InternalPropertyChanged(JProperty childProperty) { }
	// RVA: 0x618f044 VA: 0x75987a7044
	internal Void InternalPropertyChanging(JProperty childProperty) { }
	// RVA: 0x618f068 VA: 0x75987a7068
	internal override JToken CloneToken() { }
	// RVA: 0x618f0c8 VA: 0x75987a70c8
	public override JTokenType get_Type() { }
	// RVA: 0x618f0d0 VA: 0x75987a70d0
	public IEnumerable`1 Properties() { }
	// RVA: 0x618e214 VA: 0x75987a6214
	public JProperty Property(String name) { }
	// RVA: 0x618f118 VA: 0x75987a7118
	public override JToken get_Item(Object key) { }
	// RVA: 0x618f230 VA: 0x75987a7230
	public JToken get_Item(String propertyName) { }
	// RVA: 0x618f2ac VA: 0x75987a72ac
	public Void set_Item(String propertyName, JToken value) { }
	// RVA: 0x618f508 VA: 0x75987a7508
	public static JObject Load(JsonReader reader) { }
	// RVA: 0x618f510 VA: 0x75987a7510
	public static JObject Load(JsonReader reader, JsonLoadSettings settings) { }
	// RVA: 0x618f6d4 VA: 0x75987a76d4
	public static JObject Parse(String json) { }
	// RVA: 0x618f6dc VA: 0x75987a76dc
	public static JObject Parse(String json, JsonLoadSettings settings) { }
	// RVA: 0x618f918 VA: 0x75987a7918
	public static JObject FromObject(Object o) { }
	// RVA: 0x618f938 VA: 0x75987a7938
	public static JObject FromObject(Object o, JsonSerializer jsonSerializer) { }
	// RVA: 0x618fcc4 VA: 0x75987a7cc4
	public override Void WriteTo(JsonWriter writer, JsonConverter[] converters) { }
	// RVA: 0x618fdac VA: 0x75987a7dac
	public JToken GetValue(String propertyName) { }
	// RVA: 0x618fdb4 VA: 0x75987a7db4
	public JToken GetValue(String propertyName, StringComparison comparison) { }
	// RVA: 0x6190128 VA: 0x75987a8128
	public Void Add(String propertyName, JToken value) { }
	// RVA: 0x61901ac VA: 0x75987a81ac
	private Boolean System.Collections.Generic.IDictionary<System.String,Newtonsoft.Json.Linq.JToken>.ContainsKey(String key) { }
	// RVA: 0x61901c4 VA: 0x75987a81c4
	private ICollection`1 System.Collections.Generic.IDictionary<System.String,Newtonsoft.Json.Linq.JToken>.get_Keys() { }
	// RVA: 0x61901dc VA: 0x75987a81dc
	public Boolean Remove(String propertyName) { }
	// RVA: 0x6190268 VA: 0x75987a8268
	public Boolean TryGetValue(String propertyName, out JToken value) { }
	// RVA: 0x61902b8 VA: 0x75987a82b8
	private ICollection`1 System.Collections.Generic.IDictionary<System.String,Newtonsoft.Json.Linq.JToken>.get_Values() { }
	// RVA: 0x61902f8 VA: 0x75987a82f8
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<System.String,Newtonsoft.Json.Linq.JToken>>.Add(KeyValuePair`2 item) { }
	// RVA: 0x6190394 VA: 0x75987a8394
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<System.String,Newtonsoft.Json.Linq.JToken>>.Clear() { }
	// RVA: 0x61903a4 VA: 0x75987a83a4
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<System.String,Newtonsoft.Json.Linq.JToken>>.Contains(KeyValuePair`2 item) { }
	// RVA: 0x6190420 VA: 0x75987a8420
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<System.String,Newtonsoft.Json.Linq.JToken>>.CopyTo(KeyValuePair`2[] array, Int32 arrayIndex) { }
	// RVA: 0x61908a8 VA: 0x75987a88a8
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<System.String,Newtonsoft.Json.Linq.JToken>>.get_IsReadOnly() { }
	// RVA: 0x61908b0 VA: 0x75987a88b0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<System.String,Newtonsoft.Json.Linq.JToken>>.Remove(KeyValuePair`2 item) { }
	// RVA: 0x61909f4 VA: 0x75987a89f4
	internal override Int32 GetDeepHashCode() { }
	// RVA: 0x61909f8 VA: 0x75987a89f8
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x6190a94 VA: 0x75987a8a94
	protected virtual Void OnPropertyChanged(String propertyName) { }
	// RVA: 0x6190b2c VA: 0x75987a8b2c
	protected virtual Void OnPropertyChanging(String propertyName) { }
	// RVA: 0x6190bc4 VA: 0x75987a8bc4
	private PropertyDescriptorCollection System.ComponentModel.ICustomTypeDescriptor.GetProperties() { }
	// RVA: 0x6190c60 VA: 0x75987a8c60
	private PropertyDescriptorCollection System.ComponentModel.ICustomTypeDescriptor.GetProperties(Attribute[] attributes) { }
	// RVA: 0x6190f5c VA: 0x75987a8f5c
	private AttributeCollection System.ComponentModel.ICustomTypeDescriptor.GetAttributes() { }
	// RVA: 0x6190fb4 VA: 0x75987a8fb4
	private String System.ComponentModel.ICustomTypeDescriptor.GetClassName() { }
	// RVA: 0x6190fbc VA: 0x75987a8fbc
	private String System.ComponentModel.ICustomTypeDescriptor.GetComponentName() { }
	// RVA: 0x6190fc4 VA: 0x75987a8fc4
	private TypeConverter System.ComponentModel.ICustomTypeDescriptor.GetConverter() { }
	// RVA: 0x6191020 VA: 0x75987a9020
	private EventDescriptor System.ComponentModel.ICustomTypeDescriptor.GetDefaultEvent() { }
	// RVA: 0x6191028 VA: 0x75987a9028
	private PropertyDescriptor System.ComponentModel.ICustomTypeDescriptor.GetDefaultProperty() { }
	// RVA: 0x6191030 VA: 0x75987a9030
	private Object System.ComponentModel.ICustomTypeDescriptor.GetEditor(Type editorBaseType) { }
	// RVA: 0x6191038 VA: 0x75987a9038
	private EventDescriptorCollection System.ComponentModel.ICustomTypeDescriptor.GetEvents(Attribute[] attributes) { }
	// RVA: 0x6191090 VA: 0x75987a9090
	private EventDescriptorCollection System.ComponentModel.ICustomTypeDescriptor.GetEvents() { }
	// RVA: 0x61910e8 VA: 0x75987a90e8
	private Object System.ComponentModel.ICustomTypeDescriptor.GetPropertyOwner(PropertyDescriptor pd) { }
}
```