# FilterTargetWithPlayerSide

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ActionTargetType _source`

- `Boolean filterMapLayer`

- `Boolean filterTargetPlayerSide`

- `Boolean filterSourcePlayerSide`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterTargetWithPlayerSide : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ActionTargetType _source; // 0x14
	private Boolean filterMapLayer; // 0x18
	private Boolean filterTargetPlayerSide; // 0x19
	private Boolean filterSourcePlayerSide; // 0x1a
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f75154 VA: 0x759458d154
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f751bc VA: 0x759458d1bc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f75414 VA: 0x759458d414
	public Void .ctor() { }
}
```