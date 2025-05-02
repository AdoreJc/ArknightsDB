# RestartCastSkill

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean forceRechargeSP`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RestartCastSkill : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean forceRechargeSP; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f592f8 VA: 0x75945712f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f59360 VA: 0x7594571360
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5975c VA: 0x759457175c
	public Void .ctor() { }
}
```