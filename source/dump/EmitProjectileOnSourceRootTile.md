# EmitProjectileOnSourceRootTile

**Namespace:** ` `


## Fields

- `Boolean _overwriteActions`

- `Event _ev`

- `ActionTargetType _sourceType`


## Methods

- `Void GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EmitProjectileOnSourceRootTile : ActionNode, IActionNodeSource
{
	private Boolean _overwriteActions; // 0x10
	private Event _ev; // 0x14
	private ActionNode[] _actions; // 0x18
	private ActionTargetType _sourceType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f77524 VA: 0x759458f524
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7758c VA: 0x759458f58c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f778b4 VA: 0x759458f8b4
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1f7793c VA: 0x759458f93c
	public Void .ctor() { }
}
```