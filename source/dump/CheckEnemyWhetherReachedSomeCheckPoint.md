# CheckEnemyWhetherReachedSomeCheckPoint

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _backToFront`

- `Int32 _checkPointIndex`

- `String _indexBbKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyWhetherReachedSomeCheckPoint : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _backToFront; // 0x14
	private Int32 _checkPointIndex; // 0x18
	private String _indexBbKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2ad1c VA: 0x7594542d1c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2ad84 VA: 0x7594542d84
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2b040 VA: 0x7594543040
	public Void .ctor() { }
}
```