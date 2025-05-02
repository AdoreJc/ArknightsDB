# ModifyCost

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _forceToDisplayNumber`

- `Boolean _forceToDisplayNegativeNumber`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyCost : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _forceToDisplayNumber; // 0x14
	private Boolean _forceToDisplayNegativeNumber; // 0x15
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0b8c0 VA: 0x75945238c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0b928 VA: 0x7594523928
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0bad0 VA: 0x7594523ad0
	public Void .ctor() { }
}
```