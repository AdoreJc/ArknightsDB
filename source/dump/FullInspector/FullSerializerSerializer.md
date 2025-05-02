# FullSerializerSerializer

**Namespace:** `FullInspector`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class FullSerializerSerializer : BaseSerializer
{
	private static fsSerializer _serializer; // 0xffffffffffffffff
	private static readonly List`1 _serializers; // 0x0
	private static readonly List`1 _converters; // 0x8
	private static readonly List`1 _processors; // 0x10

	private static fsSerializer Serializer { get; }
	public override Boolean SupportsMultithreading { get; }

	// RVA: 0x34cca00 VA: 0x7595ae4a00
	private static fsSerializer get_Serializer() { }
	// RVA: 0x VA: 0x0
	public static Void AddConverter() { }
	// RVA: 0x VA: 0x0
	public static Void AddProcessor() { }
	// RVA: 0x34ccff4 VA: 0x7595ae4ff4
	private static Void .cctor() { }
	// RVA: 0x34cd14c VA: 0x7595ae514c
	public override String Serialize(MemberInfo storageType, Object value, ISerializationOperator serializationOperator) { }
	// RVA: 0x34cd38c VA: 0x7595ae538c
	public override Object Deserialize(MemberInfo storageType, String serializedState, ISerializationOperator serializationOperator) { }
	// RVA: 0x34cd4b0 VA: 0x7595ae54b0
	public override Boolean get_SupportsMultithreading() { }
	// RVA: 0x34cd26c VA: 0x7595ae526c
	private static Boolean EmitFailWarning(fsResult result) { }
	// RVA: 0x34cd4b8 VA: 0x7595ae54b8
	public Void .ctor() { }
}
```