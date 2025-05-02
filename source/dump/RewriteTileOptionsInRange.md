# RewriteTileOptionsInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _rangeId`

- `AdvancedBuildableMask _advancedBuildableMask`

- `Boolean _nightMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RewriteTileOptionsInRange : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _rangeId; // 0x18
	private AdvancedBuildableMask _advancedBuildableMask; // 0x20
	private Boolean _nightMode; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe4fa0 VA: 0x75945fcfa0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe5008 VA: 0x75945fd008
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe52e4 VA: 0x75945fd2e4
	public Void .ctor() { }
}
```