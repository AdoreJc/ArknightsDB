# RechargeToken

**Namespace:** ` `


## Fields

- `RechargeTiming _rechargeTiming`

- `Boolean _refreshRemainingCnt`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RechargeToken : ActionNode
{
	private RechargeTiming _rechargeTiming; // 0x10
	private Boolean _refreshRemainingCnt; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe8640 VA: 0x7594600640
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe86a8 VA: 0x75946006a8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe8828 VA: 0x7594600828
	public Void .ctor() { }
}
```