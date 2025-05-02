# IfTargetFromDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Direction _direction`

- `Boolean _checkTargetIsFromDirection`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IfTargetFromDirection : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Direction _direction; // 0x18
	private Boolean _checkTargetIsFromDirection; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f143fc VA: 0x759452c3fc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f14464 VA: 0x759452c464
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f14754 VA: 0x759452c754
	public Void .ctor() { }
}
```