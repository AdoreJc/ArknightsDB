# Act33SideFilterByTargetRopeCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _valueToCompare`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act33SideFilterByTargetRopeCnt : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _valueToCompare; // 0x14
	private CompareType _condType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eded74 VA: 0x75944f6d74
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ededdc VA: 0x75944f6ddc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edf0dc VA: 0x75944f70dc
	public Void .ctor() { }
}
```