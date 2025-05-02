# FinishOneBuffById

**Namespace:** ` `


## Fields

- `String _buffKey`

- `Boolean _loadFromBlackboard`

- `ActionTargetType _targetType`

- `Boolean _checkBuffFinished`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishOneBuffById : ActionNode
{
	private String _buffKey; // 0x10
	private Boolean _loadFromBlackboard; // 0x18
	private ActionTargetType _targetType; // 0x1c
	private Boolean _checkBuffFinished; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef69f8 VA: 0x759450e9f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef6a60 VA: 0x759450ea60
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef6be4 VA: 0x759450ebe4
	public Void .ctor() { }
}
```