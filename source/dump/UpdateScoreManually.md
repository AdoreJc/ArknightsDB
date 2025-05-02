# UpdateScoreManually

**Namespace:** ` `


## Fields

- `ScoreType _score`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UpdateScoreManually : ActionNode
{
	private ScoreType _score; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f37c9c VA: 0x759454fc9c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f37d04 VA: 0x759454fd04
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f37e60 VA: 0x759454fe60
	public Void .ctor() { }
}
```