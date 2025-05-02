# PauseEffectIfSpineEvent

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _pauseAtStart`


## Methods

- `Void _OnPlayEffect(Object)`

- `Void _OnPauseEffect(Object)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class PauseEffectIfSpineEvent : Behaviour
{
	private Boolean _pauseAtStart; // 0x20
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0__OnPlayEffect; // 0x8
	private static DelegateBridge __Hotfix0__OnPauseEffect; // 0x10
	private static DelegateBridge __Hotfix0_OnFinish; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2005e5c VA: 0x759461de5c
	public override Void OnPlay() { }
	// RVA: 0x2006090 VA: 0x759461e090
	private Void _OnPlayEffect(Object arg) { }
	// RVA: 0x2006110 VA: 0x759461e110
	private Void _OnPauseEffect(Object arg) { }
	// RVA: 0x2006190 VA: 0x759461e190
	public override Void OnFinish() { }
	// RVA: 0x20063b0 VA: 0x759461e3b0
	public Void .ctor() { }
	// RVA: 0x200641c VA: 0x759461e41c
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2006420 VA: 0x759461e420
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```