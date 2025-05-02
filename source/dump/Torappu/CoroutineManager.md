# CoroutineManager

**Namespace:** `Torappu`


## Fields

- `MonoBehaviour m_host`


## Methods

- `Void Dispose()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class CoroutineManager : LazySingleton`1, IDisposable
{
	private MonoBehaviour m_host; // 0x10
	private static __XLua_Gen_Delegate0 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate1 __Hotfix0_CreateInstance; // 0x8
	private static __XLua_Gen_Delegate1 __Hotfix0_StartCoroutine; // 0x10
	private static __XLua_Gen_Delegate1 __Hotfix0_StopCoroutine; // 0x18
	private static __XLua_Gen_Delegate1 __Hotfix0_StopCoroutineNested; // 0x20
	private static __XLua_Gen_Delegate1 __Hotfix0_Dispose; // 0x28
	private static __XLua_Gen_Delegate2 __Hotfix0__CheckHost; // 0x30


	// RVA: 0x67467d0 VA: 0x7598d5e7d0
	private Void .ctor(MonoBehaviour host) { }
	// RVA: 0x6746880 VA: 0x7598d5e880
	public static Void CreateInstance(MonoBehaviour host) { }
	// RVA: 0x6746968 VA: 0x7598d5e968
	public static Void StartCoroutine(IEnumerator routine) { }
	// RVA: 0x6746bd4 VA: 0x7598d5ebd4
	public static Void StopCoroutine(IEnumerator routine) { }
	// RVA: 0x6746ca8 VA: 0x7598d5eca8
	public static Void StopCoroutineNested(IEnumerator routine) { }
	// RVA: 0x6746d74 VA: 0x7598d5ed74
	public Void Dispose() { }
	// RVA: 0x6746a3c VA: 0x7598d5ea3c
	private static MonoBehaviour _CheckHost() { }
}
```