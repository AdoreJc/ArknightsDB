# LegionModeOnlyModifyCharacterOverlapState

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _noOverlap`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyModifyCharacterOverlapState : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _noOverlap; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6af60 VA: 0x7594582f60
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6afc8 VA: 0x7594582fc8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6b1b8 VA: 0x75945831b8
	public Void .ctor() { }
}
```