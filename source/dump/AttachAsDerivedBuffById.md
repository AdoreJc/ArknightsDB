# AttachAsDerivedBuffById

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _buffKey`

- `Boolean _loadFromBlackboard`

- `Boolean _finishDerivedBuffIfParentFinish`

- `Boolean _attachToSourceHost`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AttachAsDerivedBuffById : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _buffKey; // 0x18
	private Boolean _loadFromBlackboard; // 0x20
	private Boolean _finishDerivedBuffIfParentFinish; // 0x21
	private Boolean _attachToSourceHost; // 0x22
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f03a5c VA: 0x759451ba5c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f03ac4 VA: 0x759451bac4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f03d2c VA: 0x759451bd2c
	public Void .ctor() { }
}
```