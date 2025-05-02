# UnityObjectConverter

**Namespace:** `FullInspector.Serializers.FullSerializer`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Serializers.FullSerializer
public class UnityObjectConverter : fsConverter
{


	// RVA: 0x34d8ad8 VA: 0x7595af0ad8
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34d8bb8 VA: 0x7595af0bb8
	public override Boolean RequestCycleSupport(Type storageType) { }
	// RVA: 0x34d8bc0 VA: 0x7595af0bc0
	public override Boolean RequestInheritanceSupport(Type storageType) { }
	// RVA: 0x34d8bc8 VA: 0x7595af0bc8
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34d8d9c VA: 0x7595af0d9c
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34d8f4c VA: 0x7595af0f4c
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34d8f54 VA: 0x7595af0f54
	public Void .ctor() { }
}
```