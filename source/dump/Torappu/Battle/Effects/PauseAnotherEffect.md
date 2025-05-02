# PauseAnotherEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _effect`

- `Single _preDelay`

- `Boolean _checkUpdate`

- `Boolean m_markPreDelay`

- `Single m_preDelayCounter`


## Methods

- `Void _OnPause()`

- `Void _OnUnpause()`

- `Void Update()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class PauseAnotherEffect : Behaviour
{
	private String _effect; // 0x20
	private Single _preDelay; // 0x28
	private Boolean _checkUpdate; // 0x2c
	private ObjectPtr`1 m_effectHolder; // 0x30
	private Boolean m_markPreDelay; // 0x40
	private Single m_preDelayCounter; // 0x44
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_OnFinish; // 0x8
	private static DelegateBridge __Hotfix0__OnPause; // 0x10
	private static DelegateBridge __Hotfix0__OnUnpause; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x20033c4 VA: 0x759461b3c4
	public override Void OnPlay() { }
	// RVA: 0x2003608 VA: 0x759461b608
	public override Void OnFinish() { }
	// RVA: 0x200349c VA: 0x759461b49c
	private Void _OnPause() { }
	// RVA: 0x2003678 VA: 0x759461b678
	private Void _OnUnpause() { }
	// RVA: 0x2003770 VA: 0x759461b770
	private Void Update() { }
	// RVA: 0x2003874 VA: 0x759461b874
	public Void .ctor() { }
	// RVA: 0x20038e0 VA: 0x759461b8e0
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x20038e4 VA: 0x759461b8e4
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```