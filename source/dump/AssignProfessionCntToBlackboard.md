# AssignProfessionCntToBlackboard

**Namespace:** ` `


## Fields

- `ProfessionCategory _professionCategory`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignProfessionCntToBlackboard : ActionNode
{
	private ProfessionCategory _professionCategory; // 0x10
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef316c VA: 0x759450b16c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef31d4 VA: 0x759450b1d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef360c VA: 0x759450b60c
	public Void .ctor() { }
}
```