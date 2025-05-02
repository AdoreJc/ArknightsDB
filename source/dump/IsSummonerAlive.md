# IsSummonerAlive

**Namespace:** ` `


## Fields

- `ActionTargetType _token`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IsSummonerAlive : ActionNode
{
	private ActionTargetType _token; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe9f44 VA: 0x7594601f44
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe9fac VA: 0x7594601fac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fea260 VA: 0x7594602260
	public Void .ctor() { }
}
```