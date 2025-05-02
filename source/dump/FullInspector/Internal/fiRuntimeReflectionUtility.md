# fiRuntimeReflectionUtility

**Namespace:** `FullInspector.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Internal
public class fiRuntimeReflectionUtility
{
	private static List`1 _cachedRuntimeAssemblies; // 0x0
	private static List`1 _cachedUserDefinedEditorAssemblies; // 0x8
	private static List`1 _cachedAllEditorAssembles; // 0x10


	// RVA: 0x34de21c VA: 0x7595af621c
	public static Object InvokeStaticMethod(Type type, String methodName, Object[] parameters) { }
	// RVA: 0x34de324 VA: 0x7595af6324
	public static Object InvokeStaticMethod(String typeName, String methodName, Object[] parameters) { }
	// RVA: 0x34de398 VA: 0x7595af6398
	public static Void InvokeMethod(Type type, String methodName, Object thisInstance, Object[] parameters) { }
	// RVA: 0x VA: 0x0
	public static T ReadField(TContext context, String fieldName) { }
	// RVA: 0x VA: 0x0
	public static T ReadFields(TContext context, String[] fieldNames) { }
	// RVA: 0x VA: 0x0
	public static IEnumerable`1 GetAssemblyInstances() { }
	// RVA: 0x34de4b4 VA: 0x7595af64b4
	public static IEnumerable`1 GetUnityObjectTypes() { }
	// RVA: 0x34dedd8 VA: 0x7595af6dd8
	private static String GetName(Assembly assembly) { }
	// RVA: 0x34de928 VA: 0x7595af6928
	public static IEnumerable`1 GetRuntimeAssemblies() { }
	// RVA: 0x34df2b0 VA: 0x7595af72b0
	public static IEnumerable`1 GetUserDefinedEditorAssemblies() { }
	// RVA: 0x34df6d0 VA: 0x7595af76d0
	public static IEnumerable`1 GetAllEditorAssemblies() { }
	// RVA: 0x34dfa54 VA: 0x7595af7a54
	private static Boolean IsUnityEditorAssembly(Assembly assembly) { }
	// RVA: 0x34dfb98 VA: 0x7595af7b98
	private static Boolean IsBannedAssembly(Assembly assembly) { }
	// RVA: 0x34e1050 VA: 0x7595af9050
	public static IEnumerable`1 AllSimpleTypesDerivingFrom(Type baseType) { }
	// RVA: 0x34e14bc VA: 0x7595af94bc
	public static IEnumerable`1 AllSimpleCreatableTypesDerivingFrom(Type baseType) { }
	// RVA: 0x34e1710 VA: 0x7595af9710
	public Void .ctor() { }
}
```