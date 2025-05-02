# SingletonMonoBehaviour

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class SingletonMonoBehaviour`1 : MonoBehaviour, IHotfixable
{
	protected static T s_instance; // 0x0
	private static __XLua_Gen_Delegate5 __Hotfix0_get_hasInstance; // 0x0

	public static T instance { get; }
	public static T instanceOrNull { get; }
	public static Boolean hasInstance { get; }

	// RVA: 0x VA: 0x0
	public static T get_instance() { }
	// RVA: 0x VA: 0x0
	public static T CreateInstanceIfNot() { }
	// RVA: 0x VA: 0x0
	public static T get_instanceOrNull() { }
	// RVA: 0x VA: 0x0
	public static Boolean get_hasInstance() { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnInit() { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnDuplicated() { }
	// RVA: 0x VA: 0x0
	protected virtual Void Awake() { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnDestroy() { }
	// RVA: 0x VA: 0x0
	private static T _CreateNewInstance() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```