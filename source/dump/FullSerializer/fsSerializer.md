# fsSerializer

**Namespace:** `FullSerializer`


## Fields

- `fsContext Context`

- `fsConfig Config`


## Methods

- `Void AddProcessor(fsObjectProcessor)`

- `Void RemoveProcessor()`

- `Void AddConverter(fsBaseConverter)`

- `fsBaseConverter GetConverter(Type, Type)`

- `fsResult TrySerialize(T, out)`

- `fsResult TryDeserialize(fsData, ref)`

- `fsResult TrySerialize(Type, Object, out)`

- `fsResult TrySerialize(Type, Type, Object, out)`

- `fsResult InternalSerialize_1_ProcessCycles(Type, Type, Object, out)`

- `fsResult InternalSerialize_2_Inheritance(Type, Type, Object, out)`

- `fsResult InternalSerialize_3_ProcessVersioning(Type, Object, out)`

- `fsResult InternalSerialize_4_Converter(Type, Object, out)`

- `fsResult TryDeserialize(fsData, Type, ref)`

- `fsResult TryDeserialize(fsData, Type, Type, ref)`

- `fsResult InternalDeserialize_1_CycleReference(Type, fsData, Type, ref, out)`

- `fsResult InternalDeserialize_2_Version(Type, fsData, Type, ref, out)`

- `fsResult InternalDeserialize_3_Inheritance(Type, fsData, Type, ref, out)`

- `fsResult InternalDeserialize_4_Cycles(Type, fsData, Type, ref)`

- `fsResult InternalDeserialize_5_Converter(Type, fsData, Type, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer
public class fsSerializer
{
	private static HashSet`1 _reservedKeywords; // 0x0
	private const String Key_ObjectReference; // 0x0
	private const String Key_ObjectDefinition; // 0x0
	private const String Key_InstanceType; // 0x0
	private const String Key_Version; // 0x0
	private const String Key_Content; // 0x0
	private Dictionary`2 _cachedConverterTypeInstances; // 0x10
	private Dictionary`2 _cachedConverters; // 0x18
	private Dictionary`2 _cachedProcessors; // 0x20
	private readonly List`1 _availableConverters; // 0x28
	private readonly Dictionary`2 _availableDirectConverters; // 0x30
	private readonly List`1 _processors; // 0x38
	private readonly fsCyclicReferenceManager _references; // 0x40
	private readonly fsLazyCycleDefinitionWriter _lazyReferenceWriter; // 0x48
	public fsContext Context; // 0x50
	public fsConfig Config; // 0x58


	// RVA: 0x34b45ec VA: 0x7595acc5ec
	private static Void .cctor() { }
	// RVA: 0x34b4764 VA: 0x7595acc764
	public static Boolean IsReservedKeyword(String key) { }
	// RVA: 0x34b47e4 VA: 0x7595acc7e4
	private static Boolean IsObjectReference(fsData data) { }
	// RVA: 0x34b4878 VA: 0x7595acc878
	private static Boolean IsObjectDefinition(fsData data) { }
	// RVA: 0x34b490c VA: 0x7595acc90c
	private static Boolean IsVersioned(fsData data) { }
	// RVA: 0x34b49a0 VA: 0x7595acc9a0
	private static Boolean IsTypeSpecified(fsData data) { }
	// RVA: 0x34b4a34 VA: 0x7595acca34
	private static Boolean IsWrappedData(fsData data) { }
	// RVA: 0x34b4ac8 VA: 0x7595accac8
	public static Void StripDeserializationMetadata(ref fsData data) { }
	// RVA: 0x34b4c7c VA: 0x7595accc7c
	private static Void ConvertLegacyData(ref fsData data) { }
	// RVA: 0x34b50c8 VA: 0x7595acd0c8
	private static Void Invoke_OnBeforeSerialize(List`1 processors, Type storageType, Object instance) { }
	// RVA: 0x34b5174 VA: 0x7595acd174
	private static Void Invoke_OnAfterSerialize(List`1 processors, Type storageType, Object instance, ref fsData data) { }
	// RVA: 0x34b5224 VA: 0x7595acd224
	private static Void Invoke_OnBeforeDeserialize(List`1 processors, Type storageType, ref fsData data) { }
	// RVA: 0x34b52d0 VA: 0x7595acd2d0
	private static Void Invoke_OnBeforeDeserializeAfterInstanceCreation(List`1 processors, Type storageType, Object instance, ref fsData data) { }
	// RVA: 0x34b538c VA: 0x7595acd38c
	private static Void Invoke_OnAfterDeserialize(List`1 processors, Type storageType, Object instance) { }
	// RVA: 0x34b5018 VA: 0x7595acd018
	private static Void EnsureDictionary(fsData data) { }
	// RVA: 0x34b542c VA: 0x7595acd42c
	public Void .ctor() { }
	// RVA: 0x34b65f4 VA: 0x7595ace5f4
	public Void AddProcessor(fsObjectProcessor processor) { }
	// RVA: 0x VA: 0x0
	public Void RemoveProcessor() { }
	// RVA: 0x34b66f0 VA: 0x7595ace6f0
	private List`1 GetProcessors(Type type) { }
	// RVA: 0x34b6394 VA: 0x7595ace394
	public Void AddConverter(fsBaseConverter converter) { }
	// RVA: 0x34b6a2c VA: 0x7595acea2c
	private fsBaseConverter GetConverter(Type type, Type overrideConverterType) { }
	// RVA: 0x VA: 0x0
	public fsResult TrySerialize(T instance, out fsData data) { }
	// RVA: 0x VA: 0x0
	public fsResult TryDeserialize(fsData data, ref T instance) { }
	// RVA: 0x34b6ee0 VA: 0x7595aceee0
	public fsResult TrySerialize(Type storageType, Object instance, out fsData data) { }
	// RVA: 0x34b6ef0 VA: 0x7595aceef0
	public fsResult TrySerialize(Type storageType, Type overrideConverterType, Object instance, out fsData data) { }
	// RVA: 0x34b7084 VA: 0x7595acf084
	private fsResult InternalSerialize_1_ProcessCycles(Type storageType, Type overrideConverterType, Object instance, out fsData data) { }
	// RVA: 0x34b73b4 VA: 0x7595acf3b4
	private fsResult InternalSerialize_2_Inheritance(Type storageType, Type overrideConverterType, Object instance, out fsData data) { }
	// RVA: 0x34b7b90 VA: 0x7595acfb90
	private fsResult InternalSerialize_3_ProcessVersioning(Type overrideConverterType, Object instance, out fsData data) { }
	// RVA: 0x34b821c VA: 0x7595ad021c
	private fsResult InternalSerialize_4_Converter(Type overrideConverterType, Object instance, out fsData data) { }
	// RVA: 0x34b8288 VA: 0x7595ad0288
	public fsResult TryDeserialize(fsData data, Type storageType, ref Object result) { }
	// RVA: 0x34b8294 VA: 0x7595ad0294
	public fsResult TryDeserialize(fsData data, Type storageType, Type overrideConverterType, ref Object result) { }
	// RVA: 0x34b84c4 VA: 0x7595ad04c4
	private fsResult InternalDeserialize_1_CycleReference(Type overrideConverterType, fsData data, Type storageType, ref Object result, out List`1 processors) { }
	// RVA: 0x34b8760 VA: 0x7595ad0760
	private fsResult InternalDeserialize_2_Version(Type overrideConverterType, fsData data, Type storageType, ref Object result, out List`1 processors) { }
	// RVA: 0x34b8f4c VA: 0x7595ad0f4c
	private fsResult InternalDeserialize_3_Inheritance(Type overrideConverterType, fsData data, Type storageType, ref Object result, out List`1 processors) { }
	// RVA: 0x34b94f0 VA: 0x7595ad14f0
	private fsResult InternalDeserialize_4_Cycles(Type overrideConverterType, fsData data, Type resultType, ref Object result) { }
	// RVA: 0x34b95f8 VA: 0x7595ad15f8
	private fsResult InternalDeserialize_5_Converter(Type overrideConverterType, fsData data, Type resultType, ref Object result) { }
}
```