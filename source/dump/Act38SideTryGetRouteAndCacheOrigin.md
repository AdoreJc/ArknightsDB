# Act38SideTryGetRouteAndCacheOrigin

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _envSystemKey`

- `Boolean _restoreCache`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act38SideTryGetRouteAndCacheOrigin : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _envSystemKey; // 0x18
	private Boolean _restoreCache; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee1548 VA: 0x75944f9548
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee15b0 VA: 0x75944f95b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee17d4 VA: 0x75944f97d4
	public Void .ctor() { }
}
```