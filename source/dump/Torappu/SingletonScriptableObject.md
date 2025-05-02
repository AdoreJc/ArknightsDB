# SingletonScriptableObject

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class SingletonScriptableObject`1 : ScriptableObject
{
	private static T s_instance; // 0x0

	public static T instance { get; }

	// RVA: 0x VA: 0x0
	public static T get_instance() { }
	// RVA: 0x VA: 0x0
	public static T GetInstanceSafe() { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnEnable() { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnDisable() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```