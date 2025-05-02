# CheckTargetProfession

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _readProfessionFromBlackboard`

- `Boolean _checkSubProfession`

- `String _subProfessions`


## Properties

- `ProfessionCategory professionGroup`


## Methods

- `ProfessionCategory get_professionGroup()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTargetProfession : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private ProfessionCategory[] _profession; // 0x18
	private Boolean _readProfessionFromBlackboard; // 0x20
	private Boolean _checkSubProfession; // 0x21
	private String _subProfessions; // 0x28
	private static DelegateBridge __Hotfix0_get_professionGroup; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private ProfessionCategory professionGroup { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f2b7f4 VA: 0x75945437f4
	private ProfessionCategory get_professionGroup() { }
	// RVA: 0x1f2b8ac VA: 0x75945438ac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2b914 VA: 0x7594543914
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2bbdc VA: 0x7594543bdc
	public Void .ctor() { }
}
```