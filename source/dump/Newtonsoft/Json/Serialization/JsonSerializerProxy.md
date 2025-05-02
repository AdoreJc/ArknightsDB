# JsonSerializerProxy

**Namespace:** `Newtonsoft.Json.Serialization`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
internal class JsonSerializerProxy : JsonSerializer
{
	private readonly JsonSerializerInternalReader _serializerReader; // 0xe0
	private readonly JsonSerializerInternalWriter _serializerWriter; // 0xe8
	private readonly JsonSerializer _serializer; // 0xf0

	public override IReferenceResolver ReferenceResolver { set; }
	public override ITraceWriter TraceWriter { get; set; }
	public override IEqualityComparer EqualityComparer { set; }
	public override JsonConverterCollection Converters { get; }
	public override DefaultValueHandling DefaultValueHandling { set; }
	public override IContractResolver ContractResolver { get; set; }
	public override MissingMemberHandling MissingMemberHandling { set; }
	public override NullValueHandling NullValueHandling { set; }
	public override ObjectCreationHandling ObjectCreationHandling { get; set; }
	public override ReferenceLoopHandling ReferenceLoopHandling { set; }
	public override PreserveReferencesHandling PreserveReferencesHandling { set; }
	public override TypeNameHandling TypeNameHandling { set; }
	public override MetadataPropertyHandling MetadataPropertyHandling { get; set; }
	public override FormatterAssemblyStyle TypeNameAssemblyFormat { set; }
	public override ConstructorHandling ConstructorHandling { set; }
	public override SerializationBinder Binder { set; }
	public override StreamingContext Context { get; set; }
	public override Formatting Formatting { get; set; }
	public override Boolean CheckAdditionalContent { get; set; }

	// RVA: 0x6185d14 VA: 0x759879dd14
	public override Void add_Error(EventHandler`1 value) { }
	// RVA: 0x6185d34 VA: 0x759879dd34
	public override Void remove_Error(EventHandler`1 value) { }
	// RVA: 0x6185d54 VA: 0x759879dd54
	public override Void set_ReferenceResolver(IReferenceResolver value) { }
	// RVA: 0x6185d74 VA: 0x759879dd74
	public override ITraceWriter get_TraceWriter() { }
	// RVA: 0x6185d94 VA: 0x759879dd94
	public override Void set_TraceWriter(ITraceWriter value) { }
	// RVA: 0x6185db4 VA: 0x759879ddb4
	public override Void set_EqualityComparer(IEqualityComparer value) { }
	// RVA: 0x6185dd4 VA: 0x759879ddd4
	public override JsonConverterCollection get_Converters() { }
	// RVA: 0x6185df8 VA: 0x759879ddf8
	public override Void set_DefaultValueHandling(DefaultValueHandling value) { }
	// RVA: 0x6185e1c VA: 0x759879de1c
	public override IContractResolver get_ContractResolver() { }
	// RVA: 0x6185e40 VA: 0x759879de40
	public override Void set_ContractResolver(IContractResolver value) { }
	// RVA: 0x6185e64 VA: 0x759879de64
	public override Void set_MissingMemberHandling(MissingMemberHandling value) { }
	// RVA: 0x6185e88 VA: 0x759879de88
	public override Void set_NullValueHandling(NullValueHandling value) { }
	// RVA: 0x6185eac VA: 0x759879deac
	public override ObjectCreationHandling get_ObjectCreationHandling() { }
	// RVA: 0x6185ed0 VA: 0x759879ded0
	public override Void set_ObjectCreationHandling(ObjectCreationHandling value) { }
	// RVA: 0x6185ef4 VA: 0x759879def4
	public override Void set_ReferenceLoopHandling(ReferenceLoopHandling value) { }
	// RVA: 0x6185f18 VA: 0x759879df18
	public override Void set_PreserveReferencesHandling(PreserveReferencesHandling value) { }
	// RVA: 0x6185f3c VA: 0x759879df3c
	public override Void set_TypeNameHandling(TypeNameHandling value) { }
	// RVA: 0x6185f5c VA: 0x759879df5c
	public override MetadataPropertyHandling get_MetadataPropertyHandling() { }
	// RVA: 0x6185f80 VA: 0x759879df80
	public override Void set_MetadataPropertyHandling(MetadataPropertyHandling value) { }
	// RVA: 0x6185fa4 VA: 0x759879dfa4
	public override Void set_TypeNameAssemblyFormat(FormatterAssemblyStyle value) { }
	// RVA: 0x6185fc4 VA: 0x759879dfc4
	public override Void set_ConstructorHandling(ConstructorHandling value) { }
	// RVA: 0x6185fe8 VA: 0x759879dfe8
	public override Void set_Binder(SerializationBinder value) { }
	// RVA: 0x6186008 VA: 0x759879e008
	public override StreamingContext get_Context() { }
	// RVA: 0x618602c VA: 0x759879e02c
	public override Void set_Context(StreamingContext value) { }
	// RVA: 0x6186050 VA: 0x759879e050
	public override Formatting get_Formatting() { }
	// RVA: 0x6186074 VA: 0x759879e074
	public override Void set_Formatting(Formatting value) { }
	// RVA: 0x6186098 VA: 0x759879e098
	public override Boolean get_CheckAdditionalContent() { }
	// RVA: 0x61860bc VA: 0x759879e0bc
	public override Void set_CheckAdditionalContent(Boolean value) { }
	// RVA: 0x61860e4 VA: 0x759879e0e4
	internal JsonSerializerInternalBase GetInternalSerializer() { }
	// RVA: 0x617781c VA: 0x759878f81c
	public Void .ctor(JsonSerializerInternalReader serializerReader) { }
	// RVA: 0x6180f3c VA: 0x7598798f3c
	public Void .ctor(JsonSerializerInternalWriter serializerWriter) { }
	// RVA: 0x6186100 VA: 0x759879e100
	internal override Object DeserializeInternal(JsonReader reader, Type objectType) { }
	// RVA: 0x6186134 VA: 0x759879e134
	internal override Void PopulateInternal(JsonReader reader, Object target) { }
	// RVA: 0x6186164 VA: 0x759879e164
	internal override Void SerializeInternal(JsonWriter jsonWriter, Object value, Type rootType) { }
}
```