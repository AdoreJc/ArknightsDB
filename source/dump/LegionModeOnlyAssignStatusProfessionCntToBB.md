# LegionModeOnlyAssignStatusProfessionCntToBB

**Namespace:** ` `


## Fields

- `String _professionCntKey`

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyAssignStatusProfessionCntToBB : ActionNode
{
	private String _professionCntKey; // 0x10
	private ActionTargetType _sourceType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6a154 VA: 0x7594582154
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6a1bc VA: 0x75945821bc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6a3e8 VA: 0x75945823e8
	public Void .ctor() { }
}
```