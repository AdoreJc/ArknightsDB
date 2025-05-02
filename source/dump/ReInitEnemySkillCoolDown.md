# ReInitEnemySkillCoolDown

**Namespace:** ` `


## Fields

- `String _skillName`

- `ActionTargetType _ownerType`

- `Boolean _checkSkillActive`

- `Boolean _onlyResetCD`

- `Boolean _waitFirstPeriod`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ReInitEnemySkillCoolDown : ActionNode
{
	private String _skillName; // 0x10
	private ActionTargetType _ownerType; // 0x18
	private Boolean _checkSkillActive; // 0x1c
	private Boolean _onlyResetCD; // 0x1d
	private Boolean _waitFirstPeriod; // 0x1e
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f95a68 VA: 0x75945ada68
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f95ad0 VA: 0x75945adad0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f95cc8 VA: 0x75945adcc8
	public Void .ctor() { }
}
```