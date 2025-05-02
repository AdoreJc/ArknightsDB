# JsonSerializerSettings

**Namespace:** `Newtonsoft.Json`


## Fields

- `IContractResolver <ContractResolver>k__BackingField`

- `IEqualityComparer <EqualityComparer>k__BackingField`

- `ITraceWriter <TraceWriter>k__BackingField`

- `SerializationBinder <Binder>k__BackingField`


## Properties

- `ReferenceLoopHandling ReferenceLoopHandling`

- `MissingMemberHandling MissingMemberHandling`

- `ObjectCreationHandling ObjectCreationHandling`

- `NullValueHandling NullValueHandling`

- `DefaultValueHandling DefaultValueHandling`

- `PreserveReferencesHandling PreserveReferencesHandling`

- `TypeNameHandling TypeNameHandling`

- `MetadataPropertyHandling MetadataPropertyHandling`

- `FormatterAssemblyStyle TypeNameAssemblyFormat`

- `ConstructorHandling ConstructorHandling`

- `IContractResolver ContractResolver`

- `IEqualityComparer EqualityComparer`

- `ITraceWriter TraceWriter`

- `SerializationBinder Binder`

- `StreamingContext Context`

- `Formatting Formatting`


## Methods

- `ReferenceLoopHandling get_ReferenceLoopHandling()`

- `MissingMemberHandling get_MissingMemberHandling()`

- `ObjectCreationHandling get_ObjectCreationHandling()`

- `NullValueHandling get_NullValueHandling()`

- `Void set_NullValueHandling(NullValueHandling)`

- `DefaultValueHandling get_DefaultValueHandling()`

- `Void set_Converters(IList`1)`

- `PreserveReferencesHandling get_PreserveReferencesHandling()`

- `TypeNameHandling get_TypeNameHandling()`

- `Void set_TypeNameHandling(TypeNameHandling)`

- `MetadataPropertyHandling get_MetadataPropertyHandling()`

- `FormatterAssemblyStyle get_TypeNameAssemblyFormat()`

- `Void set_TypeNameAssemblyFormat(FormatterAssemblyStyle)`

- `ConstructorHandling get_ConstructorHandling()`

- `IContractResolver get_ContractResolver()`

- `Void set_ContractResolver(IContractResolver)`

- `IEqualityComparer get_EqualityComparer()`

- `ITraceWriter get_TraceWriter()`

- `SerializationBinder get_Binder()`

- `StreamingContext get_Context()`

- `Void set_Formatting(Formatting)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json
public class JsonSerializerSettings
{
	internal static readonly StreamingContext DefaultContext; // 0x0
	internal static readonly CultureInfo DefaultCulture; // 0x10
	internal Nullable`1 _formatting; // 0x10
	internal Nullable`1 _dateFormatHandling; // 0x18
	internal Nullable`1 _dateTimeZoneHandling; // 0x20
	internal Nullable`1 _dateParseHandling; // 0x28
	internal Nullable`1 _floatFormatHandling; // 0x30
	internal Nullable`1 _floatParseHandling; // 0x38
	internal Nullable`1 _stringEscapeHandling; // 0x40
	internal CultureInfo _culture; // 0x48
	internal Nullable`1 _checkAdditionalContent; // 0x50
	internal Nullable`1 _maxDepth; // 0x54
	internal Boolean _maxDepthSet; // 0x5c
	internal String _dateFormatString; // 0x60
	internal Boolean _dateFormatStringSet; // 0x68
	internal Nullable`1 _typeNameAssemblyFormat; // 0x6c
	internal Nullable`1 _defaultValueHandling; // 0x74
	internal Nullable`1 _preserveReferencesHandling; // 0x7c
	internal Nullable`1 _nullValueHandling; // 0x84
	internal Nullable`1 _objectCreationHandling; // 0x8c
	internal Nullable`1 _missingMemberHandling; // 0x94
	internal Nullable`1 _referenceLoopHandling; // 0x9c
	internal Nullable`1 _context; // 0xa8
	internal Nullable`1 _constructorHandling; // 0xc0
	internal Nullable`1 _typeNameHandling; // 0xc8
	internal Nullable`1 _metadataPropertyHandling; // 0xd0
	private IList`1 <Converters>k__BackingField; // 0xd8
	private IContractResolver <ContractResolver>k__BackingField; // 0xe0
	private IEqualityComparer <EqualityComparer>k__BackingField; // 0xe8
	private Func`1 <ReferenceResolverProvider>k__BackingField; // 0xf0
	private ITraceWriter <TraceWriter>k__BackingField; // 0xf8
	private SerializationBinder <Binder>k__BackingField; // 0x100
	private EventHandler`1 <Error>k__BackingField; // 0x108

	public ReferenceLoopHandling ReferenceLoopHandling { get; }
	public MissingMemberHandling MissingMemberHandling { get; }
	public ObjectCreationHandling ObjectCreationHandling { get; }
	public NullValueHandling NullValueHandling { get; set; }
	public DefaultValueHandling DefaultValueHandling { get; }
	public IList`1 Converters { get; set; }
	public PreserveReferencesHandling PreserveReferencesHandling { get; }
	public TypeNameHandling TypeNameHandling { get; set; }
	public MetadataPropertyHandling MetadataPropertyHandling { get; }
	public FormatterAssemblyStyle TypeNameAssemblyFormat { get; set; }
	public ConstructorHandling ConstructorHandling { get; }
	public IContractResolver ContractResolver { get; set; }
	public IEqualityComparer EqualityComparer { get; }
	public Func`1 ReferenceResolverProvider { get; }
	public ITraceWriter TraceWriter { get; }
	public SerializationBinder Binder { get; }
	public EventHandler`1 Error { get; }
	public StreamingContext Context { get; }
	public Formatting Formatting { set; }

	// RVA: 0x613e3d0 VA: 0x75987563d0
	public ReferenceLoopHandling get_ReferenceLoopHandling() { }
	// RVA: 0x613e420 VA: 0x7598756420
	public MissingMemberHandling get_MissingMemberHandling() { }
	// RVA: 0x613e470 VA: 0x7598756470
	public ObjectCreationHandling get_ObjectCreationHandling() { }
	// RVA: 0x613e4c0 VA: 0x75987564c0
	public NullValueHandling get_NullValueHandling() { }
	// RVA: 0x613e510 VA: 0x7598756510
	public Void set_NullValueHandling(NullValueHandling value) { }
	// RVA: 0x613e578 VA: 0x7598756578
	public DefaultValueHandling get_DefaultValueHandling() { }
	// RVA: 0x613e5c8 VA: 0x75987565c8
	public IList`1 get_Converters() { }
	// RVA: 0x613e5d0 VA: 0x75987565d0
	public Void set_Converters(IList`1 value) { }
	// RVA: 0x613e5d8 VA: 0x75987565d8
	public PreserveReferencesHandling get_PreserveReferencesHandling() { }
	// RVA: 0x613e628 VA: 0x7598756628
	public TypeNameHandling get_TypeNameHandling() { }
	// RVA: 0x613e678 VA: 0x7598756678
	public Void set_TypeNameHandling(TypeNameHandling value) { }
	// RVA: 0x613e6e0 VA: 0x75987566e0
	public MetadataPropertyHandling get_MetadataPropertyHandling() { }
	// RVA: 0x613e730 VA: 0x7598756730
	public FormatterAssemblyStyle get_TypeNameAssemblyFormat() { }
	// RVA: 0x613e780 VA: 0x7598756780
	public Void set_TypeNameAssemblyFormat(FormatterAssemblyStyle value) { }
	// RVA: 0x613e7e8 VA: 0x75987567e8
	public ConstructorHandling get_ConstructorHandling() { }
	// RVA: 0x613e838 VA: 0x7598756838
	public IContractResolver get_ContractResolver() { }
	// RVA: 0x613e840 VA: 0x7598756840
	public Void set_ContractResolver(IContractResolver value) { }
	// RVA: 0x613e848 VA: 0x7598756848
	public IEqualityComparer get_EqualityComparer() { }
	// RVA: 0x613e850 VA: 0x7598756850
	public Func`1 get_ReferenceResolverProvider() { }
	// RVA: 0x613e858 VA: 0x7598756858
	public ITraceWriter get_TraceWriter() { }
	// RVA: 0x613e860 VA: 0x7598756860
	public SerializationBinder get_Binder() { }
	// RVA: 0x613e868 VA: 0x7598756868
	public EventHandler`1 get_Error() { }
	// RVA: 0x613e870 VA: 0x7598756870
	public StreamingContext get_Context() { }
	// RVA: 0x613e900 VA: 0x7598756900
	public Void set_Formatting(Formatting value) { }
	// RVA: 0x613e968 VA: 0x7598756968
	private static Void .cctor() { }
	// RVA: 0x613e9f0 VA: 0x75987569f0
	public Void .ctor() { }
}
```