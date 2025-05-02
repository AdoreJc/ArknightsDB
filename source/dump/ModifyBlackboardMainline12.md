# ModifyBlackboardMainline12

**Namespace:** ` `


## Fields

- `String _abilityName`

- `ActionTargetType _sourceType`

- `String _blackboardKey`

- `Boolean _viaStandsCount`

- `String _rewriteBlackboardKey`

- `Boolean _viaHostBuffStackCount`

- `String _hostBuffID`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyBlackboardMainline12 : ActionNode
{
	private String _abilityName; // 0x10
	private ActionTargetType _sourceType; // 0x18
	private String _blackboardKey; // 0x20
	private Boolean _viaStandsCount; // 0x28
	private String _rewriteBlackboardKey; // 0x30
	private Boolean _viaHostBuffStackCount; // 0x38
	private String _hostBuffID; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6ea90 VA: 0x7594586a90
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6eaf8 VA: 0x7594586af8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6eeb8 VA: 0x7594586eb8
	public Void .ctor() { }
}
```