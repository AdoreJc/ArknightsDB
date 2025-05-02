# TriggerAnimatorWhenFinish

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Animator m_animator`


## Methods

- `Void Awake()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class TriggerAnimatorWhenFinish : Behaviour
{
	private Animator m_animator; // 0x20
	private static readonly Int32 s_onFinish; // 0x0
	private static DelegateBridge __Hotfix0_OnFinish; // 0x8
	private static DelegateBridge __Hotfix0_Awake; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x201466c VA: 0x759462c66c
	public override Void OnFinish() { }
	// RVA: 0x20147d0 VA: 0x759462c7d0
	private Void Awake() { }
	// RVA: 0x2014870 VA: 0x759462c870
	public Void .ctor() { }
	// RVA: 0x20148f0 VA: 0x759462c8f0
	private static Void .cctor() { }
	// RVA: 0x2014958 VA: 0x759462c958
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```