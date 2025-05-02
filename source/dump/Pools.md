# Pools

**Namespace:** ` `


## Methods

- `Void _ReleaseMeshDict(Dictionary`2)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class Pools : SingletonInScene`1
{
	public LocalGenericPool`1 meshPool; // 0x18
	public LocalGenericPool`1 contextPool; // 0x20
	public LocalGenericPool`1 trailContextPool; // 0x28
	private LocalGenericPool`1 m_meshDictPool; // 0x30
	private static __XLua_Gen_Delegate150 __Hotfix0_get_meshDictPool; // 0x0
	private static __XLua_Gen_Delegate0 __Hotfix0__ReleaseMeshDict; // 0x8
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x10

	public LocalGenericPool`1 meshDictPool { get; }

	// RVA: 0x679cb64 VA: 0x7598db4b64
	public LocalGenericPool`1 get_meshDictPool() { }
	// RVA: 0x67a1b34 VA: 0x7598db9b34
	private Void _ReleaseMeshDict(Dictionary`2 dict) { }
	// RVA: 0x67a1d1c VA: 0x7598db9d1c
	private Void .ctor() { }
}
```