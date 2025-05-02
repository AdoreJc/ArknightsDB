# FinishBuffsByIdFromBlockee

**Namespace:** ` `


## Fields

- `String _buffKey`

- `Boolean _loadFromBlackboard`

- `Boolean _decCntIfStack`

- `Boolean _updateOverrideMap`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishBuffsByIdFromBlockee : ActionNode
{
	private String _buffKey; // 0x10
	private Boolean _loadFromBlackboard; // 0x18
	private Boolean _decCntIfStack; // 0x19
	private Boolean _updateOverrideMap; // 0x1a
	private ActionTargetType _targetType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef75bc VA: 0x759450f5bc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef7624 VA: 0x759450f624
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef7b14 VA: 0x759450fb14
	public Void .ctor() { }
}
```