# RoundBuffBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `String _buffKey`

- `RoundType _roundType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoundBuffBlackboard : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private String _buffKey; // 0x20
	private RoundType _roundType; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eed714 VA: 0x7594505714
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eed77c VA: 0x759450577c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eed9f8 VA: 0x75945059f8
	public Void .ctor() { }
}
```