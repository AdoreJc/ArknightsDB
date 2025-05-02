# StaticLuaCallbacks

**Namespace:** `XLua`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class StaticLuaCallbacks
{
	internal lua_CSFunction GcMeta; // 0x10
	internal lua_CSFunction ToStringMeta; // 0x18
	internal lua_CSFunction EnumAndMeta; // 0x20
	internal lua_CSFunction EnumOrMeta; // 0x28
	internal lua_CSFunction StaticCSFunctionWraper; // 0x30
	internal lua_CSFunction FixCSFunctionWraper; // 0x38
	internal lua_CSFunction DelegateCtor; // 0x40


	// RVA: 0x3ec642c VA: 0x75964de42c
	internal static Boolean __tryArrayGet(Type type, IntPtr L, ObjectTranslator translator, Object obj, Int32 index) { }
	// RVA: 0x3ec7234 VA: 0x75964df234
	internal static Boolean __tryArraySet(Type type, IntPtr L, ObjectTranslator translator, Object obj, Int32 array_idx, Int32 obj_idx) { }
	// RVA: 0x3ec80c4 VA: 0x75964e00c4
	public Void .ctor() { }
	// RVA: 0x3ec0ab4 VA: 0x75964d8ab4
	public static Int32 EnumAnd(IntPtr L) { }
	// RVA: 0x3ec0d90 VA: 0x75964d8d90
	public static Int32 EnumOr(IntPtr L) { }
	// RVA: 0x3ec106c VA: 0x75964d906c
	private static Int32 StaticCSFunction(IntPtr L) { }
	// RVA: 0x3ec1214 VA: 0x75964d9214
	private static Int32 FixCSFunction(IntPtr L) { }
	// RVA: 0x3ec1394 VA: 0x75964d9394
	public static Int32 DelegateCall(IntPtr L) { }
	// RVA: 0x3ec15a4 VA: 0x75964d95a4
	public static Int32 LuaGC(IntPtr L) { }
	// RVA: 0x3ec16e8 VA: 0x75964d96e8
	public static Int32 ToString(IntPtr L) { }
	// RVA: 0x3ec18e8 VA: 0x75964d98e8
	public static Int32 DelegateCombine(IntPtr L) { }
	// RVA: 0x3ec1b84 VA: 0x75964d9b84
	public static Int32 DelegateRemove(IntPtr L) { }
	// RVA: 0x3ec82ec VA: 0x75964e02ec
	private static Boolean tryPrimitiveArrayGet(Type type, IntPtr L, Object obj, Int32 index) { }
	// RVA: 0x3ec1e04 VA: 0x75964d9e04
	public static Int32 ArrayIndexer(IntPtr L) { }
	// RVA: 0x3ec8b00 VA: 0x75964e0b00
	public static Boolean TryPrimitiveArraySet(Type type, IntPtr L, Object obj, Int32 array_idx, Int32 obj_idx) { }
	// RVA: 0x3ec22a4 VA: 0x75964da2a4
	public static Int32 ArrayNewIndexer(IntPtr L) { }
	// RVA: 0x3ec2778 VA: 0x75964da778
	public static Int32 ArrayLength(IntPtr L) { }
	// RVA: 0x3ec292c VA: 0x75964da92c
	public static Int32 MetaFuncIndex(IntPtr L) { }
	// RVA: 0x3ec2b68 VA: 0x75964dab68
	internal static Int32 Panic(IntPtr L) { }
	// RVA: 0x3ec2bd8 VA: 0x75964dabd8
	internal static Int32 Print(IntPtr L) { }
	// RVA: 0x3ec2e58 VA: 0x75964dae58
	internal static Int32 LoadSocketCore(IntPtr L) { }
	// RVA: 0x3ec2e60 VA: 0x75964dae60
	internal static Int32 LoadCS(IntPtr L) { }
	// RVA: 0x3ec2ecc VA: 0x75964daecc
	internal static Int32 LoadBuiltinLib(IntPtr L) { }
	// RVA: 0x3ec30bc VA: 0x75964db0bc
	internal static Int32 LoadFromResource(IntPtr L) { }
	// RVA: 0x3ec33ec VA: 0x75964db3ec
	internal static Int32 LoadFromStreamingAssetsPath(IntPtr L) { }
	// RVA: 0x3ec37bc VA: 0x75964db7bc
	internal static Int32 LoadFromCustomLoaders(IntPtr L) { }
	// RVA: 0x3ec3b98 VA: 0x75964dbb98
	public static Int32 LoadAssembly(IntPtr L) { }
	// RVA: 0x3ec3e90 VA: 0x75964dbe90
	public static Int32 ImportType(IntPtr L) { }
	// RVA: 0x3ec40ec VA: 0x75964dc0ec
	public static Int32 ImportGenericType(IntPtr L) { }
	// RVA: 0x3ec4530 VA: 0x75964dc530
	public static Int32 Cast(IntPtr L) { }
	// RVA: 0x3ec9544 VA: 0x75964e1544
	private static Type getType(IntPtr L, ObjectTranslator translator, Int32 idx) { }
	// RVA: 0x3ec47f8 VA: 0x75964dc7f8
	public static Int32 XLuaAccess(IntPtr L) { }
	// RVA: 0x3ec4d34 VA: 0x75964dcd34
	public static Int32 XLuaPrivateAccessible(IntPtr L) { }
	// RVA: 0x3ec4f58 VA: 0x75964dcf58
	public static Int32 XLuaMetatableOperation(IntPtr L) { }
	// RVA: 0x3ec5280 VA: 0x75964dd280
	public static Int32 DelegateConstructor(IntPtr L) { }
	// RVA: 0x3ec54dc VA: 0x75964dd4dc
	public static Int32 ToFunction(IntPtr L) { }
	// RVA: 0x3ec57f4 VA: 0x75964dd7f4
	public static Int32 GenericMethodWraper(IntPtr L) { }
	// RVA: 0x3ec5c88 VA: 0x75964ddc88
	public static Int32 GetGenericMethod(IntPtr L) { }
	// RVA: 0x3ec6150 VA: 0x75964de150
	public static Int32 ReleaseCsObject(IntPtr L) { }
	// RVA: 0x3ec6280 VA: 0x75964de280
	public static Int32 FindTypeByName(IntPtr L) { }
}
```