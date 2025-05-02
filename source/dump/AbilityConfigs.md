# AbilityConfigs

**Namespace:** ` `


## Fields

- `Ability _ability`

- `TargetTrigger _trigger`


## Properties

- `Ability ability`

- `TargetTrigger trigger`


## Methods

- `Ability get_ability()`

- `TargetTrigger get_trigger()`

- `Boolean TryCastToTarget(FinishCallbackDelegate, Boolean)`

- `Boolean TryCastDirectly(FinishCallbackDelegate, Boolean)`

- `Void DoSetData(Entity, Options)`

- `Void Reset()`

- `Entity _GetTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AbilityConfigs
{
	private Ability _ability; // 0x10
	private TargetTrigger _trigger; // 0x18

	public Ability ability { get; }
	public TargetTrigger trigger { get; }

	// RVA: 0x1e65f8c VA: 0x759447df8c
	public Ability get_ability() { }
	// RVA: 0x1e65f94 VA: 0x759447df94
	public TargetTrigger get_trigger() { }
	// RVA: 0x1e65f9c VA: 0x759447df9c
	public Boolean TryCastToTarget(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e660ec VA: 0x759447e0ec
	public Boolean TryCastDirectly(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e66158 VA: 0x759447e158
	public Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e661c0 VA: 0x759447e1c0
	public Void Reset() { }
	// RVA: 0x1e66040 VA: 0x759447e040
	private Entity _GetTarget() { }
	// RVA: 0x1e661dc VA: 0x759447e1dc
	public Void .ctor() { }
}
```