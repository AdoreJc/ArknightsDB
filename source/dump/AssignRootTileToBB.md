# AssignRootTileToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _assignTargetTokenOrHost`

- `String _colKey`

- `String _rowKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignRootTileToBB : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _assignTargetTokenOrHost; // 0x14
	private String _colKey; // 0x18
	private String _rowKey; // 0x20
	private List`1 m_targetTokens; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef2d74 VA: 0x759450ad74
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef2ddc VA: 0x759450addc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef30a8 VA: 0x759450b0a8
	public Void .ctor() { }
}
```