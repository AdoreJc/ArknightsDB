# KillCharacterOnTileIfExists

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _noSource`

- `Boolean _skipReborn`

- `SourceType _allowedSource`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class KillCharacterOnTileIfExists : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _noSource; // 0x14
	private Boolean _skipReborn; // 0x15
	private SourceType _allowedSource; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd1020 VA: 0x75945e9020
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd1088 VA: 0x75945e9088
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd1268 VA: 0x75945e9268
	public Void .ctor() { }
}
```