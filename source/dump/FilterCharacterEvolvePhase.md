# FilterCharacterEvolvePhase

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Int32 _phaseLevel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterCharacterEvolvePhase : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Int32 _phaseLevel; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f60e38 VA: 0x7594578e38
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f60ea0 VA: 0x7594578ea0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f61084 VA: 0x7594579084
	public Void .ctor() { }
}
```