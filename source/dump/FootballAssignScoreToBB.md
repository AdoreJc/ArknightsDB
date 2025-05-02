# FootballAssignScoreToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `ScoreType _scoreType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FootballAssignScoreToBB : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private ScoreType _scoreType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f517d0 VA: 0x75945697d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f51838 VA: 0x7594569838
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f51a5c VA: 0x7594569a5c
	public Void .ctor() { }
}
```