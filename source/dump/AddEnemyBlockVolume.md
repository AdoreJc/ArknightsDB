# AddEnemyBlockVolume

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _additionVolume`

- `Boolean _isMinus`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddEnemyBlockVolume : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _additionVolume; // 0x14
	private Boolean _isMinus; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f12080 VA: 0x759452a080
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f120e8 VA: 0x759452a0e8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f122a8 VA: 0x759452a2a8
	public Void .ctor() { }
}
```