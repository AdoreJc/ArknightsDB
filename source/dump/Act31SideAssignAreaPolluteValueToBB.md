# Act31SideAssignAreaPolluteValueToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _polluteVKey`

- `Boolean _assignPVRatio`

- `Boolean _assignTilePV`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SideAssignAreaPolluteValueToBB : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _polluteVKey; // 0x18
	private Boolean _assignPVRatio; // 0x20
	private Boolean _assignTilePV; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edd4a4 VA: 0x75944f54a4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edd50c VA: 0x75944f550c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edd780 VA: 0x75944f5780
	public Void .ctor() { }
}
```