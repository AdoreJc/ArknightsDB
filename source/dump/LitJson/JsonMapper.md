# JsonMapper

**Namespace:** `LitJson`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : LitJson
public class JsonMapper
{
	private static Int32 max_nesting_depth; // 0x0
	private static IFormatProvider datetime_format; // 0x8
	private static IDictionary`2 base_exporters_table; // 0x10
	private static IDictionary`2 custom_exporters_table; // 0x18
	private static IDictionary`2 base_importers_table; // 0x20
	private static IDictionary`2 custom_importers_table; // 0x28
	private static IDictionary`2 array_metadata; // 0x30
	private static readonly Object array_metadata_lock; // 0x38
	private static IDictionary`2 conv_ops; // 0x40
	private static readonly Object conv_ops_lock; // 0x48
	private static IDictionary`2 object_metadata; // 0x50
	private static readonly Object object_metadata_lock; // 0x58
	private static IDictionary`2 type_properties; // 0x60
	private static readonly Object type_properties_lock; // 0x68
	private static JsonWriter static_writer; // 0x70
	private static readonly Object static_writer_lock; // 0x78


	// RVA: 0x65e800c VA: 0x7598c0000c
	private static Void .cctor() { }
	// RVA: 0x65e9d08 VA: 0x7598c01d08
	private static Boolean HasInterface(Type type, String name) { }
	// RVA: 0x65e9d94 VA: 0x7598c01d94
	public static PropertyInfo[] GetPublicInstanceProperties(Type type) { }
	// RVA: 0x65e9da8 VA: 0x7598c01da8
	private static Void AddArrayMetadata(Type type) { }
	// RVA: 0x65ea228 VA: 0x7598c02228
	private static Void AddObjectMetadata(Type type) { }
	// RVA: 0x65ea990 VA: 0x7598c02990
	private static Void AddTypeProperties(Type type) { }
	// RVA: 0x65eaedc VA: 0x7598c02edc
	private static MethodInfo GetConvOp(Type t1, Type t2) { }
	// RVA: 0x65eb768 VA: 0x7598c03768
	private static Object ReadValue(Type inst_type, JsonReader reader) { }
	// RVA: 0x65ecd10 VA: 0x7598c04d10
	private static IJsonWrapper ReadValue(WrapperFactory factory, JsonReader reader) { }
	// RVA: 0x65ecc08 VA: 0x7598c04c08
	private static Void ReadSkip(JsonReader reader) { }
	// RVA: 0x65e84f4 VA: 0x7598c004f4
	private static Void RegisterBaseExporters() { }
	// RVA: 0x65e90d8 VA: 0x7598c010d8
	private static Void RegisterBaseImporters() { }
	// RVA: 0x65ed3d0 VA: 0x7598c053d0
	private static Void RegisterImporter(IDictionary`2 table, Type json_type, Type value_type, ImporterFunc importer) { }
	// RVA: 0x65ed614 VA: 0x7598c05614
	private static Void WriteValue(Object obj, JsonWriter writer, Boolean writer_is_private, Int32 depth) { }
	// RVA: 0x65ef6f8 VA: 0x7598c076f8
	public static String ToJson(Object obj) { }
	// RVA: 0x65ef960 VA: 0x7598c07960
	public static Void ToJson(Object obj, JsonWriter writer) { }
	// RVA: 0x65ef9cc VA: 0x7598c079cc
	public static JsonData ToObject(JsonReader reader) { }
	// RVA: 0x65efb20 VA: 0x7598c07b20
	public static JsonData ToObject(TextReader reader) { }
	// RVA: 0x65efcac VA: 0x7598c07cac
	public static JsonData ToObject(String json) { }
	// RVA: 0x VA: 0x0
	public static T ToObject(JsonReader reader) { }
	// RVA: 0x VA: 0x0
	public static T ToObject(TextReader reader) { }
	// RVA: 0x VA: 0x0
	public static T ToObject(String json) { }
	// RVA: 0x65ed36c VA: 0x7598c0536c
	public static IJsonWrapper ToWrapper(WrapperFactory factory, JsonReader reader) { }
	// RVA: 0x65efe00 VA: 0x7598c07e00
	public static IJsonWrapper ToWrapper(WrapperFactory factory, String json) { }
	// RVA: 0x VA: 0x0
	public static Void RegisterExporter(ExporterFunc`1 exporter) { }
	// RVA: 0x VA: 0x0
	public static Void RegisterImporter(ImporterFunc`2 importer) { }
	// RVA: 0x65eff0c VA: 0x7598c07f0c
	public static Void UnregisterExporters() { }
	// RVA: 0x65effd8 VA: 0x7598c07fd8
	public static Void UnregisterImporters() { }
	// RVA: 0x65f00a4 VA: 0x7598c080a4
	public Void .ctor() { }
}
```