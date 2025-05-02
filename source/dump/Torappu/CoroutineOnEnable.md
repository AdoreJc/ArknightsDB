# CoroutineOnEnable

**Namespace:** `Torappu`


## Fields

- `Options m_options`

- `Boolean m_isEnabled`

- `Boolean m_coroutineLock`


## Methods

- `Void InvokeOnEnable()`

- `Void InvokeOnDisable()`

- `Void _TryStartCoroutine()`

- `IEnumerator _TaskWrapper(IEnumerator)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class CoroutineOnEnable : IHotfixable
{
	private Options m_options; // 0x10
	private Boolean m_isEnabled; // 0x20
	private Boolean m_coroutineLock; // 0x21
	private Func`2 m_startCoroutine; // 0x28
	private static __XLua_Gen_Delegate90 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate1 __Hotfix0_InvokeOnEnable; // 0x8
	private static __XLua_Gen_Delegate1 __Hotfix0_InvokeOnDisable; // 0x10
	private static __XLua_Gen_Delegate1 __Hotfix0__TryStartCoroutine; // 0x18
	private static __XLua_Gen_Delegate91 __Hotfix0__TaskWrapper; // 0x20


	// RVA: 0x677b104 VA: 0x7598d93104
	public Void .ctor(MonoBehaviour target, Options options) { }
	// RVA: 0x677b36c VA: 0x7598d9336c
	public Void InvokeOnEnable() { }
	// RVA: 0x677b3e4 VA: 0x7598d933e4
	public Void InvokeOnDisable() { }
	// RVA: 0x677b2a4 VA: 0x7598d932a4
	private Void _TryStartCoroutine() { }
	// RVA: 0x677b454 VA: 0x7598d93454
	private IEnumerator _TaskWrapper(IEnumerator task) { }
}
```