# AutochessAssignEquipCntToBlackboard

**Namespace:** ` `


## Fields

- `Boolean _onlyGoldenEquip`

- `String _blackboardKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutochessAssignEquipCntToBlackboard : ActionNode
{
	private Boolean _onlyGoldenEquip; // 0x10
	private String _blackboardKey; // 0x18
	private ActionTargetType _targetType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee419c VA: 0x75944fc19c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee4204 VA: 0x75944fc204
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee43d0 VA: 0x75944fc3d0
	public Void .ctor() { }
}
```