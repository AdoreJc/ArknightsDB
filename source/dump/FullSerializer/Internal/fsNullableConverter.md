# fsNullableConverter

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsNullableConverter : fsConverter
{


	// RVA: 0x34c1578 VA: 0x7595ad9578
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34c1668 VA: 0x7595ad9668
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34c16b0 VA: 0x7595ad96b0
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34c16f8 VA: 0x7595ad96f8
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34b6324 VA: 0x7595ace324
	public Void .ctor() { }
}
```