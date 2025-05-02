# fsTypeConverter

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsTypeConverter : fsConverter
{


	// RVA: 0x34c2ff4 VA: 0x7595adaff4
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34c3088 VA: 0x7595adb088
	public override Boolean RequestCycleSupport(Type type) { }
	// RVA: 0x34c3090 VA: 0x7595adb090
	public override Boolean RequestInheritanceSupport(Type type) { }
	// RVA: 0x34c3098 VA: 0x7595adb098
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34c31a8 VA: 0x7595adb1a8
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34c3304 VA: 0x7595adb304
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34b6334 VA: 0x7595ace334
	public Void .ctor() { }
}
```