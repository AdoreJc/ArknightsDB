# LuaTemplate

**Namespace:** `XLua.TemplateEngine`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua.TemplateEngine
public class LuaTemplate
{
	private static lua_CSFunction templateCompileFunction; // 0x0
	private static lua_CSFunction templateExecuteFunction; // 0x8


	// RVA: 0x3ffd950 VA: 0x7596615950
	public static String ComposeCode(List`1 chunks) { }
	// RVA: 0x3ffdc40 VA: 0x7596615c40
	public static LuaFunction Compile(LuaEnv luaenv, String snippet) { }
	// RVA: 0x3ffdd08 VA: 0x7596615d08
	public static String Execute(LuaFunction compiledTemplate, LuaTable parameters) { }
	// RVA: 0x3ffddd0 VA: 0x7596615dd0
	public static String Execute(LuaFunction compiledTemplate) { }
	// RVA: 0x3ffd718 VA: 0x7596615718
	public static Int32 Compile(IntPtr L) { }
	// RVA: 0x3ffd8ac VA: 0x75966158ac
	public static Int32 Execute(IntPtr L) { }
	// RVA: 0x3ffe010 VA: 0x7596616010
	public static Void OpenLib(IntPtr L) { }
	// RVA: 0x3ffe210 VA: 0x7596616210
	public Void .ctor() { }
	// RVA: 0x3ffe218 VA: 0x7596616218
	private static Void .cctor() { }
}
```