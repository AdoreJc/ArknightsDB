# fsWeakReferenceConverter

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsWeakReferenceConverter : fsConverter
{


	// RVA: 0x34c330c VA: 0x7595adb30c
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34c3394 VA: 0x7595adb394
	public override Boolean RequestCycleSupport(Type storageType) { }
	// RVA: 0x34c339c VA: 0x7595adb39c
	public override Boolean RequestInheritanceSupport(Type storageType) { }
	// RVA: 0x34c33a4 VA: 0x7595adb3a4
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34c3610 VA: 0x7595adb610
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34c38e4 VA: 0x7595adb8e4
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34b6374 VA: 0x7595ace374
	public Void .ctor() { }
}
```