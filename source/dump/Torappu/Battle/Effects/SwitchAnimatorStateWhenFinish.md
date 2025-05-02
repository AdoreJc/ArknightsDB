# SwitchAnimatorStateWhenFinish

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Animator m_animator`

- `String _stateName`


## Methods

- `Void Awake()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SwitchAnimatorStateWhenFinish : Behaviour
{
	private Animator m_animator; // 0x20
	private String _stateName; // 0x28
	private static DelegateBridge __Hotfix0_OnFinish; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2013028 VA: 0x759462b028
	public override Void OnFinish() { }
	// RVA: 0x2013160 VA: 0x759462b160
	private Void Awake() { }
	// RVA: 0x20131f0 VA: 0x759462b1f0
	public Void .ctor() { }
	// RVA: 0x2013260 VA: 0x759462b260
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```