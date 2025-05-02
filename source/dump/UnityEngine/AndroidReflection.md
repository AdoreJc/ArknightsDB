# AndroidReflection

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.AndroidJNIModule.dll
// Namespace : UnityEngine
internal class AndroidReflection
{
	private static readonly GlobalJavaObjectRef s_ReflectionHelperClass; // 0x0
	private static readonly IntPtr s_ReflectionHelperGetConstructorID; // 0x8
	private static readonly IntPtr s_ReflectionHelperGetMethodID; // 0x10
	private static readonly IntPtr s_ReflectionHelperGetFieldID; // 0x18
	private static readonly IntPtr s_ReflectionHelperGetFieldSignature; // 0x20
	private static readonly IntPtr s_ReflectionHelperNewProxyInstance; // 0x28
	private static readonly IntPtr s_ReflectionHelperSetNativeExceptionOnProxy; // 0x30
	private static readonly IntPtr s_FieldGetDeclaringClass; // 0x38


	// RVA: 0x68389e4 VA: 0x7598e509e4
	public static Boolean IsPrimitive(Type t) { }
	// RVA: 0x68389f8 VA: 0x7598e509f8
	public static Boolean IsAssignableFrom(Type t, Type from) { }
	// RVA: 0x6838a18 VA: 0x7598e50a18
	private static IntPtr GetStaticMethodID(String clazz, String methodName, String signature) { }
	// RVA: 0x6838b6c VA: 0x7598e50b6c
	private static IntPtr GetMethodID(String clazz, String methodName, String signature) { }
	// RVA: 0x6838cc0 VA: 0x7598e50cc0
	public static IntPtr GetConstructorMember(IntPtr jclass, String signature) { }
	// RVA: 0x6838fa4 VA: 0x7598e50fa4
	public static IntPtr GetMethodMember(IntPtr jclass, String methodName, String signature, Boolean isStatic) { }
	// RVA: 0x68391a4 VA: 0x7598e511a4
	public static IntPtr GetFieldMember(IntPtr jclass, String fieldName, String signature, Boolean isStatic) { }
	// RVA: 0x68393a4 VA: 0x7598e513a4
	public static IntPtr GetFieldClass(IntPtr field) { }
	// RVA: 0x68394c0 VA: 0x7598e514c0
	public static String GetFieldSignature(IntPtr field) { }
	// RVA: 0x6839620 VA: 0x7598e51620
	public static IntPtr NewProxyInstance(IntPtr player, IntPtr delegateHandle, IntPtr interfaze) { }
	// RVA: 0x6835e60 VA: 0x7598e4de60
	public static Void SetNativeExceptionOnProxy(IntPtr proxy, Exception e, Boolean methodNotFound) { }
	// RVA: 0x6839704 VA: 0x7598e51704
	private static Void .cctor() { }
}
```