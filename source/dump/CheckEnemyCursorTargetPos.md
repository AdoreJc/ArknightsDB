# CheckEnemyCursorTargetPos

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Int32 _cursorIndexOffset`

- `String _rowKey`

- `String _colKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyCursorTargetPos : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Int32 _cursorIndexOffset; // 0x14
	private String _rowKey; // 0x18
	private String _colKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f30e0c VA: 0x7594548e0c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f30e74 VA: 0x7594548e74
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f31040 VA: 0x7594549040
	public Void .ctor() { }
}
```