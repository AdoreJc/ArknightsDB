# TriggerAnimatorWhenContainsBuff

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _buffKey`

- `String _animatorDefaultName`

- `String _animatorTriggerName`

- `Animator m_animator`

- `Int32 m_triggerAnimatorID`

- `Int32 m_defaultAnimatorID`

- `FP m_checkTime`


## Methods

- `Void Update()`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class TriggerAnimatorWhenContainsBuff : Behaviour
{
	private String _buffKey; // 0x20
	private String _animatorDefaultName; // 0x28
	private String _animatorTriggerName; // 0x30
	private Animator m_animator; // 0x38
	private Int32 m_triggerAnimatorID; // 0x40
	private Int32 m_defaultAnimatorID; // 0x44
	private FP m_checkTime; // 0x48
	private const Single m_checkInterval; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x20142dc VA: 0x759462c2dc
	public override Void OnPlay() { }
	// RVA: 0x20143d4 VA: 0x759462c3d4
	private Void Update() { }
	// RVA: 0x20145c0 VA: 0x759462c5c0
	public Void .ctor() { }
	// RVA: 0x2014664 VA: 0x759462c664
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```