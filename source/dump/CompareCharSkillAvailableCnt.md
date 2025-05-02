# CompareCharSkillAvailableCnt

**Namespace:** ` `


## Fields

- `CompareType _condType`

- `Int32 _count`

- `ActionTargetType _targetType`

- `Boolean _dontShowWarnning`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CompareCharSkillAvailableCnt : ActionNode
{
	private CompareType _condType; // 0x10
	private Int32 _count; // 0x14
	private ActionTargetType _targetType; // 0x18
	private Boolean _dontShowWarnning; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f24cac VA: 0x759453ccac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f24d14 VA: 0x759453cd14
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f24fec VA: 0x759453cfec
	public Void .ctor() { }
}
```