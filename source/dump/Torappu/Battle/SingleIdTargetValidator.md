# SingleIdTargetValidator

**Namespace:** `Torappu.Battle`


## Fields

- `String _targetId`

- `Boolean _loadFromBlackboard`

- `String m_targetId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SingleIdTargetValidator : TargetValidator
{
	private String _targetId; // 0x90
	private Boolean _loadFromBlackboard; // 0x98
	private String m_targetId; // 0xa0


	// RVA: 0x1bdbc88 VA: 0x75941f3c88
	public override Void SetData(Entity owner, Blackboard blackboard, Boolean ignoreTargetSide) { }
	// RVA: 0x1bdbd2c VA: 0x75941f3d2c
	public override Boolean Validate(Entity target) { }
	// RVA: 0x1bdbd58 VA: 0x75941f3d58
	public Void .ctor() { }
}
```