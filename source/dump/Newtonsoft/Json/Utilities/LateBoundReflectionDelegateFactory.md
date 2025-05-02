# LateBoundReflectionDelegateFactory

**Namespace:** `Newtonsoft.Json.Utilities`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Utilities
internal class LateBoundReflectionDelegateFactory : ReflectionDelegateFactory
{
	private static readonly LateBoundReflectionDelegateFactory _instance; // 0x0

	internal static ReflectionDelegateFactory Instance { get; }

	// RVA: 0x6153a9c VA: 0x759876ba9c
	internal static ReflectionDelegateFactory get_Instance() { }
	// RVA: 0x6153af4 VA: 0x759876baf4
	public override ObjectConstructor`1 CreateParameterizedConstructor(MethodBase method) { }
	// RVA: 0x VA: 0x0
	public override MethodCall`2 CreateMethodCall(MethodBase method) { }
	// RVA: 0x VA: 0x0
	public override Func`1 CreateDefaultConstructor(Type type) { }
	// RVA: 0x VA: 0x0
	public override Func`2 CreateGet(PropertyInfo propertyInfo) { }
	// RVA: 0x VA: 0x0
	public override Func`2 CreateGet(FieldInfo fieldInfo) { }
	// RVA: 0x VA: 0x0
	public override Action`2 CreateSet(FieldInfo fieldInfo) { }
	// RVA: 0x VA: 0x0
	public override Action`2 CreateSet(PropertyInfo propertyInfo) { }
	// RVA: 0x6153c9c VA: 0x759876bc9c
	public Void .ctor() { }
	// RVA: 0x6153ca4 VA: 0x759876bca4
	private static Void .cctor() { }
}
```