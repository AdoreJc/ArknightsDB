# CheckTargetTokenOrHost

**Namespace:** ` `


## Fields

- `ActionTargetType _hostType`

- `ActionTargetType _tokenType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTargetTokenOrHost : ActionNode
{
	private ActionTargetType _hostType; // 0x10
	private ActionTargetType _tokenType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1feb450 VA: 0x7594603450
	public override SourceType get_allowedSource() { }
	// RVA: 0x1feb4b8 VA: 0x75946034b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1feb6e0 VA: 0x75946036e0
	public Void .ctor() { }
}
```