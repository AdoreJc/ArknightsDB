# CheckCharacterDefaultDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Direction _direction`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCharacterDefaultDirection : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Direction _direction; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1eb60 VA: 0x7594536b60
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1ebc8 VA: 0x7594536bc8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1ed40 VA: 0x7594536d40
	public Void .ctor() { }
}
```