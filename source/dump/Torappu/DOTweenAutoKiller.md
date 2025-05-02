# DOTweenAutoKiller

**Namespace:** `Torappu`


## Methods

- `Void RegisterDontAutoKillTween(Tween)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DOTweenAutoKiller : SingletonInScene`1, IDisposable, IHotfixable
{
	private List`1 m_dontAutoKillTweens; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RegisterDontAutoKillTween; // 0x8
	private static DelegateBridge __Hotfix0_Dispose; // 0x10


	// RVA: 0x2d15c0c VA: 0x759532dc0c
	private Void .ctor() { }
	// RVA: 0x2d15cf0 VA: 0x759532dcf0
	public Void RegisterDontAutoKillTween(Tween t) { }
	// RVA: 0x2d15e48 VA: 0x759532de48
	public Void Dispose() { }
}
```