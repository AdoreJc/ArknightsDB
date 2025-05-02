# AssignValueToBBWithWeight

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `Int32 _weightNum`

- `Int32 _maxWeight`

- `Boolean _useNum2`

- `Int32 _weightNum2`

- `String _weightNum2Key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignValueToBBWithWeight : ActionNode
{
	public String _blackboardKey; // 0x10
	public Int32 _weightNum; // 0x18
	public Int32 _maxWeight; // 0x1c
	private Boolean _useNum2; // 0x20
	private Int32 _weightNum2; // 0x24
	private String _weightNum2Key; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7c2bc VA: 0x75945942bc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7c324 VA: 0x7594594324
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7c508 VA: 0x7594594508
	public Void .ctor() { }
}
```