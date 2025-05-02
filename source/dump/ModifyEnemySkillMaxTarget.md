# ModifyEnemySkillMaxTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _maxTarget`

- `String _skillKey`

- `Boolean _checkSkillActive`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyEnemySkillMaxTarget : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _maxTarget; // 0x14
	private String _skillKey; // 0x18
	private Boolean _checkSkillActive; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcf288 VA: 0x75945e7288
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcf2f0 VA: 0x75945e72f0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcf4ec VA: 0x75945e74ec
	public Void .ctor() { }
}
```