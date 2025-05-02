# fsArrayConverter

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsArrayConverter : fsConverter
{


	// RVA: 0x34bbc28 VA: 0x7595ad3c28
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34bbc40 VA: 0x7595ad3c40
	public override Boolean RequestCycleSupport(Type storageType) { }
	// RVA: 0x34bbc48 VA: 0x7595ad3c48
	public override Boolean RequestInheritanceSupport(Type storageType) { }
	// RVA: 0x34bbc50 VA: 0x7595ad3c50
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34bbfd4 VA: 0x7595ad3fd4
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34bc260 VA: 0x7595ad4260
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34b6354 VA: 0x7595ace354
	public Void .ctor() { }
}
```