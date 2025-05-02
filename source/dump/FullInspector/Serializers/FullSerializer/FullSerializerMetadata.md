# FullSerializerMetadata

**Namespace:** `FullInspector.Serializers.FullSerializer`


## Properties

- `Guid SerializerGuid`

- `Type SerializerType`


## Methods

- `Guid get_SerializerGuid()`

- `Type get_SerializerType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Serializers.FullSerializer
public class FullSerializerMetadata : fiISerializerMetadata
{

	public Guid SerializerGuid { get; }
	public Type SerializerType { get; }
	public Type[] SerializationOptInAnnotationTypes { get; }
	public Type[] SerializationOptOutAnnotationTypes { get; }

	// RVA: 0x34d8f5c VA: 0x7595af0f5c
	public Guid get_SerializerGuid() { }
	// RVA: 0x34d8fb8 VA: 0x7595af0fb8
	public Type get_SerializerType() { }
	// RVA: 0x34d9024 VA: 0x7595af1024
	public Type[] get_SerializationOptInAnnotationTypes() { }
	// RVA: 0x34d916c VA: 0x7595af116c
	public Type[] get_SerializationOptOutAnnotationTypes() { }
	// RVA: 0x34d925c VA: 0x7595af125c
	public Void .ctor() { }
}
```