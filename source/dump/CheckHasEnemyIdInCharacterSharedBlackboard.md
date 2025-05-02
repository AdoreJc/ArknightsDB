# CheckHasEnemyIdInCharacterSharedBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ActionTargetType _source`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckHasEnemyIdInCharacterSharedBlackboard : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ActionTargetType _source; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd8338 VA: 0x75945f0338
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd83a0 VA: 0x75945f03a0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd85c8 VA: 0x75945f05c8
	public Void .ctor() { }
}
```