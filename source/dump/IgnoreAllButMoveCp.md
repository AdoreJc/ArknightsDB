# IgnoreAllButMoveCp

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Boolean _ignore`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IgnoreAllButMoveCp : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Boolean _ignore; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc9284 VA: 0x75945e1284
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc92ec VA: 0x75945e12ec
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc948c VA: 0x75945e148c
	public Void .ctor() { }
}
```