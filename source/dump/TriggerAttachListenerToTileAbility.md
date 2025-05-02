# TriggerAttachListenerToTileAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `ActionTargetType _targetType`

- `String _abilityName`

- `String _rangeIdKey`

- `String _rangeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerAttachListenerToTileAbility : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _abilityName; // 0x18
	private String _rangeIdKey; // 0x20
	private String _rangeId; // 0x28
	private List`1 m_tiles; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f90e50 VA: 0x75945a8e50
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f90eb8 VA: 0x75945a8eb8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f91334 VA: 0x75945a9334
	public Void .ctor() { }
}
```