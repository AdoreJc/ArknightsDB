# CharacterHasValidToken

**Namespace:** ` `


## Fields

- `ActionTargetType _hostType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharacterHasValidToken : ActionNode
{
	private ActionTargetType _hostType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fea9dc VA: 0x75946029dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1feaa44 VA: 0x7594602a44
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1feacf4 VA: 0x7594602cf4
	public Void .ctor() { }
}
```