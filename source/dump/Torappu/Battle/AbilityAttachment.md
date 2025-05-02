# AbilityAttachment

**Namespace:** `Torappu.Battle`


## Fields

- `Entity source`

- `Blackboard extraBlackboard`

- `Single prob`

- `TargetValidator m_targetValidator`


## Methods

- `Void Init(TargetValidator)`

- `Void Apply(Entity, Entity, Ability, Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AbilityAttachment : IAbilityAttachment
{
	public Entity source; // 0x10
	public BuffData[] activeBuffData; // 0x18
	public Blackboard extraBlackboard; // 0x20
	public Single prob; // 0x28
	private TargetValidator m_targetValidator; // 0x30


	// RVA: 0x3f21be0 VA: 0x7596539be0
	public Void Init(TargetValidator targetValidator) { }
	// RVA: 0x3f21be8 VA: 0x7596539be8
	public Void Apply(Entity target, Entity owner, Ability ability, Blackboard blackboard) { }
	// RVA: 0x3f21d78 VA: 0x7596539d78
	public static Void Apply(IList`1 attachments, Entity target, Entity owner, Ability ability, Blackboard blackboard) { }
	// RVA: 0x3f21f50 VA: 0x7596539f50
	public Void .ctor() { }
}
```