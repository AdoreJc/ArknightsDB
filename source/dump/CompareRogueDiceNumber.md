# CompareRogueDiceNumber

**Namespace:** ` `


## Fields

- `Int32 _threshold`

- `CompareType _condType`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CompareRogueDiceNumber : ActionNode
{
	private Int32 _threshold; // 0x10
	private CompareType _condType; // 0x14
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7d334 VA: 0x7594595334
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7d39c VA: 0x759459539c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7d6a4 VA: 0x75945956a4
	public Void .ctor() { }
}
```