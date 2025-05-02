# fsEnumConverter

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsEnumConverter : fsConverter
{


	// RVA: 0x34be4d0 VA: 0x7595ad64d0
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34be538 VA: 0x7595ad6538
	public override Boolean RequestCycleSupport(Type storageType) { }
	// RVA: 0x34be540 VA: 0x7595ad6540
	public override Boolean RequestInheritanceSupport(Type storageType) { }
	// RVA: 0x34be548 VA: 0x7595ad6548
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34be5dc VA: 0x7595ad65dc
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34beb04 VA: 0x7595ad6b04
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x VA: 0x0
	private static Boolean ArrayContains(T[] values, T value) { }
	// RVA: 0x34b6344 VA: 0x7595ace344
	public Void .ctor() { }
}
```