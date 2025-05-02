# JsonSerializer

**Namespace:** `Newtonsoft.Json`


## Fields

- `IReferenceResolver _referenceResolver`

- `CultureInfo _culture`

- `Boolean _maxDepthSet`

- `String _dateFormatString`

- `Boolean _dateFormatStringSet`


## Methods

- `Void Populate(JsonReader, Object)`

- `Object Deserialize(JsonReader)`

- `T Deserialize(JsonReader)`

- `Object Deserialize(JsonReader, Type)`

- `Void SetupReader(JsonReader, out, out, out, out, out, out)`

- `Void ResetReader(JsonReader, CultureInfo, Nullable`1, Nullable`1, Nullable`1, Nullable`1, String)`

- `Void Serialize(JsonWriter, Object, Type)`

- `Void Serialize(JsonWriter, Object)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json
public class JsonSerializer
{
	internal TypeNameHandling _typeNameHandling; // 0x10
	internal FormatterAssemblyStyle _typeNameAssemblyFormat; // 0x14
	internal PreserveReferencesHandling _preserveReferencesHandling; // 0x18
	internal ReferenceLoopHandling _referenceLoopHandling; // 0x1c
	internal MissingMemberHandling _missingMemberHandling; // 0x20
	internal ObjectCreationHandling _objectCreationHandling; // 0x24
	internal NullValueHandling _nullValueHandling; // 0x28
	internal DefaultValueHandling _defaultValueHandling; // 0x2c
	internal ConstructorHandling _constructorHandling; // 0x30
	internal MetadataPropertyHandling _metadataPropertyHandling; // 0x34
	internal JsonConverterCollection _converters; // 0x38
	internal IContractResolver _contractResolver; // 0x40
	internal ITraceWriter _traceWriter; // 0x48
	internal IEqualityComparer _equalityComparer; // 0x50
	internal SerializationBinder _binder; // 0x58
	internal StreamingContext _context; // 0x60
	private IReferenceResolver _referenceResolver; // 0x70
	private Nullable`1 _formatting; // 0x78
	private Nullable`1 _dateFormatHandling; // 0x80
	private Nullable`1 _dateTimeZoneHandling; // 0x88
	private Nullable`1 _dateParseHandling; // 0x90
	private Nullable`1 _floatFormatHandling; // 0x98
	private Nullable`1 _floatParseHandling; // 0xa0
	private Nullable`1 _stringEscapeHandling; // 0xa8
	private CultureInfo _culture; // 0xb0
	private Nullable`1 _maxDepth; // 0xb8
	private Boolean _maxDepthSet; // 0xc0
	private Nullable`1 _checkAdditionalContent; // 0xc1
	private String _dateFormatString; // 0xc8
	private Boolean _dateFormatStringSet; // 0xd0
	private EventHandler`1 Error; // 0xd8

	public virtual IReferenceResolver ReferenceResolver { set; }
	public virtual SerializationBinder Binder { set; }
	public virtual ITraceWriter TraceWriter { get; set; }
	public virtual IEqualityComparer EqualityComparer { set; }
	public virtual TypeNameHandling TypeNameHandling { set; }
	public virtual FormatterAssemblyStyle TypeNameAssemblyFormat { set; }
	public virtual PreserveReferencesHandling PreserveReferencesHandling { set; }
	public virtual ReferenceLoopHandling ReferenceLoopHandling { set; }
	public virtual MissingMemberHandling MissingMemberHandling { set; }
	public virtual NullValueHandling NullValueHandling { set; }
	public virtual DefaultValueHandling DefaultValueHandling { set; }
	public virtual ObjectCreationHandling ObjectCreationHandling { get; set; }
	public virtual ConstructorHandling ConstructorHandling { set; }
	public virtual MetadataPropertyHandling MetadataPropertyHandling { get; set; }
	public virtual JsonConverterCollection Converters { get; }
	public virtual IContractResolver ContractResolver { get; set; }
	public virtual StreamingContext Context { get; set; }
	public virtual Formatting Formatting { get; set; }
	public virtual Boolean CheckAdditionalContent { get; set; }

	// RVA: 0x614bb64 VA: 0x7598763b64
	public virtual Void add_Error(EventHandler`1 value) { }
	// RVA: 0x614bc14 VA: 0x7598763c14
	public virtual Void remove_Error(EventHandler`1 value) { }
	// RVA: 0x614bcc4 VA: 0x7598763cc4
	public virtual Void set_ReferenceResolver(IReferenceResolver value) { }
	// RVA: 0x614bd40 VA: 0x7598763d40
	public virtual Void set_Binder(SerializationBinder value) { }
	// RVA: 0x614bdbc VA: 0x7598763dbc
	public virtual ITraceWriter get_TraceWriter() { }
	// RVA: 0x614bdc4 VA: 0x7598763dc4
	public virtual Void set_TraceWriter(ITraceWriter value) { }
	// RVA: 0x614bdcc VA: 0x7598763dcc
	public virtual Void set_EqualityComparer(IEqualityComparer value) { }
	// RVA: 0x614bdd4 VA: 0x7598763dd4
	public virtual Void set_TypeNameHandling(TypeNameHandling value) { }
	// RVA: 0x614be38 VA: 0x7598763e38
	public virtual Void set_TypeNameAssemblyFormat(FormatterAssemblyStyle value) { }
	// RVA: 0x614be9c VA: 0x7598763e9c
	public virtual Void set_PreserveReferencesHandling(PreserveReferencesHandling value) { }
	// RVA: 0x614bf00 VA: 0x7598763f00
	public virtual Void set_ReferenceLoopHandling(ReferenceLoopHandling value) { }
	// RVA: 0x614bf64 VA: 0x7598763f64
	public virtual Void set_MissingMemberHandling(MissingMemberHandling value) { }
	// RVA: 0x614bfc8 VA: 0x7598763fc8
	public virtual Void set_NullValueHandling(NullValueHandling value) { }
	// RVA: 0x614c02c VA: 0x759876402c
	public virtual Void set_DefaultValueHandling(DefaultValueHandling value) { }
	// RVA: 0x614c090 VA: 0x7598764090
	public virtual ObjectCreationHandling get_ObjectCreationHandling() { }
	// RVA: 0x614c098 VA: 0x7598764098
	public virtual Void set_ObjectCreationHandling(ObjectCreationHandling value) { }
	// RVA: 0x614c0fc VA: 0x75987640fc
	public virtual Void set_ConstructorHandling(ConstructorHandling value) { }
	// RVA: 0x614c160 VA: 0x7598764160
	public virtual MetadataPropertyHandling get_MetadataPropertyHandling() { }
	// RVA: 0x614c168 VA: 0x7598764168
	public virtual Void set_MetadataPropertyHandling(MetadataPropertyHandling value) { }
	// RVA: 0x614c1cc VA: 0x75987641cc
	public virtual JsonConverterCollection get_Converters() { }
	// RVA: 0x614c240 VA: 0x7598764240
	public virtual IContractResolver get_ContractResolver() { }
	// RVA: 0x614c248 VA: 0x7598764248
	public virtual Void set_ContractResolver(IContractResolver value) { }
	// RVA: 0x614c2f8 VA: 0x75987642f8
	public virtual StreamingContext get_Context() { }
	// RVA: 0x614c304 VA: 0x7598764304
	public virtual Void set_Context(StreamingContext value) { }
	// RVA: 0x614c314 VA: 0x7598764314
	public virtual Formatting get_Formatting() { }
	// RVA: 0x614c364 VA: 0x7598764364
	public virtual Void set_Formatting(Formatting value) { }
	// RVA: 0x614c3cc VA: 0x75987643cc
	public virtual Boolean get_CheckAdditionalContent() { }
	// RVA: 0x614c428 VA: 0x7598764428
	public virtual Void set_CheckAdditionalContent(Boolean value) { }
	// RVA: 0x614b74c VA: 0x759876374c
	internal Boolean IsCheckAdditionalContentSet() { }
	// RVA: 0x614c490 VA: 0x7598764490
	public Void .ctor() { }
	// RVA: 0x614c5dc VA: 0x75987645dc
	public static JsonSerializer Create() { }
	// RVA: 0x614c634 VA: 0x7598764634
	public static JsonSerializer Create(JsonSerializerSettings settings) { }
	// RVA: 0x614ccb4 VA: 0x7598764cb4
	public static JsonSerializer CreateDefault() { }
	// RVA: 0x614b078 VA: 0x7598763078
	public static JsonSerializer CreateDefault(JsonSerializerSettings settings) { }
	// RVA: 0x614c668 VA: 0x7598764668
	private static Void ApplySerializerSettings(JsonSerializer serializer, JsonSerializerSettings settings) { }
	// RVA: 0x614ba04 VA: 0x7598763a04
	public Void Populate(JsonReader reader, Object target) { }
	// RVA: 0x614cd58 VA: 0x7598764d58
	internal virtual Void PopulateInternal(JsonReader reader, Object target) { }
	// RVA: 0x614d568 VA: 0x7598765568
	public Object Deserialize(JsonReader reader) { }
	// RVA: 0x VA: 0x0
	public T Deserialize(JsonReader reader) { }
	// RVA: 0x614b788 VA: 0x7598763788
	public Object Deserialize(JsonReader reader, Type objectType) { }
	// RVA: 0x614d57c VA: 0x759876557c
	internal virtual Object DeserializeInternal(JsonReader reader, Type objectType) { }
	// RVA: 0x614cff4 VA: 0x7598764ff4
	private Void SetupReader(JsonReader reader, out CultureInfo previousCulture, out Nullable`1 previousDateTimeZoneHandling, out Nullable`1 previousDateParseHandling, out Nullable`1 previousFloatParseHandling, out Nullable`1 previousMaxDepth, out String previousDateFormatString) { }
	// RVA: 0x614d3b8 VA: 0x75987653b8
	private Void ResetReader(JsonReader reader, CultureInfo previousCulture, Nullable`1 previousDateTimeZoneHandling, Nullable`1 previousDateParseHandling, Nullable`1 previousFloatParseHandling, Nullable`1 previousMaxDepth, String previousDateFormatString) { }
	// RVA: 0x614b428 VA: 0x7598763428
	public Void Serialize(JsonWriter jsonWriter, Object value, Type objectType) { }
	// RVA: 0x614d814 VA: 0x7598765814
	public Void Serialize(JsonWriter jsonWriter, Object value) { }
	// RVA: 0x614d828 VA: 0x7598765828
	internal virtual Void SerializeInternal(JsonWriter jsonWriter, Object value, Type objectType) { }
	// RVA: 0x614df5c VA: 0x7598765f5c
	internal IReferenceResolver GetReferenceResolver() { }
	// RVA: 0x614dfd4 VA: 0x7598765fd4
	internal JsonConverter GetMatchingConverter(Type type) { }
	// RVA: 0x614dfdc VA: 0x7598765fdc
	internal static JsonConverter GetMatchingConverter(IList`1 converters, Type objectType) { }
	// RVA: 0x614e138 VA: 0x7598766138
	internal Void OnError(ErrorEventArgs e) { }
}
```