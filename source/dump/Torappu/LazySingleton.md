# LazySingleton

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class LazySingleton`1 : IHotfixable
{
	private static T <instance>k__BackingField; // 0x0
	private static __XLua_Gen_Delegate4 __Hotfix0_Release; // 0x0

	public static T instance { get; set; }

	// RVA: 0x VA: 0x0
	public static T get_instance() { }
	// RVA: 0x VA: 0x0
	private static Void set_instance(T value) { }
	// RVA: 0x VA: 0x0
	protected static Void SetInstance(T inst) { }
	// RVA: 0x VA: 0x0
	public static Void Release() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```