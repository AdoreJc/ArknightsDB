# AssignFinishedBossWaveIntoBlackBoard

**Namespace:** ` `


## Fields

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignFinishedBossWaveIntoBlackBoard : ActionNode
{
	private String _blackboardKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef5b7c VA: 0x759450db7c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef5be4 VA: 0x759450dbe4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef5d74 VA: 0x759450dd74
	public Void .ctor() { }
}
```