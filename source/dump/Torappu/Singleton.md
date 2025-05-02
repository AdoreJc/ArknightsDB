# Singleton

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class Singleton`1 : IHotfixable
{
	private static T s_instance; // 0x0
	private static __XLua_Gen_Delegate4 __Hotfix0_Reset; // 0x0
	private static __XLua_Gen_Delegate4 __Hotfix0__CreateInstance; // 0x0

	public static T instance { get; }

	// RVA: 0x VA: 0x0
	public static T get_instance() { }
	// RVA: 0x VA: 0x0
	public static Void Reset() { }
	// RVA: 0x VA: 0x0
	private static Void _CreateInstance() { }
	// RVA: 0x VA: 0x0
	protected Void .ctor() { }
}
```