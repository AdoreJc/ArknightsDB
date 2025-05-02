# SetCastSkillCost

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _value`

- `String _valueBbKey`

- `String _assignOldValueKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetCastSkillCost : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _value; // 0x14
	private String _valueBbKey; // 0x18
	private String _assignOldValueKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8f184 VA: 0x75945a7184
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8f1ec VA: 0x75945a71ec
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8f48c VA: 0x75945a748c
	public Void .ctor() { }
}
```