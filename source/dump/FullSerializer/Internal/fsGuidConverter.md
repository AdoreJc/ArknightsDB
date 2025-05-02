# fsGuidConverter

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsGuidConverter : fsConverter
{


	// RVA: 0x34bf764 VA: 0x7595ad7764
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34bf7ec VA: 0x7595ad77ec
	public override Boolean RequestCycleSupport(Type storageType) { }
	// RVA: 0x34bf7f4 VA: 0x7595ad77f4
	public override Boolean RequestInheritanceSupport(Type storageType) { }
	// RVA: 0x34bf7fc VA: 0x7595ad77fc
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34bf910 VA: 0x7595ad7910
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34bfa20 VA: 0x7595ad7a20
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34b632c VA: 0x7595ace32c
	public Void .ctor() { }
}
```