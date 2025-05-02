# MemberInfoSerializationHolder

**Namespace:** `System.Reflection`


## Fields

- `String m_memberName`

- `RuntimeType m_reflectedType`

- `String m_signature`

- `String m_signature2`

- `MemberTypes m_memberType`

- `SerializationInfo m_info`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
internal class MemberInfoSerializationHolder : ISerializable, IObjectReference
{
	private String m_memberName; // 0x10
	private RuntimeType m_reflectedType; // 0x18
	private String m_signature; // 0x20
	private String m_signature2; // 0x28
	private MemberTypes m_memberType; // 0x30
	private SerializationInfo m_info; // 0x38


	// RVA: 0x5fed218 VA: 0x7598605218
	public static Void GetSerializationInfo(SerializationInfo info, String name, RuntimeType reflectedClass, String signature, MemberTypes type) { }
	// RVA: 0x5fed228 VA: 0x7598605228
	public static Void GetSerializationInfo(SerializationInfo info, String name, RuntimeType reflectedClass, String signature, String signature2, MemberTypes type, Type[] genericArguments) { }
	// RVA: 0x5fed53c VA: 0x759860553c
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fed8e8 VA: 0x75986058e8
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fed948 VA: 0x7598605948
	public virtual Object GetRealObject(StreamingContext context) { }
}
```