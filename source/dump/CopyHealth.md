# CopyHealth

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Boolean _copyByRatio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CopyHealth : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Boolean _copyByRatio; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f359b4 VA: 0x759454d9b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f35a1c VA: 0x759454da1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f35cf8 VA: 0x759454dcf8
	public Void .ctor() { }
}
```