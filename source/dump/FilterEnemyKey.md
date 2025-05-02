# FilterEnemyKey

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterEnemyKey : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f613b0 VA: 0x75945793b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f61418 VA: 0x7594579418
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f615a8 VA: 0x75945795a8
	public Void .ctor() { }
}
```