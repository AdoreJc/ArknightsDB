# IsCloseToFootball

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _ignoreIsSelected`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IsCloseToFootball : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _ignoreIsSelected; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f4eeb8 VA: 0x7594566eb8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4ef20 VA: 0x7594566f20
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4f09c VA: 0x759456709c
	public Void .ctor() { }
}
```