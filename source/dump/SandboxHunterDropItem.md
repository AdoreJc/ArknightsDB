# SandboxHunterDropItem

**Namespace:** ` `


## Fields

- `ActionTargetType _owner`

- `ResDropSourceType _type`

- `EnemyDeathDetailType _detailType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxHunterDropItem : ActionNode
{
	private ActionTargetType _owner; // 0x10
	private ResDropSourceType _type; // 0x14
	private EnemyDeathDetailType _detailType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f860b0 VA: 0x759459e0b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f86118 VA: 0x759459e118
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f864ac VA: 0x759459e4ac
	public Void .ctor() { }
}
```