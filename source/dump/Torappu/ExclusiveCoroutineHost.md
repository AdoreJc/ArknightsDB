# ExclusiveCoroutineHost

**Namespace:** `Torappu`


## Fields

- `Boolean m_isDisposed`

- `MonoBehaviour m_host`

- `WeakReference m_routineRef`


## Methods

- `Void ExclusiveCoroutine(IEnumerator)`

- `Void StopCoroutine(IEnumerator)`

- `Void StopCurrent()`

- `Boolean ForgetCurrent()`

- `Void _StopCoroutineInternal(IEnumerator)`

- `Void Dispose()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class ExclusiveCoroutineHost : IDisposable, IHotfixable
{
	private Boolean m_isDisposed; // 0x10
	private MonoBehaviour m_host; // 0x18
	private Func`1 m_hostGetter; // 0x20
	private WeakReference m_routineRef; // 0x28
	private static __XLua_Gen_Delegate0 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate0 __Hotfix0_ExclusiveCoroutine; // 0x8
	private static __XLua_Gen_Delegate0 __Hotfix0_StopCoroutine; // 0x10
	private static __XLua_Gen_Delegate1 __Hotfix0_StopCurrent; // 0x18
	private static __XLua_Gen_Delegate8 __Hotfix0_ForgetCurrent; // 0x20
	private static __XLua_Gen_Delegate0 __Hotfix0__StopCoroutineInternal; // 0x28
	private static __XLua_Gen_Delegate1 __Hotfix0_Dispose; // 0x30


	// RVA: 0x67659f8 VA: 0x7598d7d9f8
	public Void .ctor(Func`1 lazyHostGetter) { }
	// RVA: 0x6765ad8 VA: 0x7598d7dad8
	public Void ExclusiveCoroutine(IEnumerator routine) { }
	// RVA: 0x6765dd4 VA: 0x7598d7ddd4
	public Void StopCoroutine(IEnumerator routine) { }
	// RVA: 0x6765f34 VA: 0x7598d7df34
	public Void StopCurrent() { }
	// RVA: 0x6765fec VA: 0x7598d7dfec
	public Boolean ForgetCurrent() { }
	// RVA: 0x6765e5c VA: 0x7598d7de5c
	private Void _StopCoroutineInternal(IEnumerator routine) { }
	// RVA: 0x67660a8 VA: 0x7598d7e0a8
	public Void Dispose() { }
}
```