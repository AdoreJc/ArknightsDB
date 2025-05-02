# fsAotCompilationManager

**Namespace:** `FullSerializer`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer
public class fsAotCompilationManager
{
	private static Dictionary`2 _computedAotCompilations; // 0x0
	private static List`1 _uncomputedAotCompilations; // 0x8

	public static Dictionary`2 AvailableAotCompilations { get; }

	// RVA: 0x34940fc VA: 0x7595aac0fc
	public static Dictionary`2 get_AvailableAotCompilations() { }
	// RVA: 0x349530c VA: 0x7595aad30c
	public static Boolean TryToPerformAotCompilation(fsConfig config, Type type, out String aotCompiledClassInCSharp) { }
	// RVA: 0x3495408 VA: 0x7595aad408
	public static Void AddAotCompilation(Type type, fsMetaProperty[] members, Boolean isConstructorPublic) { }
	// RVA: 0x3495578 VA: 0x7595aad578
	private static String GetConverterString(fsMetaProperty member) { }
	// RVA: 0x3494264 VA: 0x7595aac264
	private static String GenerateDirectConverterForTypeInCSharp(Type type, fsMetaProperty[] members, Boolean isConstructorPublic) { }
	// RVA: 0x3495640 VA: 0x7595aad640
	public Void .ctor() { }
	// RVA: 0x3495648 VA: 0x7595aad648
	private static Void .cctor() { }
}
```