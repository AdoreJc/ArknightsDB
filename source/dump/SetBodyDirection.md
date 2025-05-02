# SetBodyDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Direction _direction`

- `Boolean _includeFace`

- `Boolean _onlyChangeFace`

- `Boolean _useSourceDirection`

- `Boolean _useDirectionFromBlackboard`

- `String _directionKey`

- `Boolean _force`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetBodyDirection : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Direction _direction; // 0x14
	private Boolean _includeFace; // 0x18
	private Boolean _onlyChangeFace; // 0x19
	private Boolean _useSourceDirection; // 0x1a
	private Boolean _useDirectionFromBlackboard; // 0x1b
	private String _directionKey; // 0x20
	private Boolean _force; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc6b0c VA: 0x75945deb0c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc6b74 VA: 0x75945deb74
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc6df4 VA: 0x75945dedf4
	public Void .ctor() { }
}
```