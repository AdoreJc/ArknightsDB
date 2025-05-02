# fsKeyValuePairConverter

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsKeyValuePairConverter : fsConverter
{


	// RVA: 0x34c0df8 VA: 0x7595ad8df8
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34c0ee8 VA: 0x7595ad8ee8
	public override Boolean RequestCycleSupport(Type storageType) { }
	// RVA: 0x34c0ef0 VA: 0x7595ad8ef0
	public override Boolean RequestInheritanceSupport(Type storageType) { }
	// RVA: 0x34c0ef8 VA: 0x7595ad8ef8
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34c11d8 VA: 0x7595ad91d8
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34b636c VA: 0x7595ace36c
	public Void .ctor() { }
}
```