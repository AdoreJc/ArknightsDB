# AssignValueToBB

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `Single _value`

- `String _copyFromKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignValueToBB : ActionNode
{
	private String _blackboardKey; // 0x10
	private Single _value; // 0x18
	private String _copyFromKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef117c VA: 0x759450917c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef11e4 VA: 0x75945091e4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef12f4 VA: 0x75945092f4
	public Void .ctor() { }
}
```