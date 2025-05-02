# UpdateFrictionFactor

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Single _frictionFactor`

- `Boolean _restoreFrictionFactor`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UpdateFrictionFactor : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Single _frictionFactor; // 0x14
	private Boolean _restoreFrictionFactor; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f76474 VA: 0x759458e474
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f764dc VA: 0x759458e4dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f76698 VA: 0x759458e698
	public Void .ctor() { }
}
```