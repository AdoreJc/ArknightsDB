# FinishBuffsByIdByBuffSource

**Namespace:** ` `


## Fields

- `String _buffKey`

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `Boolean _alsoClearNullSource`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishBuffsByIdByBuffSource : ActionNode
{
	private String _buffKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private ActionTargetType _sourceType; // 0x1c
	private Boolean _alsoClearNullSource; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef7b94 VA: 0x759450fb94
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef7bfc VA: 0x759450fbfc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef7d64 VA: 0x759450fd64
	public Void .ctor() { }
}
```