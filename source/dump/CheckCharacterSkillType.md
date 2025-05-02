# CheckCharacterSkillType

**Namespace:** ` `


## Fields

- `SkillType _skillType`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCharacterSkillType : ActionNode
{
	private SkillType _skillType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2d814 VA: 0x7594545814
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2d87c VA: 0x759454587c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2da40 VA: 0x7594545a40
	public Void .ctor() { }
}
```