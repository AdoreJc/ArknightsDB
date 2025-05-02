# fsReflectedConverter

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsReflectedConverter : fsConverter
{


	// RVA: 0x34c2a74 VA: 0x7595adaa74
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34c2b4c VA: 0x7595adab4c
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34c2d64 VA: 0x7595adad64
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34c2f80 VA: 0x7595adaf80
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34b637c VA: 0x7595ace37c
	public Void .ctor() { }
}
```