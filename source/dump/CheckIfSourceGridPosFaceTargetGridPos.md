# CheckIfSourceGridPosFaceTargetGridPos

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `FaceType _faceType`

- `Single _targetColOffset`

- `FaceType _faceIfSameCol`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckIfSourceGridPosFaceTargetGridPos : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private FaceType _faceType; // 0x18
	private Single _targetColOffset; // 0x1c
	private FaceType _faceIfSameCol; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2e05c VA: 0x759454605c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2e0c4 VA: 0x75945460c4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2e310 VA: 0x7594546310
	public Void .ctor() { }
}
```