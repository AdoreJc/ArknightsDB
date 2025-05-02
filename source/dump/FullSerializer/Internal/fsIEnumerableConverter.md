# fsIEnumerableConverter

**Namespace:** `FullSerializer.Internal`


## Methods

- `Boolean IsStack(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsIEnumerableConverter : fsConverter
{


	// RVA: 0x34bfa74 VA: 0x7595ad7a74
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34bfcc4 VA: 0x7595ad7cc4
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34bfd38 VA: 0x7595ad7d38
	public override fsResult TrySerialize(Object instance_, out fsData serialized, Type storageType) { }
	// RVA: 0x34c0458 VA: 0x7595ad8458
	private Boolean IsStack(Type type) { }
	// RVA: 0x34c0558 VA: 0x7595ad8558
	public override fsResult TryDeserialize(fsData data, ref Object instance_, Type storageType) { }
	// RVA: 0x34c0358 VA: 0x7595ad8358
	private static Int32 HintSize(IEnumerable collection) { }
	// RVA: 0x34c0228 VA: 0x7595ad8228
	private static Type GetElementType(Type objectType) { }
	// RVA: 0x34c0a1c VA: 0x7595ad8a1c
	private static Void TryClear(Type type, Object instance) { }
	// RVA: 0x34c0ad4 VA: 0x7595ad8ad4
	private static Int32 TryGetExistingSize(Type type, Object instance) { }
	// RVA: 0x34bfb34 VA: 0x7595ad7b34
	private static MethodInfo GetAddMethod(Type type) { }
	// RVA: 0x34b6364 VA: 0x7595ace364
	public Void .ctor() { }
}
```