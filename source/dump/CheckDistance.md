# CheckDistance

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `Single _radius`

- `String _radiusBbKey`

- `Boolean _checkCertainPosition`

- `String _rowKey`

- `String _colKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckDistance : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private Single _radius; // 0x18
	private String _radiusBbKey; // 0x20
	private Boolean _checkCertainPosition; // 0x28
	private String _rowKey; // 0x30
	private String _colKey; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f30a30 VA: 0x7594548a30
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f30a98 VA: 0x7594548a98
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f30d48 VA: 0x7594548d48
	public Void .ctor() { }
}
```