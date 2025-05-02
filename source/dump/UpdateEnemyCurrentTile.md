# UpdateEnemyCurrentTile

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Boolean _force`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UpdateEnemyCurrentTile : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Boolean _force; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc8918 VA: 0x75945e0918
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc8980 VA: 0x75945e0980
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc8af4 VA: 0x75945e0af4
	public Void .ctor() { }
}
```