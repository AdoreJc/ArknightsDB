# VersionCompat

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class VersionCompat : ILuaCallCSharp
{
	private static String s_targetFunVer; // 0x0

	public static String CUR_FUNC_VER { get; }

	// RVA: 0x677af0c VA: 0x7598d92f0c
	public static String get_CUR_FUNC_VER() { }
	// RVA: 0x677af4c VA: 0x7598d92f4c
	private static Void .cctor() { }
	// RVA: 0x677afc8 VA: 0x7598d92fc8
	public static Void SetFuncVersion(String targetFuncVer) { }
	// RVA: 0x677b030 VA: 0x7598d93030
	public static Boolean FuncVersion(String requireVersion) { }
	// RVA: 0x677b0a8 VA: 0x7598d930a8
	public static String GetVersion4Display() { }
	// RVA: 0x677b0fc VA: 0x7598d930fc
	public Void .ctor() { }
}
```