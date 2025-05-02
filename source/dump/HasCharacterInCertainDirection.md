# HasCharacterInCertainDirection

**Namespace:** ` `


## Fields

- `Direction _direction`

- `ActionTargetType _target`

- `Boolean _checkSameSide`

- `Boolean _excludeTrapCategory`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HasCharacterInCertainDirection : ActionNode
{
	private Direction _direction; // 0x10
	private ActionTargetType _target; // 0x14
	private Boolean _checkSameSide; // 0x18
	private Boolean _excludeTrapCategory; // 0x19
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f9b308 VA: 0x75945b3308
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9b370 VA: 0x75945b3370
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9b640 VA: 0x75945b3640
	public Void .ctor() { }
}
```