# fsPrimitiveConverter

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsPrimitiveConverter : fsConverter
{


	// RVA: 0x34c1700 VA: 0x7595ad9700
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34c1814 VA: 0x7595ad9814
	public override Boolean RequestCycleSupport(Type storageType) { }
	// RVA: 0x34c181c VA: 0x7595ad981c
	public override Boolean RequestInheritanceSupport(Type storageType) { }
	// RVA: 0x34c1824 VA: 0x7595ad9824
	private static Boolean UseBool(Type type) { }
	// RVA: 0x34c18ac VA: 0x7595ad98ac
	private static Boolean UseInt64(Type type) { }
	// RVA: 0x34c1b40 VA: 0x7595ad9b40
	private static Boolean UseDouble(Type type) { }
	// RVA: 0x34c1c6c VA: 0x7595ad9c6c
	private static Boolean UseString(Type type) { }
	// RVA: 0x34c1d50 VA: 0x7595ad9d50
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34c2440 VA: 0x7595ada440
	public override fsResult TryDeserialize(fsData storage, ref Object instance, Type storageType) { }
	// RVA: 0x34b634c VA: 0x7595ace34c
	public Void .ctor() { }
}
```