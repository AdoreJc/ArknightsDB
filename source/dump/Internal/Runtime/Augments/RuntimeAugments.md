# RuntimeAugments

**Namespace:** `Internal.Runtime.Augments`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Internal.Runtime.Augments
internal class RuntimeAugments
{
	private static ReflectionExecutionDomainCallbacks s_reflectionExecutionDomainCallbacks; // 0x0

	internal static ReflectionExecutionDomainCallbacks Callbacks { get; }

	// RVA: 0x5f1b52c VA: 0x759853352c
	public static Void ReportUnhandledException(Exception exception) { }
	// RVA: 0x5f1b54c VA: 0x759853354c
	internal static ReflectionExecutionDomainCallbacks get_Callbacks() { }
	// RVA: 0x5f1b5a4 VA: 0x75985335a4
	private static Void .cctor() { }
}
```