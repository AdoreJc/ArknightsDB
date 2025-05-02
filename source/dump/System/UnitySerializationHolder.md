# UnitySerializationHolder

**Namespace:** `System`


## Fields

- `Int32 m_genericParameterPosition`

- `Type m_declaringType`

- `MethodBase m_declaringMethod`

- `String m_data`

- `String m_assemblyName`

- `Int32 m_unityType`


## Methods

- `Void ThrowInsufficientInformation(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class UnitySerializationHolder : ISerializable, IObjectReference
{
	private Type[] m_instantiation; // 0x10
	private Int32[] m_elementTypes; // 0x18
	private Int32 m_genericParameterPosition; // 0x20
	private Type m_declaringType; // 0x28
	private MethodBase m_declaringMethod; // 0x30
	private String m_data; // 0x38
	private String m_assemblyName; // 0x40
	private Int32 m_unityType; // 0x48


	// RVA: 0x60f84a4 VA: 0x75987104a4
	internal static RuntimeType AddElementTypes(SerializationInfo info, RuntimeType type) { }
	// RVA: 0x60f8870 VA: 0x7598710870
	internal Type MakeElementTypes(Type type) { }
	// RVA: 0x60f8968 VA: 0x7598710968
	internal static Void GetUnitySerializationInfo(SerializationInfo info, Int32 unityType) { }
	// RVA: 0x60f8abc VA: 0x7598710abc
	internal static Void GetUnitySerializationInfo(SerializationInfo info, RuntimeType type) { }
	// RVA: 0x60f8e44 VA: 0x7598710e44
	internal static Void GetUnitySerializationInfo(SerializationInfo info, Int32 unityType, String data, RuntimeAssembly assembly) { }
	// RVA: 0x60f8fd0 VA: 0x7598710fd0
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60f9494 VA: 0x7598711494
	private Void ThrowInsufficientInformation(String field) { }
	// RVA: 0x60f95a0 VA: 0x75987115a0
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60f95f8 VA: 0x75987115f8
	public virtual Object GetRealObject(StreamingContext context) { }
}
```