# SerializationCallbackReceiverObjectProcessor

**Namespace:** `FullInspector.Serializers.FullSerializer`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Serializers.FullSerializer
public class SerializationCallbackReceiverObjectProcessor : fsObjectProcessor
{


	// RVA: 0x34d8718 VA: 0x7595af0718
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34d891c VA: 0x7595af091c
	public override Void OnBeforeSerialize(Type storageType, Object instance) { }
	// RVA: 0x34d89f0 VA: 0x7595af09f0
	public override Void OnAfterSerialize(Type storageType, Object instance, ref fsData data) { }
	// RVA: 0x34d89f4 VA: 0x7595af09f4
	public override Void OnBeforeDeserialize(Type storageType, ref fsData data) { }
	// RVA: 0x34d89f8 VA: 0x7595af09f8
	public override Void OnAfterDeserialize(Type storageType, Object instance) { }
	// RVA: 0x34d8ad0 VA: 0x7595af0ad0
	public Void .ctor() { }
}
```