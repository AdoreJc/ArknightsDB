# ArgumentCache

**Namespace:** `UnityEngine.Events`


## Fields

- `Object m_ObjectArgument`

- `String m_ObjectArgumentAssemblyTypeName`

- `Int32 m_IntArgument`

- `Single m_FloatArgument`

- `String m_StringArgument`

- `Boolean m_BoolArgument`


## Properties

- `Object unityObjectArgument`

- `String unityObjectArgumentAssemblyTypeName`

- `Int32 intArgument`

- `Single floatArgument`

- `String stringArgument`

- `Boolean boolArgument`


## Methods

- `Object get_unityObjectArgument()`

- `String get_unityObjectArgumentAssemblyTypeName()`

- `Int32 get_intArgument()`

- `Single get_floatArgument()`

- `String get_stringArgument()`

- `Boolean get_boolArgument()`

- `Void OnBeforeSerialize()`

- `Void OnAfterDeserialize()`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Events
internal class ArgumentCache : ISerializationCallbackReceiver
{
	private Object m_ObjectArgument; // 0x10
	private String m_ObjectArgumentAssemblyTypeName; // 0x18
	private Int32 m_IntArgument; // 0x20
	private Single m_FloatArgument; // 0x24
	private String m_StringArgument; // 0x28
	private Boolean m_BoolArgument; // 0x30

	public Object unityObjectArgument { get; }
	public String unityObjectArgumentAssemblyTypeName { get; }
	public Int32 intArgument { get; }
	public Single floatArgument { get; }
	public String stringArgument { get; }
	public Boolean boolArgument { get; }

	// RVA: 0x68968a0 VA: 0x7598eae8a0
	public Object get_unityObjectArgument() { }
	// RVA: 0x68968a8 VA: 0x7598eae8a8
	public String get_unityObjectArgumentAssemblyTypeName() { }
	// RVA: 0x68968b0 VA: 0x7598eae8b0
	public Int32 get_intArgument() { }
	// RVA: 0x68968b8 VA: 0x7598eae8b8
	public Single get_floatArgument() { }
	// RVA: 0x68968c0 VA: 0x7598eae8c0
	public String get_stringArgument() { }
	// RVA: 0x68968c8 VA: 0x7598eae8c8
	public Boolean get_boolArgument() { }
	// RVA: 0x68968d0 VA: 0x7598eae8d0
	public Void OnBeforeSerialize() { }
	// RVA: 0x68968f4 VA: 0x7598eae8f4
	public Void OnAfterDeserialize() { }
	// RVA: 0x6896918 VA: 0x7598eae918
	public Void .ctor() { }
}
```