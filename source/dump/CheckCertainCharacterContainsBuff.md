# CheckCertainCharacterContainsBuff

**Namespace:** ` `


## Fields

- `String _targetKey`

- `String _buffKey`

- `Boolean _loadFromBlackboard`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCertainCharacterContainsBuff : ActionNode
{
	private String _targetKey; // 0x10
	private String _buffKey; // 0x18
	private Boolean _loadFromBlackboard; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1dd30 VA: 0x7594535d30
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1dd98 VA: 0x7594535d98
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1dec4 VA: 0x7594535ec4
	public Void .ctor() { }
}
```